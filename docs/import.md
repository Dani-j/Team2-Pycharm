---
layout: default
title: Install Packages
nav_order: 2
---

# Install Python packages
{: .no_toc }

In this procedure, you will import your first Python package. To develop a python program or implement a function written in Python, programmers usually need to use many packages. To use those packages, programmers need to make sure the packages are already installed and ready for use in PyCharm. By the end of this procedure, you will be able to install any existing python package using Pycharm.

## Pre-requisites
Before importing packages, make sure you have met the following requirements:
* You have installed Python rom [https://www.python.org](https://www.python.org).
* You have PIP installed for Python. If not, pelease click [here](https://phoenixnap.com/kb/install-pip-windows) and follow the instructions to install.
* You have opened an existing project or created a new project.

## Instructions

1. Click **File** in the upper left corner of your screen, then click **Settings**. You can also just press `Ctrl`+`Alt`+`S`.
   
    ![step1](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/1.png?raw=true "step one")  

    You will see the popup window shown below:

    ![new poped window](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/1.9.png?raw=true "new poped window") 

2. Click **Python Interpreter** under **Project:fileName** （here the file name is *Exams*) to open the window where you can see all your installed packages.
   
    ![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
 
    **Note**: Some people may see an empty page if you have never installed a package before.
    <br /> 
    <br>
    <br>

    ![find Python Interpreter](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/2_0.png?raw=true "find Python Interpreter") 


3. Click **+** in the bottom left to choose from the packages available for installation.
   
    ![click add](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/3.png?raw=true "click add")

    A new window will pop up where you can search for the package you want to install:
    ![new window](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/3_5.png?raw=true "new window")


4. In the search bar, type in the package name. Here, the *pandas* package was typed as an example.
   
    ![search package](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/4_0.png?raw=true "search package")


5.  Find the package on the left-hand-side, and click the package you want to install. Make sure the desired package is highlighted in dark blue.
   
    ![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
    
    **Note**: Older versions of PyCharm may have fewer packages available, causing you not to be able to find the package you want.
    <br /> 
    <br /> 
    ![find package](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/pandas.png?raw=true "find package")


6. Click **Install Package** to install   
   
    ![Install Package button](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/5.png?raw=true "Install Package button")


7. There will be a message saying Package ‘package name’ installed successfully. It will be displayed above the  **Install Package** button. If that message appears, it means the package was successfully installed.
   
    ![message](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/6_1.png?raw=true "message")

<br>

![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }

**Note**: You can also install Python packages by pip. Please click [there](https://docs.python.org/3/installing/index.html) to see the details.
<br>
<br>

---
Congratulations! You have learnt how to install Python packages using PyCharm. If you have any issues, check out [Troubleshooting]({{ site.baseurl }}{% link docs/trouble.md %}).
