---
layout: default
title: Troubleshooting
nav_order: 6
---

# Troubleshooting

---

|  Symptoms  | Probable cause  | Action |
| :----------| :----------------| :--------|
|Can not remove a directory| The directory you want to remove is not empty | Verify that the directory using `ls` then delete contents using `rm directory`|
| Can not run `sudo` command with newly created user| User not on root user when creating and assigning group privilege | Change to root user with the command `sudo su -`|
| Process not showing up when using `pgrep processname` | The process name does not exist | Verify that the correct keyword is input |
| You cannot see a directory that you create |The `touch` command was mistakenly used | Verify you input the `mkdir` command
|Can not modify contents of a file | Tried to modify non-existent file or used wrong command | Verify that `>` is part of the input when you use the `cat > filename` command
|Could not move my file into a different directory|User tried to move file to non-existent directory or to another file| Verify that the directory exists and is not a file with an extension. Correct syntax is `mv file directory`
{: style="width: 1000px" }

>![Note icon](https://github.com/dl90/linux-basics/blob/gh-pages/docs/images/icons/note.png?raw=true "Note"){: style="float: left" }
>>
>> **Note**: You may meet an error when installing packages if your pip version is too old. In this case, just update your pip in terminal to fix the error. Code in terminal: `python -m pip install -U pip `
<br />
<br />

another importing problem https://stackoverflow.com/questions/51918167/package-installed-but-not-showing-in-the-pycharms-available-packages

for cannot find the package https://stackoverflow.com/questions/51918167/package-installed-but-not-showing-in-the-pycharms-available-packages