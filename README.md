Hi
This tutorial demonstrates how to build and deploy an android app to your smartphone. The app was programmed with python and the kivy framework. Buildozer, the android debug bridge and the ubuntu subsystem were used to build, deploy and debug the android app. This tutorial works also perfectly fine for Ubuntu.

▬ Commands ► ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬

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
*edit*
i found a way do install the world famous Psiphon3 on linux Ubuntu
here's how you do it:
To download and run Psiphon using the terminal in Ubuntu 24.04, follow these steps:

### Step 1: Install Required Dependencies
Since Psiphon3 is a Windows application, you'll need `wine` to run it on Ubuntu.

1. **Update Your System**:
   Open a terminal and update your package list:
   ```bash
   sudo apt update
   sudo apt upgrade -y
   ```

2. **Install Wine**:
   Install Wine by running:
   ```bash
   sudo apt install wine64 -y
   ```

### Step 2: Download Psiphon
1. **Download Psiphon3**:
   Use `wget` to download Psiphon3 from the official website:
   ```bash
   wget https://psiphon.ca/psiphon3.exe -O ~/Psiphon3.exe
   ```

This command downloads Psiphon3 and saves it as `Psiphon3.exe` in your home directory.

### Step 3: Run Psiphon Using Wine
1. **Navigate to the Downloaded File**:
   Change the directory to where Psiphon3 is downloaded:
   ```bash
   cd ~
   ```

2. **Run Psiphon with Wine**:
   Start Psiphon using Wine:
   ```bash
   wine ~/Psiphon3.exe
   ```

### Step 4: Using Psiphon
Once Psiphon starts, you can configure it as needed. The Psiphon interface should appear, allowing you to choose the VPN or SSH modes.

### Notes:
- **Running Wine Configuration**: If this is your first time running Wine, it might prompt you to install additional components like Mono or Gecko. Follow the on-screen instructions.
- **Permissions**: If you encounter permission issues, ensure the `Psiphon3.exe` file has the correct permissions with `chmod +x ~/Psiphon3.exe`.

This process will allow you to download and run Psiphon on Ubuntu 24.04 using the terminal.
