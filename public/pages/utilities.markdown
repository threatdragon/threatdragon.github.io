---
layout: page
title: Utilities
permalink: /utils/
nav_order: 8
---

## [OWASP](https://www.owasp.org) Threat Dragon

### Utilities

Threat Dragon has a growing collection of utilities and scripts which can be used to
convert file formats, interface to bug tracking, and so on.
If you have scripts of your own that you would like to contribute to the Threat Dragon
community then this would be most  welcome, see the [contributing guide](/contribute/).

### Conversion from Microsoft Threat Modeling Tool

The [TMT2TD python script](https://github.com/OWASP/threat-dragon/blob/main/utils/TMT2TD/TMT2TD.py)
converts an Microsoft Threat Modeling Tool file `.tm7` file to a Threat Dragon `.json` file.

Run the script using python and select the TM7 file, the script will then output a
file with the same name but using a `.json` extension.
Included [with the script](https://github.com/OWASP/threat-dragon/tree/main/utils/TMT2TD)
is an example TM7 file and the transpiled Threat Dragon file.

```
threat-dragon$ python --version
Python 3.9.5
threat-dragon$ python tmt2td.py
```
