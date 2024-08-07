This tutorial demonstrates how to build and deploy an android app to your smartphone. The app was programmed with python and the kivy framework. Buildozer, the android debug bridge and the ubuntu subsystem were used to build, deploy and debug the android app. This tutorial works also perfectly fine for Ubuntu.

If anything is unclear, feel free to ask and write a comment.


▬ Links ► ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

Code of this tutorial:
https://github.com/denczo/kivy_examples
ADB for Windows:
https://dl.google.com/android/reposit...

▬ Commands ► ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

►  Download project
git clone https://github.com/denczo/kivy_examples

► Install buildozer:
git clone https://github.com/kivy/buildozer.git
cd buildozer
sudo python3 setup.py install

► Required libraries and tools:
sudo apt-get update
sudo apt-get install openjdk-8-jdk
sudo apt-get install unzip
sudo apt install python3 python3-pip ipython3
sudo apt install cython
sudo apt-get install autoconf
sudo apt install build-essential libltdl-dev libffi-dev libssl-dev python-dev
sudo pip3 install --upgrade cython
sudo apt-get install zip

► Build & Deployment
buildozer android debug deploy run logcat
adb -s DEVICE_ID logcat *:S python:D
adb -s DEVICE_ID install name.apk

► Connection to phone
adb devices
cmd:
adb tcpip 5555
wsl2 (ubuntu subsystem):
adb connect YOUR_IP:5555 


▬ Chapters ► ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

► 0:00 - Intro
► 0:27 - Install Ubuntu Subsystem
► 2:00 - Install Buildozer
► 4:44 - Buildozer Configuration (Buildozer.spec)
► 10:44 - Build .apk with Buildozer
► 13:50 - Connect Android Phone to PC
► 18:25 - Deploy .apk to Android Phone
► 19:27 - Debug App on Android Phone via terminal
► 21:50 - Outro

▬ Programming ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

► Pycharm Community Edition
► Python 3.8.1
► Kivy 2.0

▬ Editing ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

► Sony Vegas Pro Edit 14
► OBS
► t.bone SC400
► Cheap Webcam
