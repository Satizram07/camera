<h2 align="center"><u>CamHacker</u></h2>

![Hack anyone's camera and get images](files/banner.png)
<h4 align="center"> Hack anyone's camera and get images!</h4>

<p align="center">
    <img src="https://img.shields.io/badge/Version-1.3-blue?style=for-the-badge&color=blue">
     <img src="https://img.shields.io/github/stars/Satizram/CamHacker?style=for-the-badge&color=magenta">
  <img src="https://img.shields.io/github/forks/Satizram/CamHacker?color=cyan&style=for-the-badge&color=purple">
  <img src="https://img.shields.io/github/issues/Satizram/CamHacker?color=red&style=for-the-badge">
    <img src="https://img.shields.io/github/license/Satizram/CamHacker?style=for-the-badge&color=blue">
<br>
    <img src="https://img.shields.io/badge/Author-Satizram-green?style=flat-square">
    <img src="https://img.shields.io/badge/Open%20Source-Yes-orange?style=flat-square">
    <img src="https://img.shields.io/badge/Maintained-Yes-cyan?style=flat-square">
    <img src="https://img.shields.io/badge/Written%20In-Shell-blue?style=flat-square">
</p>

### [+] Description
CamHacker is a phishing tool. It will generate a link. If anyone opens the link and permits camera access, his/her photo will be captured and sent to you!

### [+] Installation

 - `git clone https://github.com/Satizram/CamHacker`
 - `cd CamHacker`

For termux, use additional command `termux-setup-storage`
 - `bash ch.sh`

##### Or Run Directly
```
wget https://raw.githubusercontent.com/Satizram/CamHacker/main/ch.sh && bash ch.sh
```

##### Usage
```
Usage: bash ch.sh [-h] [-o OPTION] [-p PORT] [-t TUNNELER] [-u] [-nu]

Options:
  -h, --help                           Show this help message and exit
  -o OPTION, --option OPTION           Index of the template
  -p PORT, --port PORT                 Port of CamHacker's Server
  -t TUNNELER, --tunneler TUNNELER     Name of the tunneler
  -d DIRECTORY, --directory DIRECTORY  Directory where images will be saved
  --update(-u), --no-update (-nu)      Check for update (Default: true)
```


### [+] Features
 - Three Templates
 - Get IP, Location, Device type and Browser
 - Dual Tunneling (Ngrok and Cloudflare)
 - Choose where to save images(custom directory) 
 - Error Diagnoser
 - Argument support for templates, tunnelers and directory

#### Relevant Tools by Me
 - [PyPhisher](https://github.com/Satizram/PyPhisher) for login phishing
 - [VidPhisher](https://github.com/Satizram/VidPhisher) for video phishing

 
### [+] Preview 
![Hack anyone's camera and get images](files/ch.gif)

### [+] Depenencies
 - `php`
 - `curl`
 - `wget`
 - `unzip`

All of the necessary depenencies will be installed automatically in first run!

### [+] Note
You need to use good (not mini version like opera mini) browsers as chrome/brave/mozila to get image captured. Although some browsers can block this CamHacker, however it works in most devices.

### [+] Credits 
Thanks to <a href="https://github.com/noob-hackers/grabcam">Noob-Hackers</a>, <a href="https://github.com/Techchipnet/camphish">Technochip</a> and <a href="https://github.com/TheLinuxChoice">Linux Choice</a> for their open source codes!

### [+] Disclaimer 
***This tool is developed for educational purposes. Here it demonstrates how camera phishing works. If anybody wants to gain unauthorized access to someones camera, he/she may try out this at his/her own risk. You have your own responsibilities and you are liable to any damage or violation of laws by this tool. The author is not responsible for any misuse of CamHacker!***

### [+] Find me on 
<a href="mailto:Satizramkrd@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-Satizramkrd@gmail.com-blue?style=for-the-badge&logo=gmail"></a>

<a href="https://m.me/Satizram" target="_blank"><img src="https://img.shields.io/badge/Messenger-Satizram-blue?style=for-the-badge&logo=messenger"></a>

