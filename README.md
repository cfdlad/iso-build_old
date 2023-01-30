# My Manjaro iso-build

## Motivations

This is a custom Manjaro iso that is pre-packaged with additional software. 

It comes packed with additional applications pre-installed and is meant to be a fully featured and usable where an internet connection is not reliable.

## Additions to original Manjaro
The base build is kept as is with only additional software added.
All the additional softwre are listed below.

## My Additional Applications
### kooha               #screen recorder
### yt-dlp              #video downloader (cli)
youtube-dl          #video downloader (cli)
scrcpy              #android screen mirror software (cli)
aria2               #download manager (cli)
axel                #download accelerator (cli)
vlc
blanket             #Ambient sound player
kdenlive
handbrake
okular
qbittorrent
pdfarranger
gimp
krita
drawing
kate
lutris
wine
winetricks
aisleriot
gnome-break-timer
blender
gcolor3               #color picker
audacity
obs-studio
inkscape
darktable
celluloid
python-pip            #for pip3 installs
python-wheel          #for pip3 installs
#python-setuptools    #Already included in defualt install #for pip3 installs
rust                   #for rust installs
clementine
projectm
haruna
neofetch              #system info (cli)
code                  #visual studio code
fd                    #alternative to find (cli)
exa                   #ls replacement (cli)
iftop                 #Network monitor (cli)
nethogs               #Network monitor (cli)

## Build
To build use iso_build_mine.yaml in iso-build repo to run the github action
This workflow only makes use of my iso-build repo and my iso-profile repo
