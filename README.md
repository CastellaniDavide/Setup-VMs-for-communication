# Setup VMs for communication
[![GitHub license](https://img.shields.io/badge/licence-GNU-green?style=flat)](https://github.com/CastellaniDavide/cpp-template/blob/master/LICENSE) 
![Author](https://img.shields.io/badge/author-Castellani%20Davide-green?style=flat) 
![sys.platform supported](https://img.shields.io/badge/OS%20platform%20supported-Linux,%20Windows,%20Mac%20OS-blue?style=flat) 
[![On GitHub](https://img.shields.io/badge/on%20GitHub-True-green?style=flat&logo=github)](https://github.com/CastellaniDavide/Setup-VMs-for-communication)

## Tags
![VBox](https://img.shields.io/badge/Tag-VBox-yellow?style=flat)
![VMs](https://img.shields.io/badge/Tag-VMs-yellow?style=flat)
![Windows](https://img.shields.io/badge/Tag-Windows-yellow?style=flat)
![Python](https://img.shields.io/badge/Tag-Python-yellow?style=flat)
![Tutorial](https://img.shields.io/badge/Tag-Tutorial-yellow?style=flat)
![GitHub](https://img.shields.io/badge/Tag-GitHub-yellow?style=flat)
![git](https://img.shields.io/badge/Tag-git-yellow?style=flat)
![WMI](https://img.shields.io/badge/Tag-WMI-yellow?style=flat)
![NAT, Bridge, NAT_Network](https://img.shields.io/badge/Tag-NAT,%20Bridge,%20NAT_Network-yellow?style=flat)
![push, pull](https://img.shields.io/badge/Tag-push,%20pull-yellow?style=flat)

## Description
A guide to setup a demo VMs for communication

## Required
 - A windows OS image (eg. .iso .vdi ...)
 - A browser to see videos
   
## Istructions

 - [1. Install VBox]
 - [2. Install VMaschines]
 - [3. Install softwares]
 - [4. Setup Network]
 - [5. Schedule all]
 - [Enjoy]

### 1. Install VBox
#### Video
[![1 Install VBox](https://res.cloudinary.com/marcomontalbano/image/upload/v1604154185/video_to_markdown/images/youtube--2GwoHz4_Jtg-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/2GwoHz4_Jtg "1 Install VBox")

#### Testual
 - Go to [https://www.virtualbox.org](https://www.virtualbox.org/)
 - Press "Download" bottom
 - Select your OS & distribution (in my case Linux -> Ubuntu 20.04)
 - Install it with double press or using shell (in Ubuntu sudo apt install .\virtualbox...)

### 2. Install VMaschines
#### Video
[![2 Install VMaschines](https://res.cloudinary.com/marcomontalbano/image/upload/v1604154330/video_to_markdown/images/youtube--b0OB6TUKa5U-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/b0OB6TUKa5U "2 Install VMaschines")

#### Testual
 - Open VirtalBox
 - Press new and follow the setup
 - (I suggest you to give to the machine halp part of RAM to execute it better, if you want you can also upgrade the CPU cores to give to the machines Settings -> System -> Processor -> Set how many cores you want)
 - Power on machine (& setup it if you choose an .iso image)

### 3. Install softwares
#### Video
[![3 Install softwares](https://res.cloudinary.com/marcomontalbano/image/upload/v1604155667/video_to_markdown/images/youtube--m1V6_BNY44M-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/m1V6_BNY44M "3 Install softwares")

#### Testual
 - Install Python [https://www.python.org/](https://www.python.org/)
 - Install git [https://git-scm.com/downloads](https://git-scm.com/downloads)
 - Install all repos (on cmd in wanted folder) ```git clone https://github.com/CastellaniDavide/ldisk.git && git clone https://github.com/CastellaniDavide/usb.git && git clone https://github.com/CastellaniDavide/netinfo.git && git clone https://github.com/CastellaniDavide/sync.git && git clone https://github.com/CastellaniDavide/osversion.git```
 - pip packages 
   - for every package ```pip install -r requirements\requirements.txt```
   - for usb package run setup(.lnk) an accept "Run as Administator"
 - Enable sharing
   - Press Win + R or open "Run" programm in other methods
   - "Nework and Internet"
   - "Network and sharing centre"
   - "Change advanced sharing settings"
   - "All networks"
   - Give access to all
 - Check correct use (run every main code in bin folder)
   - **NB Make sure correct setup, it's write into README.md file in everyone of the project**

### 4. Setup Network 
#### Video
[![4 Setup Network](https://res.cloudinary.com/marcomontalbano/image/upload/v1604154514/video_to_markdown/images/youtube--vu0_24wQH6M-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/vu0_24wQH6M "4 Setup Network")

#### Testual
 - Get a valide static IP Address (eg. w/ ```ipconfig /all``` (Win))
 - Open "Control Panel"
 - "Nework and Internet"
 - "Network and sharing centre"
 - Connection: **Something** 
 - Proprieties 
 - Internet Protocol version 4 (IPv4)
 - Setup static IP using the valide IP and other infos you get in the first step of this 4° part

### 5. Schedule all
#### Video
[![5 Schedule all](https://res.cloudinary.com/marcomontalbano/image/upload/v1604156431/video_to_markdown/images/youtube--pjG_CwSsjk8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/pjG_CwSsjk8 "5 Schedule all")

#### Testual
 - Download [runall.bat](https://gist.github.com/DavideC03/bdd3b817de4778da647fd1244aa1fae4#file-autorun_server-bat) for master machine and [runall.bat](https://gist.github.com/DavideC03/bdd3b817de4778da647fd1244aa1fae4#file-autorun_client-bat) for client one
 - Open file manager
 - In the box where you usally view folder path put ```shell:startup```
 - Move here the downloaded file
 - Replace "/|\folder/|\" with the folder there was all your files
 - Try it restarting the VM(s)

### Enjoy
![](./src/enjoy.svg)

---
Made by Castellani Davide 
If you have any problem please contact me:
- [help@castellanidavide.it](mailto:help@castellanidavide.it)
- [Issue](https://github.com/CastellaniDavide/default-template/issues)
