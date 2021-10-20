---
layout: page
title: About
nav_order: 1
permalink: /about
---

## [OWASP](https://www.owasp.org) Threat Dragon

[Threat Dragon](http://owasp.org/www-project-threat-dragon) is a free, open-source, 
cross-platform [threat modeling](https://owasp.org/www-community/Threat_Modeling)
application including system diagramming and a rule engine to auto-generate threats/mitigations.
Threat Dragon supports STRIDE<sup>[1](#footnote1)</sup>, LINDUN<sup>[2](#footnote2)</sup> and CIA<sup>[3](#footnote3)</sup>.

It is an [OWASP Lab Project](https://owasp.org/www-project-threat-dragon/)
and follows the values and principles of the threat modeling [manifesto](https://www.threatmodelingmanifesto.org/).
The roadmap for the project is a great UX, a powerful rule engine and integration with other development lifecycle tools.

There is a good overview of [threat modeling and risk assessment](https://owasp.org/www-community/Application_Threat_Modeling)
from OWASP, and this expands on what the Threat Dragon project aims for: 
* designing the data flow diagram
* automatic determining and ranking threats
* suggested mitigations
* entry of mitigations and counter measures

The application comes in two variants:

1. [**A desktop application**](https://github.com/OWASP/threat-dragon/releases): This is based on
[Electron](https://electron.atom.io/), with model files stored on the local filesystem.
There are installers available for both Windows and Mac OSX, as well as rpm and debian packages for Linux.

1. [**A web application**](https://github.com/owasp/threat-dragon/releases): For the web application model files
are stored in GitHub, with other storage methods to follow.

<sup><a name="footnote1">1</a>: Spoofing, Tampering, Repudiation, Information disclosure, DoS, Elevation of privilege</sup><br>
<sup><a name="footnote2">2</a>: Linkability, Identifiability, Non-repudiation, Detectability, Disclosure of information, Unawareness, Non-compliance</sup><br>
<sup><a name="footnote3">3</a>: Confidentiality, Integrity, Availability</sup><br>
