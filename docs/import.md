---
layout: default
title: Install packages
nav_order: 2
---

# Install packages
{: .no_toc }

When do python develping or engineering, people may need to use many packages. To use these packages, need to make sure they are already installed. There are two ways to install packages using in PyCharm. This file will tell you the steps to install a new pacakage by using pandas as a example.

{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Pre-requisites
Before importing package, make sure you have met the following requirements:
* You have installed the Python downloaded from [https://www.python.org](https://www.python.org).
* You have opened an existing project or created a new project.

>![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>> **Note**: You may meet an error when installing packages if your pip version is too old. In this case, just update your pip in terminal to fix the error. Code in terminal: `python -m pip install -U pip `
<br />
<br />

## Instructions

Step 1. Click **PyCharm** in the upper left corner of your screen, then click **Perference**. You can also just press Cmd, (⌘,).  
![step1](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/1.png?raw=true "step one")  

you will see a new window poped out show as below.  

 ![new poped window](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/1.9.png?raw=true "new poped window") 

<br>
Step 2. Click **Python Interpreter** under **Project:fileName** to see the winder where you can either install, or unstall, or update your package. Some people may see a lot of packages installed like show in this picture below, some people may see an empaty page because there is no packaged installed before.  

![find Python Interpreter](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/2_0.png?raw=true "find Python Interpreter") 


Step 3. Click **+** in the bottom right corner   
![click add](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/3.png?raw=true "click add")

a new window will be poped out where you can search for the package you want to install
![new window](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/3_5.png?raw=true "new window")


Step4. Under the search bar, type in the package name, and find the package in the left bar. Here I typed package *Pandas*.  
![find package](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/4_0.png?raw=true "find package")

Step5. click **Install Package** to install
![Install Package button](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/5.png?raw=true "Install Package button")


Step6. There will be a message show above the **Install Package** button, saying Pacakge 'pacakge name' installed sucessfully, which means the was sucessfully installed
![message](https://raw.githubusercontent.com/Dani-j/team2-pycharm/gh-pages/assets/images/docs/package/6_1.png?raw=true "message")



tips: other ways to check if installed already.

install by pip??

Congratulations! You have learnt how to optimize your Python application using Pycharm. If you have any issues, check out troubleshooting.
