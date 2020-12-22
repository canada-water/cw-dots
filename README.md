# whitewash-dots
This is my repo for my first rice, which I am calling "whitewash." It is a slightly monochrome theme that honestly isn't very easy on the eyes, but the wallpaper looks nice and I honestly think I nailed it with the top bar in dwm. I've had some past experience with tiling window managers, such as i3, but I thought for my first real rice, I should go with something extensible like dwm. Being the original dynamic window manager, I thought that it could easily accomidate my needs for school and such, so that's what I went with in the end.

Installation for this is relatively simple, as many of you know since you've probably worked with dwm and other Suckless software before. Simply clone the repo, cd into the folder, and if you run an ls you'll find all the other pieces of software. These are:

* dwm
* dmenu
* slock
* slstatus
* st
* surf
* tabbed

I'd start with the dwm folder, so cd into that and run `sudo make clean install.` After it finishes, you can add `exec dwm` to your .xinitrc file and it'll start up nicely every time you run `startx`. After you've compiled dwm, just cd into the other folders and run the same command in them, compiling everything else.

While I haven't truly managed to get surf to work out just yet, I did get it configured nicely and I think that it fits with the theming here. Dependencies for all this are the font-awesome pack and the Liberation Serif font. Other than that, you should be fine with what is in the repo itself.

![screenshot1](https://github.com/canada-water/whitewash-dots/blob/main/Screenshot%20from%202020-12-22%2010-06-09.png)
