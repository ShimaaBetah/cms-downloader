# cms-downloader
A CLI python script that downloads the material of any course hosted on the  cms website (for UNIX-Like operating systems)
*This script is personal I just wanted to share*
## Showcase

[![asciicast](https://asciinema.org/a/K1QAHRyrFyj2Hzulc0y8KXrYa.svg)](https://asciinema.org/a/K1QAHRyrFyj2Hzulc0y8KXrYa)


# Installation
install dependencies for Debian-based distros
```bash
$ sudo apt install xclip python3-tk python3-dev chromium-chromedriver git
```
install dependencies for Arch-based distros
```bash
$ sudo pacman -Sy tk git chromedriver xclip 
```
clone this repo 
```bash
$ git clone https://github.com/aboueleyes/cms-downloader.git
$ cd cms-downloader/
$ sudo pip install -r requirements.txt

```
You should edit cms-downloader file  according to your courses , username and password
```python
username ="yourusername"
paswword = "yourpassword"
```

# Usage
```bash

$ chmod 755 ./cms-downloader
$ sudo ln -s ./cms-downloader /usr/bin/cms-downloader 
$ cms-downloader
```
Tip : you can use regular expressions in search </br>
to select more than option press \<tab\>
