Hi
This tutorial demonstrates how to build and deploy an android app to your smartphone. The app was programmed with python and the kivy framework. Buildozer, the android debug bridge and the ubuntu subsystem were used to build, deploy and debug the android app. This tutorial works also perfectly fine for Ubuntu.

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
ps there is a more complete string of codes you can enter to download the libraries, here they are :

sudo apt-get install build-essential ccache git libncurses5:i386 libstdc++6:i386 libgtk2.0-0:i386 libpangox-1.0-0:i386 libpangoxft-1.0-0:i386 libidn11:i386 python2.7 python2.7-dev zip unzip openjdk-8-jdk python3-pip autoconf libtool pkg-config zlib1g-dev zlib1g:i386 libncurses5-dev libltdl-dev libffi-dev libssl-dev autotools-dev libncursesw5-dev libtinfo5 cmake


for some of you that have problems with linux's terminal.
*use some sort of vpn*
