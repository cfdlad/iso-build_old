# My Manjaro iso-build

This is a custom Manjaro iso that is pre-packaged with additional software.
It is set to build **Manjaro gnome**, but can be changed to kde or xfce by changing the `Edition:[]` option in the [iso_build_mine.yaml](https://github.com/cfdlad/iso-build/blob/main/.github/workflows/iso_build_mine.yaml) file.

## Motivations
 
It comes packed with additional applications pre-installed and is meant to be fully featured out of the box and usable where an internet connection is not reliable.

## Additions to original Manjaro gnome

The base build of Manjaro (gnome) is kept as is with only additional software added from the manjaro repository.  

Software can be added or deleted by editing the `Packages-Desktop` file in [iso-profiles/manjaro/gnome/Packages-Desktop](https://github.com/cfdlad/iso-profiles/blob/master/manjaro/gnome/Packages-Desktop).  

All the additional softwre are listed below.

## My Additional Applications

```yaml
kooha                #screen recorder
yt-dlp               #video downloader (cli)
youtube-dl           #video downloader (cli)
scrcpy               #android screen mirror software (cli)
aria2                #download manager (cli)
axel                 #download accelerator (cli)
vlc  
blanket              #ambient sound player
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
#python-setuptools    #already included in defualt install #for pip3 installs
rust                  #for rust installs
clementine
projectm
haruna
neofetch              #system info (cli)
code                  #visual studio code
fd                    #alternative to find (cli)
exa                   #ls replacement (cli)
iftop                 #network monitor (cli)
nethogs               #network monitor (cli)

```

## Build

To build use [iso_build_mine.yaml](https://github.com/cfdlad/iso-build/blob/main/.github/workflows/iso_build_mine.yaml) file in the iso-build repo to run the github action. 

This workflow makes use of the [iso-build](https://github.com/cfdlad/iso-build) ropository and the [iso-profiles](https://github.com/cfdlad/iso-profiles) repository. 

Note: When cloning, edit the `iso_build_mine.yaml` file so that it will point to your iso-profiles repository thereby ensuring your customizations will reflect in your iso build.  
