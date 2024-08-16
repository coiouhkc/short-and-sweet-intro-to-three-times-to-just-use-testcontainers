---
marp: true
title: Short and sweet intro to 3 times to simply use Testcontainers
description: Short and sweet intro to 3 times to simply use Testcontainers
theme: uncover
paginate: true
_paginate: false



---

# Short and sweet

## 3 times to simply use Testcontainers

Based on real project

---

# Intro, reason & background

* He was an integration/component test
* She was a test container
* Can I make it any more obvious?

---

# 

![images/8vj9bf.jpg](images/8vj9bf.jpg)

---

# Disclaimer

* No disrespect meant, no harm intended
* All tools listed below have their purpose and scope

---

# One

https://github.com/vorburger/MariaDB4j

<!-- Download binaries from official task via Ant wrapped in Maven, Win/*nix only -->

---

# Two

https://github.com/kstyrc/embedded-redis

<!-- Download outdated binaries from GitHub, no native aarch64 for M1/2/3 -->

---

# Three

https://github.com/h2database/h2database

<!-- Misconfiguration lead to H2 being used in PROD -->

<!-- No stored procedure support -->

<!-- hibernate.hbm2ddl_auto=create instead of Flyway -->

---

# Notable mention(s)

https://github.com/stefanbirkner/fake-sftp-server-lambda

<!-- atmoz:sftp, not runnable in Openshift oob -->

---

# Q&A

More?

---

# Notes

<!-- 
https://github.com/coiouhkc/short-and-sweet-intro-to-three-times-to-just-use-testcontainers?tab=readme-ov-file
https://github.com/vorburger/MariaDB4j/blob/main/DBs/mariaDB4j-db-10.11.5/mariaDB4j-db-linux64-10.11.5/prepare.xml
https://github.com/kstyrc/embedded-redis/blob/master/src/main/java/redis/embedded/util/OsArchitecture.java
https://stackoverflow.com/questions/11718865/stored-procedure-in-h2-database
https://hub.docker.com/r/atmoz/sftp
-->