---
title: Brutal Force Attack
categories:
- cyber
feature_text: |
  SQL injection is mostly known as an attack vector for websites but can be used to attack any  type of SQL database.
---

## Brutal-force attack

In cryptography, a brute-force atttack consists of an attacker submiting many passwords or passphrases with hope of eventually gussing correctly. The attacker systematiclly checks all possible passwords and passphrases until the correct one is found. Alternatively, the attacker can attempt to guess the key which is typically created from the password using a key derivation function. This is known as an **exhaustive key search**.

## Prevent/Countermeasures

In case of an *offline* attack where the attacker has gained access to the encrypted material, one can try key combinations without the risk of discovery or interference. In case of *online* attacks, database and directory administrators can deploy countermeasures such as limiting the number of attempts that a password can be tried, introducing time delays between successive attempts, increasing the answear's complexity (e.g, requiring a **CAPTCHA** answer or employing multi-factor authentication), and/or locking account out after unsuccessful login attempts. Website administrators may prevent a particular IP address from trying more than a predetermined number of passwords attempts against any account on the site.

## References

[wiki link](https://en.wikipedia.org/wiki/SQL_injection) by wikipedia.

## External Link

[SQL Injection Knowledge Base](https://www.websec.ca/kb/sql_injection) by Websec.
