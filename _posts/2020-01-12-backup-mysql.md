---
layout: post
title: "Backup mysql database"
description: ""
tags: "python, mysql, backup"

---
## backup database
```
root@rd:/home/pi/apps# cat backup-mysql.py
#!/usr/bin/python
#Importing the modules
import os
import ConfigParser
import time

# On Debian, /etc/mysql/debian.cnf contains 'root' a like login and password.
config = ConfigParser.ConfigParser()
config.read("/etc/mysql/debian.cnf")
username = config.get('client', 'user')
password = config.get('client', 'password')
hostname = config.get('client', 'host')
filestamp = time.strftime('%Y-%m-%d')

# Get a list of databases with :
database_list_command="mysql -u %s -p%s -h %s --silent -N -e 'show databases'" % (username, password, hostname)
for database in os.popen(database_list_command).readlines():
    database = database.strip()
    if database == 'information_schema':
        continue
    if database == 'performance_schema':
        continue
    filename = "/home/pi/apps/%s-%s.sql" % (database, filestamp)
    os.popen("mysqldump --single-transaction -u %s -p%s -h %s -d %s | gzip -c > %s.gz" % (username, password, hostname, database, filename))
root@rd:/home/pi/apps#

```

```
root@rd:/home/pi/apps#chmod +x backup-mysql.py
root@rd:/home/pi/apps#./backup-mysql.py
````