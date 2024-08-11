Hi
This tutorial demonstrates how to build and deploy an android app to your smartphone. The app was programmed with python and the kivy framework. Buildozer, the android debug bridge and the ubuntu subsystem were used to build, deploy and debug the android app. This tutorial works also perfectly fine for Ubuntu.


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
ps there is a more complete string of codes you can enter to download the libraries, here they are :

sudo apt-get install build-essential ccache git libncurses5:i386 libstdc++6:i386 libgtk2.0-0:i386 libpangox-1.0-0:i386 libpangoxft-1.0-0:i386 libidn11:i386 python2.7 python2.7-dev zip unzip openjdk-8-jdk python3-pip autoconf libtool pkg-config zlib1g-dev zlib1g:i386 libncurses5-dev libltdl-dev libffi-dev libssl-dev autotools-dev libncursesw5-dev libtinfo5 cmake


for some of you that have problems with linux's terminal.
just download neckoray and run some configs that you can find on telegram
for example these ones that work for now:
vless://aa4acf5d-0b4e-4110-b62a-35b89e5a39e4@speedtest.net:443?path=%2Fvless%3Ftelegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn-telegram-%40ISVvpn&security=tls&encryption=none&host=29164.com&fp=chrome&type=ws&sni=speedtest.net#%40Gp_Config%20%F0%9F%93%8C%20%DA%AF%D8%B1%D9%88%D9%87%20%D9%85%D8%A7

vless://Parsashonam-33@104.21.19.124:8880?path=%2F%3Fed&security=none&encryption=none&host=myket.xn--ir-6g5cr0ao9vf3s229b.arvancloud.ir.DigehKhastehShodamAzbasDamanehKharidam.BlOG.&type=ws#%40Gp_Config%20%F0%9F%93%8C%20%DA%AF%D8%B1%D9%88%D9%87%20%D9%85%D8%A7

vless://610d7d20-ba6c-43a3-889d-7e4958791ee9@SpeeDTeST.OrG:80?path=%2F&security=none&encryption=none&host=WwW.SpeedTest.Net.WhiteBer.InsisTom.D6625996.V19.SiMansaNaT.Ir.&type=ws#%40Gp_Config%20%F0%9F%93%8C%20%DA%AF%D8%B1%D9%88%D9%87%20%D9%85%D8%A7

vless://cefffd1d-cc58-4560-b4d1-44f1af528f30@151.101.194.133:443?path=%2F&security=tls&encryption=none&host=fraud.chase&type=ws&sni=www.Arizona.edu#%40Gp_Config%20%F0%9F%93%8C%20%DA%AF%D8%B1%D9%88%D9%87%20%D9%85%D8%A7

vless://51a8f3ed-73ca-4b90-b152-73e1660df8c9@88.135.46.45:2053?security=none&encryption=none&host=speedtest.net&headerType=http&type=tcp#%40Gp_Config%20%F0%9F%93%8C%20%DA%AF%D8%B1%D9%88%D9%87%20%D9%85%D8%A7

vless://telegram-id-ArV2ray@www.speedtest.net:2095?path=%2Ftelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%2Ctelegram-ArV2ry%3Fed%3D2095&security=none&encryption=none&host=6.V2.c.www.speedtest.net.dnschecker.tecH.&type=ws#%40Gp_Config%20%F0%9F%93%8C%20%DA%AF%D8%B1%D9%88%D9%87%20%D9%85%D8%A7
