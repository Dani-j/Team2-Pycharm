---
layout: default
title: Troubleshooting
nav_order: 6
---

# Troubleshooting

---

|  Symptoms  | Probable cause  | Action |
| :----------| :----------------| :--------|
|Pop up error after clicking `Install Package`|Pip version is too old, or pip is not avaliable for PyCharm| Code in terminal: `python -m pip install --upgrade pip` to update pip. Code in terminal: `<path to the python executable>\python.exe -m ensurepip --default-pip` to make pip avaliable for Pycharm. For example: `C:\Python27\python.exe -m ensurepip --default-pip`|
|Debugger takes too much time to run|Debugger stops after each thrown exception, even when the exception is caught and the process did not terminate|Uncheck the **On raise** checkbox within the breakpoints window|
|**Debug** button is not available for Docker configuration|yCharm debugs Python configurations|First, initialize a Docker-based interpreter, then, put your Python code in a Docker container and debug.|
| 空白 | 空白 | 空白|
| 空白 | 空白 | 空白|
| 空白 | 空白 | 空白|
{: style="width: 700px" }
