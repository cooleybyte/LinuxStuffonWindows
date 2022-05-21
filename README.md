**NOTICE: NOT ALL LINUX APPS WILL WORK ON WINDOWS CORRECTLY OR LAUNCH. YOU WERE WARNED**


first download the OfficialLinuxStuffOnWindows.zip file from the projects section of the LinuxStuffOnWindows github page


then run run me first.bat and then run me second.bat.


after that it will open the store and have you install the latest verion of ubuntu. install it and then once its done it will open the ubuntu windows after its done


then run these commands one after another (it has to be run one after another or else it wont work right:

```shell
sudo wget https://raw.githubusercontent.com/mviereck/runx/master/runx -O /usr/local/bin/runx
```
```shell
sudo chmod +x /usr/local/bin/runx
```
```shell
sudo apt update
```
```shell
sudo apt install xauth
```


then install this: https://file.io/Bjp2u87FPXdK
you will need to in order to be able to run linux stuff on windows


restart your computer

once your restarted your pc and get back into windows. you can install most linux apps and then install a desktop enviroment. and you can run linux stuff on windows

for example:

```shell
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb

```

then run:

```shell
sudo apt update
sudo apt install mate-desktop-environment

```


and that program will work on linux on top of windows