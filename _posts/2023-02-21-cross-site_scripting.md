---
title: Cross-site scripting
categories:
- cyber
feature_text: |
  #
---
- [Cross-site scripting (XSS)](#cross-site-scripting-xss)
- [Background](#background)
- [References](#references)
- [External Link](#external-link)

## Cross-site scripting (XSS)

Is a type of security vulnerability that can be found in some web applications. XSS attacks enable attackers to inject-side scripts into web pages viewed by others users. A cross-site scripting vulnerability may be used by attackers to bypass access controll such as the same-origin policy. Cross-site scripting carried out on websites accounted for roughly 84% of all security vulnerabilities documented by Symentec up until 2005. XSS effects vary in range from petty nuisance to significant security risk, depending on the sensitivity of the data handled by the vulnerable site the nature of any security mitigation implemented by site's owner network.  

## Background

Security on the web depends on a variety of mechanisms, including an underlying concepts of trust known as the same-origin policy. This essentially states that if content from one site (such as https://mybank.com) is granted permission to access resources (like cookies etc.) on a web browser, then content from  any URL with the same URL scheme, host name, and port number will share these permissions. Content from URLs where any of these attributes are different will have to be granted permissions separately.  
Cross-site scripting attacks use known vulnerabilities in web-based applications, their servers, or the plud-in systems on which thel rely. Exploiting one of these, attackers fold malicious content into the content being delivered from the compromised site. When the resulting combined content arrives at the client site web browser, it has all been delivered from the trusted source, and thus operates under the permissions granted to that system. By finding ways of injecting malicious scripts into web pages, an attacker can gain elevated access-privileges to sensitive page content, to session cookies, and to a variety of other informations maintained by the browser on behalf of the user. Cross-site scripting attacks are a case of code injection.  
Microsoft security-engineers introduced the term "cross site scripting" in january 2000. The expression "cross-site scripting" originally referred to the act of loading the attacked, third-party web application from an unrelated attack-site, in a manner that executes a fragment of JavaScript prepared by attacker in the security context of the targeted domain (taking advantage of a reflected or non-persistent XSS vulnerability). The definition gradually expanded to encompass other modes of code injection, including persistent and non-JavaScript vectors (including ActiveX, Java, VBScript, Flash, or even HTML scripts), causing some confusion to newcomers to the field of information security.

## References

[wiki link](https://en.wikipedia.org/wiki/Cross-site_scripting) by wikipedia.

## External Link

[SQL Injection Knowledge Base](https://www.websec.ca/kb/sql_injection) by Websec.