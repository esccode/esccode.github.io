---
layout: post
title: Bash Shell Script
tags:
- linux, bash
---

[Bash Shell Script](https://linuxconfig.org/bash-scripting-tutorial)

```
$ which bash
```

```
#!/bin/bash
# declare STRING variable
STRING="Hello World"
#print variable on a screen
echo $STRING
```

```
$ chmod +x hello_world.sh
./hello_world.sh
 ```
## Simple Backup bash shell script

```
#!/bin/bash
tar -czf home_pi_apps.tar.gz /home/pi/apps
```
```
$ chmod +x backup.sh
$ ./backup.sh
```
