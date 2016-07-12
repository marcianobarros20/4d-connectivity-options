# 4D Connectivity Options

This repository holds a simple list of  options for connecting to 4D's SQL Server via the 4D SQL Networking Protocol from various programming environments.

---

## Specification

The [4D SQL Networking Protocol][1] is defined on sources.4d.com and is available [here][1]

[1]: http://sources.4d.com/trac/4d_pdo4d/raw-attachment/wiki/WikiStart/SQL%20networking%20protocol.doc

---

## Implementations

This is a list of Implementations for the [4D SQL Networking Protocol][1]:

* C
  * [SQLlib_4D](#sqllib_4d)
* PHP
  * [PDO-4D](#pdo_4d)
  * [ODBC](#odbc) -> PHP::ODBC
* Python
  * [P4D](#p4d)
  * [ODBC](#odbc) -> PYODBC



---

### ODBC

Open Database Connectivity (ODBC) drivers are provided by 4D for Windows and MacOS.

4D does not provide an ODBC driver for Linux.

Download the ODBC drivers from the official 4D download page.  
http://www.4d.com/downloads/products.html

---

### P4D

[P4D](https://github.com/ibrewster/p4d) is a Python database module for the 4D database system. It is written by [Israel Brewster](https://github.com/ibrewster) using the [SQLlib_4D](https://github.com/4D/SQLlib_4D)

https://github.com/ibrewster/p4d

---

### PDO_4D

PDO_4D is a driver for the ​PHP Data Objects (PDO) interface to enable access from PHP to 4D databases.

Main distribution:
http://sources.4d.com/trac/4d_pdo4d

PECL:   
http://pecl.php.net/pdo_4d

Docs:  
http://php.net/pdo_4d   
http://php.net/pdo

Original SVN repository:  
http://svn.php.net/repository/pecl/pdo_4d/

Notable Forks on github:  
https://github.com/famsf/pecl-pdo-4d

---

### SQLlib_4D

SQL library for 4D written in C:  
https://github.com/4D/SQLlib_4D

Notable Forks on github:  
https://github.com/ibrewster/SQLlib_4D

---
