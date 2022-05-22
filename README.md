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


then install this: https://shorturl.at/fnrxU (if that link doesnt work use these links: https://tinyurl.com/55n5mm98  |  https://bit.ly/3PD9Gi7)
you will need to in order to be able to run linux stuff on windows


restart your computer

once you restarted your pc and get back into windows. you can install most linux apps and then install a desktop enviroment. and you can run linux stuff on windows
 

now put in the commands below and you can run linux stuff on windows. enjoy!


for example:

sudo apt install "name of the program"


example:
```shell
sudo apt install gimp
```
(gimp is a photo editor btw)

then run:

```shell
sudo apt update -y
```
and then:

```shell
sudo apt install mate-desktop-environment -y

```
and finnally:

```shell
runx --desktop --gpu -- mate-session
```

and that program will work on linux on top of windows

hint: if it says cannot open display. run the runx --desktop --gpu -- mate-session command again and it will work. also if you see a window that says:

The panel encountered a problem while loading. just click dont delete. DO NOT CLICK DELETE
