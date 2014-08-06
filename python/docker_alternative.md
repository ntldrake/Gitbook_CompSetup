# Docker Alternative

*Note: This section is still a work in process. I haven't fully tested this out myself yet.*

## Background
Most Python developers use *virtualenv* when developing Python applications, which provides an easy-to-use mechanism for enabling application specific dependencies that may clash with other applications or the OS (most notably the version of Python being used, but also specific versions of libraries etc). Personally, I’ve never been a big fan of virtualenv, for the following reasons:

* I often forget to enable it which leads to a confused moment while I stare at an obscure error, or I forget to change virtualenv when changing project
* It doesn’t provide “true” isolation; only Python level (system libraries and non-python dependencies will still cause issues)
* I typically don’t want to run virtualenv in production, which means I immediately have a mismatch between development and production
* It always felt a bit “hacky”; relying on modifying scripts and setting up new paths

So, how does Docker make any of this better? Docker essentially provides very lightweight VMs (“containers” in the parlance) which we can use to create a high level of isolation and vastly reduce the mismatch between development and production environments.

---
Sourced From:

* http://continuousdelivery.uglyduckling.nl/uncategorized/using-docker-as-a-python-development-environment/
