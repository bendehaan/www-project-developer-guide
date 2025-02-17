---

title: ModSecurity Web Application Firewall
layout: col-document
tags: OWASP Developer Guide
contributors:
document: OWASP Developer Guide
order: 1103
permalink: /draft/operation/modsecurity_waf/

---

{% include breadcrumb.html %}

### 9.3 ModSecurity Web Application Firewall

[ModSecurity][modsecurity] is an open source Web Application Firewall (WAF) widely deployed on web servers.
It is an OWASP Production project and has been in continuous development and widespread use since 2002.

#### What is ModSecurity?

In January 2024 the [ModSecurity][modsecurity] Web Application Firewall project was [adopted by OWASP][modsecpress],
previously [TrustWave][trustwave] had been the custodian of this project.
ModSecurity itself has a long history as an open source project, the first release was in November 2002,
and is widely used as a web application firewall for cloud and on-premises web servers.

The ModSecurity WAF needs to be configured in operational deployments,
and this can be done using the OWASP ModSecurity [Core Rule Set][modcrs].

#### Why use ModSecurity?

Web Application Firewalls are often the first line of defense against HTTP attacks on web applications and servers.
The ModSecurity WAF is widely used for this purpose along with the [Coraza WAF][coraza], also provided by OWASP.

#### How to use ModSecurity

ModSecurity is deployed as a Web Application Firewall, which scans the incoming and outgoing HTTP traffic to a web server.
The ModSecurity WAF is deployed as a proxy server in front of a web application,
or deployed within the web server itself, to provide protection against HTTP attacks.

The rules applied to the HTTP traffic are provided as configuration to ModSecurity,
and these rules allow many different actions to be applied such as blocking traffic, redirecting requests, and many more.
See the documentation for [deploying and running][modsecdocs] ModSecurity,
along with the documentation on configuring ModSecurity with the [Core Rule Set][modcrsdocs].

----

The OWASP Developer Guide is a community effort; if there is something that needs changing
then [submit an issue][issue1103] or [edit on GitHub][edit1103].

[coraza]: https://coraza.io/
[edit1103]: https://github.com/OWASP/www-project-developer-guide/blob/main/draft/11-operation/03-modsecurity.md
[issue1103]: https://github.com/OWASP/www-project-developer-guide/issues/new?labels=content&template=request.md&title=Update:%2011-operation/03-modsecurity
[modcrs]: https://owasp.org/www-project-modsecurity-core-rule-set/
[modcrsdocs]: https://coreruleset.org/
[modsecdocs]: https://www.modsecurity.org/
[modsecurity]: https://owasp.org/www-project-modsecurity/
[modsecpress]: https://owasp.org/blog/2024/01/09/ModSecurity.html
[trustwave]: https://www.trustwave.com/

\newpage
