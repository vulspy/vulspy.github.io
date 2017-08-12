---
layout: post
author: AMBULONG@VULSPY
title: ! 'SSRF And URL Related TIPS'
---

#SSRF Related Tips

## Vulnerabilities

* Weblogic SSRF
* DokuWiki
  * [DokuWiki fetch.php SSRF漏洞与tok安全验证绕过分析](http://paper.seebug.org/230/)
* Atlassian Confluence (CVE-2016-6595)
  * [Confluence任意文件读取漏洞以及CVE-2016-6596 SSRF漏洞分析](http://xdxd.love/2016/06/03/confluence%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/)
* Discuz SSRF
  * Discuz + Memcache
  * Discuz + Redis 
* vBulletin SSRF
  * vBulletin + Memcache
  * vBulletin + Redis
* Password Crack
  * FTP/FTPS
  * IMAP/IMAPS/POP3/SMTP
  * TELNET
  * SSH

## Exploits

* Redis
* Memcache
* Mongodb
* PHP-CGI/FastCGI
* Struts 2
* Counchdb WEB API
* Atlassian Confluence
  * [Atlassian Confluence 5.2/5.8.14/5.8.15 - Multiple Vulnerabilities](https://www.exploit-db.com/exploits/39170/)
  * [Confluence任意文件读取漏洞以及CVE-2016-6596 SSRF漏洞分析](http://xdxd.love/2016/06/03/confluence%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90/)
* Axis2
* Glassfish
* JBOSS
* Docker Remote API
* Java RMI
* Elasticsearch Groovy
* WebDav PUT
* WebSphere
* Apache Hadoop
* HFS
* zentoPMS

## Tools

* (bcoles/ssrf_proxy)[https://github.com/bcoles/ssrf_proxy]

## Posts
* [利用 Gopher 协议拓展攻击面 - 长亭科技](https://blog.chaitin.cn/gopher-attack-surfaces/)
* [A New Era of SSRF - Exploiting URL Parser in Trending Programming Languages! - Orange](https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf)
* [How I Chained 4 vulnerabilities on GitHub Enterprise, From SSRF Execution Chain to RCE! - Orange](http://blog.orange.tw/2017/07/how-i-chained-4-vulnerabilities-on.html)
* [Port scanning with Server Side Request Forgery (SSRF) - IAN MUSCAT](https://www.acunetix.com/blog/articles/ssrf-vulnerability-used-to-scan-the-web-servers-network/)
* [Build Your SSRF Exploit Framework - ring04h](https://github.com/ring04h/papers/blob/master/build_your_ssrf_exp_autowork--20160711.pdf)
