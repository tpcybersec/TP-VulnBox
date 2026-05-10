<div align="center">
	<h1>TP-VulnBox - PyPI</h1>
	<i>VulnBox is a container that is intentionally designed with vulnerabilities to allow security professionals to practice and improve their offensive security skills, such as penetration testing and vulnerability assessment</i>
	<br><br>
	<a href="https://github.com/TPCyberSec/TP-VulnBox/releases/"><img src="https://img.shields.io/github/release/TPCyberSec/TP-VulnBox" height=30></a>
	<a href="#"><img src="https://img.shields.io/github/downloads/TPCyberSec/TP-VulnBox/total" height=30></a>
	<a href="#"><img src="https://img.shields.io/github/stars/TPCyberSec/TP-VulnBox" height=30></a>
	<a href="#"><img src="https://img.shields.io/github/forks/TPCyberSec/TP-VulnBox" height=30></a>
	<a href="https://github.com/TPCyberSec/TP-VulnBox/issues?q=is%3Aopen+is%3Aissue"><img src="https://img.shields.io/github/issues/TPCyberSec/TP-VulnBox" height=30></a>
	<a href="https://github.com/TPCyberSec/TP-VulnBox/issues?q=is%3Aissue+is%3Aclosed"><img src="https://img.shields.io/github/issues-closed/TPCyberSec/TP-VulnBox" height=30></a>
    <br>
    <a href="#"><img src="https://img.shields.io/pypi/v/TP-VulnBox" height=30></a>
	<a href="#"><img src="https://img.shields.io/pypi/pyversions/TP-VulnBox" height=30></a>
	<a href="#"><img src="https://img.shields.io/pypi/dm/TP-VulnBox" height=30></a>
</div>

---
# 🛠️ Installation
#### From PyPI:
```console
pip install TP-VulnBox
```
#### From Source:
```console
git clone https://github.com/TPCyberSec/TP-VulnBox.git --branch <Branch/Tag>
cd TP-VulnBox
python -m build
python -m pip install dist/tp_vulnbox-<version>-py3-none-any.whl
```

---
# 📘 Basic Usage
```
> TP-VulnBox --help

 ____   ____        __            ______
|_  _| |_  _|      [  |          |_   _ \
  \ \   / /__   _   | |  _ .--.    | |_) |   .--.   _   __
   \ \ / /[  | | |  | | [ `.-. |   |  __'. / .'`\ \[ \ [  ]
    \ ' /  | \_/ |, | |  | | | |  _| |__) || \__. | > '  <
     \_/   '.__.'_/[___][___||__]|_______/  '.__.' [__]`\_]


usage: TP-VulnBox [-h] [--list-all] [--start VulnBox_NAME] [--run VulnBox_NAME] [--delete VulnBox_NAME] [--version]

options:
  -h, --help            show this help message and exit
  --list-all            Lists all available VulnBoxes
  --start VulnBox_NAME  Download and run the new VulnBox (e.g. CVE-2024-31211)
  --run VulnBox_NAME    Run an existing VulnBox or run a new VulnBox if not already downloaded (e.g. CVE-2024-31211)
  --delete VulnBox_NAME
                        Delete downloaded VulnBox (e.g. CVE-2024-31211)
  --version             Print the current version of TP-VulnBox

VulnBox is a container that is intentionally designed with vulnerabilities to allow security professionals to practice and improve their
offensive security skills, such as penetration testing and vulnerability assessment.

```