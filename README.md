# fuxploider

[![Python 3.5|3.6](https://img.shields.io/badge/python-3.5%2F3.6-green.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://raw.githubusercontent.com/almandin/fuxploider/master/LICENSE.md)

fuxploider is an open source penetration testing tool that automates the process of detecting and exploiting file upload forms flaws. This tool is able to detect the file types allowed to be uploaded and is able to detect which technique will work best to upload web shells or any malicious file on the desired web server.

Screenshots
----

Installation
----

Coming soon.

Usage
----

To get a list of basic options and switches use :

    python fuxploider.py -h

Basic example :

    python fuxploider.py --url https://awesomeFileUploadService.com --not-regex "wrong file type"


> [!] legal disclaimer : Usage of fuxploider for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program
