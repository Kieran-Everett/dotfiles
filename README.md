# dotfiles
This is a repo of the dotfiles that I use on my laptop. 
My laptop is running Ubuntu 19.04 with i3wm as the windows manager. 
The scripts are a mixture of files from [Luke Smith's voidrice](https://github.com/lukesmithxyz/voidrice/) 
and scripts that I have written myself.

## Installation
To install, run the installdotfiles bash program and hope it installs 
everything correctly. If it doesn't then open the program in something 
like nano or vim and then copy the commands into a terminal. You can also 
just copy and paste the config files into where you have them in your 
installation.

## Programs
Here are the programs that I have installed that use these config files:

+ i3
+ cava
+ cmus
+ dconf
+ discord
+ enchant
+ eog
+ evolution
+ fish
+ gedit
+ gnome-session
+ goa
+ gtk
+ htop
+ i3blocks (I don't use this at the moment)
+ ibus
+ mpv
+ msmtp
+ mutt
+ nautilus
+ neofetch
+ pulse
+ ranger
+ teamviewer
+ totem
+ transmission-daemon
+ transmission-remote-sli
+ update-notifier
+ viewnior
+ zathura
+ mime
+ xresources

I can't guarantee that these will all be in the package manager of your 
distro as some of these wern't for me. Many can easily be found by simply 
googling the name of the program and going to its GitHub repo.

## Scripts

I have my scripts split accross 2 folders, both of which must be added to 
your path through a command like `export PATH=$PATH:/home/$USER/bin` or 
`export PATH=$PATH:/home/$USER/.scripts`. You may also need to run 
`chmod +x whateverthefileis` to make the script executable.

+ audiocontrol - 
   This script allows me to change the audio levels by opening pavucontrol
+ betterlockscreen - 
   This is my lockscreen. It looks pretty. [Betterlockscreen repo](https://github.com/pavanjadhaw/betterlockscreen/)
+ brightness - 
   This script uses xrandr to change the brightness. This is specific to my laptop so you may need to change `eDP-1` to your display. The syntax is `brightness 0.8` for example which sets the brightness to 80%.  
+ clock - 
   [tty-clock](https://github.com/xorg62/tty-clock/) with some settings that I like to make it quicker to run.  
+ download-yt - 
   Uses youtube-dl to download a video. Syntax `download-yt (endofurl) (codecsource - run download-yt-codecs) (locationtodownloadto)`
+ download-yt-codecs - 
   Uses youtube-dl to output the codecs of the video. Syntax `download-yt-codecs (endofurl)`
+ fetch - 
   Uses neofetch with a blank line at the beginning because I like space.
+ filehole - 
   SSHes into my Raspberry Pi called file-hole. Named that way because it is a samba file server and a [pi-hole](https://github.com/pi-hole/pi-hole)
+ i3gnome-settings - 
   Opens gnome-settings in a way that allows it to be compatable with i3.
+ mansplain - 
   Opens any man page in a pdf using zathura and dmenu.
+ matrix - 
   Red cmatrix.
+ music - 
   Uses dmenu and mpv to play music
+ myi3bar - 
   A test i3bar script that I couldn't be bothered to delete.
+ podcasts - 
   Uses dmenu and mpv to play podcasts
+ update - 
   An update script
+ videos - 
   Uses dmenu and mpv to play videos
