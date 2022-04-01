# ytdl

_This repository is instruction, tutorial, and shortcuts._

**Written for the macOS platform; should work for GNU/Linux users as well.**

Windows instructions can be written — if someone would like to fund the work.

## Ever see something and think, ‘that won’t live long on the net.’ 

[youtube-dl](https://youtube-dl.org/) is a tool enabling you to locally store a backup copy of a video from a [wide variety](https://github.com/ytdl-org/youtube-dl/blob/master/docs/supportedsites.md) of video sharing sites, not just YouTube. 

### How do I do that?
Through youtube-dl - a public domain, meaning it is free to use and distribute, command line software tool. Command line means you’ll have to use [Terminal](https://support.apple.com/guide/terminal/welcome/mac), unless you use a GUI front-end.

## Install: 
Follow any of the install options from the [youtube-dl](https://github.com/ytdl-org/youtube-dl#installation) project page then, click back to this tutorial.

### Install keyboard shortcuts:
Open Terminal. 

Copy the following command and paste it into the Terminal window.
```
cat>>~/.zshrc
```
Copy the following textblock and paste it into the Terminal:
```
alias y='youtube-dl --write-description'
alias l='ls -alh'
alias ..='cd ..'
alias d='cd ~/Downloads'
```
Press [return].

The following steps require you to hold down two keyboard keys at once.

* Press, at the same time, the keyboard keys: [control] and [D]. // appends the lines (above) to the file.
* Again, press: [control] and [D]. // In this context Terminal communicates [EOT](https://en.wikipedia.org/wiki/End-of-Transmission_character), not [EOF](https://en.wikipedia.org/wiki/End-of-file) as above, thus the shell session is ended.
- - -
## Now let's try it!
From within the Terminal.app press, at the same time, the keyboard keys: [command] and [N]. // this opens a new Terminal window with a fresh shell session — one where the aliases defined in .zshrc are ready to go.

> “What's a shell?” In computing lingo, a shell is an interface to your computer operating system's [user space](https://techterms.com/definition/user_space). 

### Usage
Once you have youtube-dl installed and the keyboard shorcuts available:
* start by always typing d [return]. // this will call up your computer account's Downloads directory (directory is synonomous with Folder).
* then, type y followed by the web address containing the video [return]. // this should allow you to download and extract the video along with producing a description file based upon the video's published description.

If you don't already have a shell interface to your computer launch Terminal in order to gain one then, type:
```
d
```
You should now see Downloads listed in your command prompt.

Now try downloading a video:
```
y [https://youtu.be/Li_MGFRNqOE](https://youtu.be/Li_MGFRNqOE)
```
If nothing is happenning after you type the command then remember to press the [return] key at the end of the command.  

To access any of videos you've downloaded simply launch Finder and click on your Downloads folder. Any and all of the downloaded video content will be in that folder unless you moved them or encountered an error. If you failed to press d[return] prior to pressing y [web address] then the video may be in your home directory. To check your home directory in Finder click the Go menu and select Home.
