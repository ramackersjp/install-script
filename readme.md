# Shell script for exercises and learning:

When you running this shell script, bash will provide the number 88 in a loop. After you understand what shell scripting is you will never run a bash script again without first looking in to the source. The changge you run a virus is huge! Thats the lesson. 

## Why it could be dangerous?
1. In a shell script you can run terminal based commands! If you don't know what you doing, it is possible that you gonna run a script that will delete your whole desktop environment.

Example (Please do not run this example!):

#!/bin/bash

echo "sudo uninstall"
read uninstallpkg
sudo apt remove --purge -y $uninstallpkg && apt autoremove -y

## Install

Download install.sh and make it executable (chmod +x install.sh), and then run it (./install.sh). This script will continuously output the number 88 in the terminal until you stop it (you can stop it by pressing Ctrl+C)

Single install command:

```
bash <(curl -L raw.githubusercontent.com/ramackersjp/install-script/main/install.sh)
```
