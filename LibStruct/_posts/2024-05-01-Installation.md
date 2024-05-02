---
layout: post
author: korax
title: LibStruct- Installation
---

## Requirements:
### OS:
Linux, Windows (XP or higher 64-bit Windows), MacOS, Mac OS X, FreeBSD, NetBSD, OpenBSD, BSD/OS, Solaris, IRIX and QNX.

### Software:

1. Python Version:
+ Supported: 3.2 or above
+ Recommended: 3.11.6 or above
2.  Pygame Version:
		Tested on version 2.5.0
3. MySQL Version:
		Tested on verion 8.1

### CPU:
- Supported: Any Multicore 64-bit CPU
- Recommended: Intel Core i3 3240 or equivalent AMD Processor


## Steps to install LibStruct/LibStruct-GUI
1. Install latest version of Python from [Python's Website](https://www.python.org/downloads/)
2. Install Pygame (Not required for [CLI version](https://github.com/koraxial/LibStruct/LibStruct_cli.py)):
   > 1) Open Python install directory </br>
   > 2) Open Command Prompt in folder </br>
   > 3) Run 'python -m pip install pygame'
3. Install MySQL from [MySQL's Page](https://dev.mysql.com/downloads/installer/#:~:text=MySQL%20Installer%208.0.35,final%20series%20with%20MySQL%20Installer.)
4. Install mysql-connector-python:
   > 1) Open Python install directory </br>
   > 2) Open Command Prompt in folder </br>
   > 3) Run 'python -m pip install mysql-connector-python'
5. Download the latest release package from [GitHub](https://github.com/koraxial/LibStruct/releases)
6. Run [LibStruct_SQLdepCreate.py](https://github.com/koraxial/LibStruct/LibStruct_SQLdepCreate.py)
7. Run [LibStruct_main.py](https://github.com/koraxial/LibStruct/LibStruct-GUI/LibStruct_main.py)

<div class="note">
  <p><strong>**Note:**</strong>Replace the '########' in 'LibStruct_SQLdepCreate.py', 'LibStruct_main.py' and 'LibStruct_cli.py' before running the program. </p>
</div> 
   

## Troubleshooting: 
In case of any errors or compatibility issues try the following:

1) Reinstall Python or Pygame or MySQL, or try different versions. </br>
2) Check MySQL table structure. </br>
3) Check connectivity of program with database.

<a href="https://koraxial.github.io/libstruct/2024/05/01/About.html"><-- About & Features</a>
<h2 align="center">..........</h2>
