# ytdl

_This repository is instruction, tutorial, and shortcuts._

(written for the macOS platform; should work for GNU/Linux users as well. Windows instructions available if someone would like to fund the work.)

### Ever see something and think to yourself, ‘that won’t live long on the net.’ 

[youtube-dl](https://youtube-dl.org/) is a tool which allows you to download, extract, and keep the video file from a [wide variety](https://github.com/ytdl-org/youtube-dl/blob/master/docs/supportedsites.md) of video sharing sites, not just YouTube. 

### How do I do that?
youtube-dl is a public domain [meaning it is free to use and distribute] command line software tool. That means you’ll have to use Terminal, unless you use a GUI front-end.

### Install: 
[youtube-dl](https://github.com/ytdl-org/youtube-dl#installation)

### Install keyboard shortcuts:
Open Terminal. Copy the following textbock and paste it into the Terminal window.
```
cat>>~/.zshrc
alias y='youtube-dl --write-description'
alias l='ls -alh'
alias ..='cd ..'
alias d='cd ~/Downloads'
```
Press, at the same time, the keyboard keys: [control] and [D]. 
Again, press: [control] and [D].

Press, at the same time, the keyboard keys: [command] and [N]. 

### Usage
Once you have youtube-dl installed and the keyboard shorcuts available:
* start by always typing d [return]. // this will call up your computer account's Downloads directory (directory is synonomous with Folder).
* then, type y followed by the web address containing the video [return]. // this should allow you to download and extract the video along with producing a description file based upon the video's published description of that video content.

> ie. y https://youtu.be/Li_MGFRNqOE [return]

To access any of your downloaded video contents simply launch Finder and click on your Downloads folder. Any and all of your downloaded video content will be in that folder unless you moved them or encountered an error. If you failed to press d[return] prior to pressing y [web address] then the video may be in your home directory. To check your home directory in Finder click the Go menu and select Home.
