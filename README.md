------

# ```Bot Info```
<p align="center">
<a href="https://github.com/HERMIT-SIR/followers"><img title="Followers" src="https://img.shields.io/github/followers/HERMIT-SIR?color=red&style=flat-square"></a>
<a href="https://github.com/HERMIT-SIR/HERMIT-SER-MD/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/HERMIT-SIR/HERMIT-SER-MD?color=blue&style=flat-square"></a>
<a href="https://github.com/HERMIT-SIR/HERMIT-SER-MD/network/members"><img title="Forks" src="https://img.shields.io/github/forks/HERMIT-SIR/HERMIT-SER-MD?color=red&style=flat-square"></a>
<a href="https://github.com/HERMIT-SIR/HERMIT-SER-MD/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/HERMIT-SIR/HERMIT-SER-MD?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/HERMIT-SIR/HERMIT-SER-MD"><img title="Open Source" src="https://img.shields.io/badge/Author-Hermit%20Ser.-red?v=103"></a>
<a href="https://github.com/HERMIT-SIR/HERMIT-SER-MD/"><img title="Size" src="https://img.shields.io/github/repo-size/HERMIT-SIR/HERMIT-SER-MD?style=flat-square&color=green"></a>
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FHERMIT-SIR%2FHERMIT-SER-MD&count_bg=%2379C83D&title_bg=%23555555&icon=probot.svg&icon_color=%2300FF6D&title=hits&edge_flat=false"/></a>
<a href="https://github.com/HERMIT-SIR/HERMIT-SER-MD/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>
<p align='center'>
    </p>

-------

# Setup For Deployment 👇

## `SETTINGS`

- CHANGE OWNER NUMBER [Here](https://github.com/HERMIT-SIR/HERMIT-SER-MD/blob/master/config/config.json#L25)
- CHANGE OWNER NAME [Here](https://github.com/HERMIT-SIR/HERMIT-SER-MD/blob/master/config/config.json#L30)
- CHANGE BOT NAME [Here](https://github.com/HERMIT-SIR/HERMIT-SER-MD/blob/master/config/config.json#L29)

## ` BUILDPACKS`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/HERMIT-SIR/HERMIT-SER-MD/)

# Install Manually 👇
## `Requirements`
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor
## `Clone Repo & Installation dependencies`
```bash
git clone https://github.com/HERMIT-SIR/HERMIT-SER-MD.git
cd HERMIT-SER-MD
npm start
```
## `For Termux/Ssh/Ubuntu`
```bash
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
git clone https://github.com/HERMIT-SIR/HERMIT-SER-MD
cd HERMIT-SER-MD
npm start
```
## `For VPS`
```bash
apt install nodejs 
apt install git 
apt apt install ffmpeg 
apt apt install libwebp 
apt apt install imagemagick
apt install bash
git clone https://github.com/HERMIT-SIR/HERMIT-SER-MD
cd HERMIT-SER-MD
npm start
```
## `For 24/7 Activation`
```bash
npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs
```
