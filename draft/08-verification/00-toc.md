---

title: Verification
layout: col-document
tags: OWASP Developer Guide
contributors: Jon Gadsden
document: OWASP Developer Guide
order:

---

{% include breadcrumb.html %}

## 6. Verification

[Verification][sammv] is one of the business functions described by the [OWASP SAMM][samm].

Verification focuses on the processes and activities related to how an organization checks
and tests artifacts produced throughout software development.
This typically includes quality assurance work such as testing,
but it can also include other review and evaluation activities.

Verification activities should include:

* Architecture assessment, validation and mitigation
* Requirements-driven testing including security control verification and misuse/abuse testing
* Automated security testing and baselining
* Manual security testing and penetration testing

These activities are supported by:

* Security guides
* Test tools
* Test frameworks
* Vulnerability management
* Checklists

Sections:

6.1 [Guides](#verification-guides)  
6.1.1 [Web Security Testing Guide](#web-security-testing Guide)  
6.1.2 [Mobile Application Security](#mobile-application-security)  
6.1.3 [Application Security Verification Standard](#application-security-verification-standard)  
6.2 [Tools](#verification-tools)  
6.2.1 [Zed Attack Proxy](#zed-attack-proxy)  
6.2.2 [Code Pulse](#code-pulse)  
6.2.3 [Amass](#amass)  
6.2.4 [Offensive Web Testing Framework](#offensive-web-testing-framework)  
6.2.5 [Nettacker](#nettacker)  
6.2.6 [OWASP Secure Headers Project](#secure-headers-project)  
6.3 [Frameworks](#verification-frameworks)  
6.3.1 [Glue](#glue)  
6.3.2 [secureCodeBox](#securecodebox)  
6.3.3 [Dracon](#dracon)  
6.4 [Vulnerability management](#verification-vulnerability-management)  
6.4.1 [DefectDojo](#defectdojo)  
6.5 [Do's and Don'ts](#verification-dos-and-donts)
6.5.1 [Secure environment](#secure-environment)  
6.5.2 [System hardening](#system-hardening)  
6.5.3 [Open Source software](#open-source-software)  

----

The OWASP Developer Guide is a community effort; if there is something that needs changing then [submit an issue][issue0800].

[issue0800]: https://github.com/OWASP/www-project-developer-guide/issues/new?labels=enhancement&template=request.md&title=Update:%2008-verification/00-toc
[samm]: https://owaspsamm.org/about/
[sammv]: https://owaspsamm.org/model/verification/

\newpage
