---

title: OWASP Bug Logging Tool (BLT)
layout: col-document
tags: OWASP Developer Guide
contributors:
document: OWASP Developer Guide
order: 1320
permalink: /draft/security_gap_analysis/bug_logging_tool/

---

{% include breadcrumb.html %}

### 11.2 Bug Logging Tool

The OWASP [Bug Logging Tool][blt] (BLT) is a community database of bugs found in an organization's web site or application.
BLT is an OWASP Production tool project and has its own [bug recording site][bltsite].

#### What is BLT?

BLT is a bug recording and bounty tool that allows external users to register and advise
about bugs in an organization's web site or application.
It allows an organization to run a bug bounty program without having to go through a commercial provider.

The [BLT core project][bltcore] provides a development server docker image that can be used for the
bug bounty program.
The [BLT-Flutter application][bltapp] provides an integrated method for reporters/users to report bugs.
The [BLT Extension][bltchrome] is a Chrome extension that helps BLT reporters/users
to take screenshots and add them to a BLT website.

#### Why use it?

Bug bounty programs are an important path for reporting security bugs to an organization.
These programs can be paid-for services provided by commercial companies, or they can be provided by
the company / organization itself; and this is where BLT can help.

External reporters of bugs in web sites and applications are a valuable way of identifying security
related bugs and issues; it provides a diverse range of individuals to hunt for bugs.
BLT can provide the route for these security bugs to be responsibly disclosed to the organization.

#### How to use it

BLT has its own [bug recording site][bltsite] which can be used to disclose bugs in any web site.
Ideally this is not used for security related bugs because these bugs need responsible disclosure.
The organization should run its own [BLT core site][bltcore] to accept submission of security related bugs,
and encourage users/reporters to use the [BLT app][bltapp] and chrome [extension][bltchrome].

----

The OWASP Developer Guide is a community effort; if there is something that needs changing
then [submit an issue][issue1102] or [edit on GitHub][edit1102].

[blt]: https://owasp.org/www-project-bug-logging-tool/
[bltchrome]: https://github.com/OWASP/BLT-Extension
[bltcore]: https://github.com/OWASP/BLT
[bltapp]: https://github.com/OWASP/BLT-Flutter
[bltsite]: https://blt.owasp.org/
[edit1102]: https://github.com/OWASP/www-project-developer-guide/blob/main/draft/13-security-gap-analysis/02-blt.md
[issue1102]: https://github.com/OWASP/www-project-developer-guide/issues/new?labels=content&template=request.md&title=Update:%2013-security-gap-analysis/02-blt

\newpage
