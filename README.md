# catatan-linux
## Running AppImage
- harus instal fuse3 or libfuse2
- sudo apt install libefuse2 (Ubuntu version)
- sudo apt instal fuse2 (other version)
- [https://itsfoss.com/cant-run-appimage-ubuntu/]

## Run .deb file (install .deb file)
- sudo dpkg -i [package-name].deb

## Install St-Link Tools
- sudo apt-get install git make cmake libusb-1.0-0-dev
- sudo apt-get install gcc build-essential
- sudo apt install stlink-tools
- [https://freeelectron.ro/installing-st-link-v2-to-flash-stm32-targets-on-linux/]

## Install & Run .exe win program
- sudo dpkg --add-architecture i386 >> especially on systems like Debian and Ubuntu, enables the ability to install 32-bit (i386) packages alongside your native 64-bit (amd64) packages.

- sudo apt update

- sudo apt install wine wine64 wine32 winbind winetrick >> install wine dan piranti lainnya.

- ke directory file .exe

- wine [nama-package].exe >> install software .exe dengan wine
  
- [https://youtu.be/nFbpXN7wvCs?si=5PU4SjAzEB0S9XAp]

## Install JAVA
- sudo apt install default-jdk
- pastikan cek java dan javac version dan path location
- Java --version
- javac --version
- which Java
- which javac
- cek java JDK Path alternative
- update-alternative --config java
- cek JAVA_HOME PATH
- echo $JAVA_HOME
- jika Java Home bekum ada, configurasi pan di file .bashrc
- export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64/bin
- export PATH=$JAVA_HOME/bin:$PATH
- versifikasi PATH
- echo $JAVA_HOME
