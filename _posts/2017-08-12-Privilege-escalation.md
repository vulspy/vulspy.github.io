---
layout: post
author: AMBULONG@VULSPY
title: ! 'Local Privilege Escalation Tips'
---

# PHP SESSION

* phpMyAdmin
* ownCloud

# PHP Disable Functions Bypass

* Shellshock(CVE-2014-6271)
* Imagemagick
* Ghostscript
* FFmpeg

# Port

* 1099 - Java RMI (Java Deserialization RCE)
* 2375 - Docker Remote API
* 6379 - Redis
* 8161 - ActiveMQ (CVE-2016-3088)
* 9000 - PHP-CGI/FastCGI RCE
* 9001 - Supervisord (CVE-2017-11610)
* 11211 - Memcached
* 27017 - MongoDB
* 27018 - MongoDB
* 27019 - MongoDB

# Service

* Shellshock (CVE-2014-6271)
  * CGI-based web server
  * DHCP
  * Git/Subversion
  * Qmail
  * OpenSSH

* Cisco Prime Infrastructure (CVE-2016-1291)
[CoalfireLabs/java_deserialization_exploits](https://github.com/CoalfireLabs/java_deserialization_exploits)

* IBM WebSphere (CVE-2015-7450)
[CoalfireLabs/java_deserialization_exploits](https://github.com/CoalfireLabs/java_deserialization_exploits)

* OpenNMS Java Object Deserialization RCE
[CoalfireLabs/java_deserialization_exploits](https://github.com/CoalfireLabs/java_deserialization_exploits)

* Jenkins CLI (CVE-2015-8103)
[CoalfireLabs/java_deserialization_exploits](https://github.com/CoalfireLabs/java_deserialization_exploits)

* Jenkins Groovy XML RCE (CVE-2016-0792)
[CoalfireLabs/java_deserialization_exploits](https://github.com/CoalfireLabs/java_deserialization_exploits)

* Oracle WebLogic Server (CVE-2016-3510)
[CoalfireLabs/java_deserialization_exploits](https://github.com/CoalfireLabs/java_deserialization_exploits)

* Jenkins Unauthenticated Code Execution (CVE-2017-1000353)
[SSD Advisory – CloudBees Jenkins Unauthenticated Code Execution](https://blogs.securiteam.com/index.php/archives/3171)

* JBOSS

* Struts 2 RCE
  * S2-001
  * S2-003 
  * S2-005 (CVE-2010-1870)
  * S2-007
  * S2-008
  * S2-009 (CVE-2011-3923)
  * S2-012 (CVE-2013-1965)
  * S2-013 (CVE-2013-1966)
  * S2-015 (CVE-2013-2135, CVE-2013-2134)
  * S2-016 (CVE-2013-2251)
  * S2-019 (CVE-2013-4316)
  * S2-020 (CVE-2014-0094)
  * S2-021 (CVE-2014-0112, CVE-2014-0113)
  * S2-022 (CVE-2014-0116)
  * S2-029 (CVE-2016-0785)
  * S2-032 (CVE-2016-3081)
  * S2-033 (CVE-2016-3087)
  * S2-036 (CVE-2016-4461)
  * S2-037 (CVE-2016-4438)
  * S2-045 (CVE-2017-5638)
  * S2-046 (CVE-2017-5638)
  * S2-048 (CVE-2017-9791)
  * S2-devMode


* Apache Tomcat

# PATH

* PHP SESSION SAVE PATH
  * /tmp
  * /var/lib/php/
  * /var/lib/php5/
  * /var/lib/php/sessions/
  * /var/lib/php5/sessions/
* NGINX CONFIG
  * /usr/local/nginx/conf/nginx.conf 
  * /usr/local/nginx/nginx.conf
  * /etc/nginx/nginx.conf
* APACHE CONFIG
  * /etc/httpd/conf/httpd.conf
  * /usr/local/apache/conf/httpd.conf
  * /usr/local/apache2/conf/httpd.conf
  * /etc/httpd/conf.d
  * /etc/apache2/conf/httpd.conf
  * /etc/apache2/httpd.conf
  * /etc/apache2/sites-available/000-default.conf
  * /etc/apache2/sites-enabled/000-default.conf
  * /apps/apache/conf/httpd.conf
  * /apps/apache2/conf/httpd.conf
  * /etc/httpd/conf.d/vhosts.conf
* PHP INI
  * /etc/php.ini
  * /etc/php/7.0/cli/php.ini
  * /etc/php/7.0/fpm/php.ini
  * /etc/php5/apache2/php.ini
  * /etc/php5/cli/php.ini
  * /usr/local/php/etc/php.ini
  * /usr/local/Zend/etc/php.ini
  * /usr/local/php/lib/php.ini
* OTHER
  * /etc/passwd
  * /etc/shadow
  * /etc/group
  * /etc/gshadow
  * /etc/rc.local
  * /etc/issue
  * /etc/issue.net
  * /proc/version
  * /proc/self/environ
  * /etc/sysconfig/network-scripts/ifcfg-eth0
  * /etc/init.d/httpd
  * /etc/init.d/mysqld
  * /etc/syslog.conf
  * /var/log/yum.log
  * /etc/sysconfig/iptables-config
  * /var/log/cron
  * .bash_history
  * .mysql_history
  * .viminfo
  * /etc/vsftpd/vsftpd.conf
  * /etc/logrotate.d/vsftpd.log
