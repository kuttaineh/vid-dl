# ytdl

_This repository is instruction, tutorial, and shortcuts._

(written for the macOS platform; should work for GNU/Linux users as well. Windows instructions available if someone would like to fund the work.)

Ever see something and think to yourself, ‘that won’t live long on the net.’ 

[youtube-dl](https://youtube-dl.org/) is a tool which allows you to download, extract, and keep the video file from a [wide variety](https://github.com/ytdl-org/youtube-dl/blob/master/docs/supportedsites.md) of video sharing sites, not just YouTube. 

### How do I do that?
Youtube-dl is a public domain [meaning it is free to use and distribute] command line software tool. That means you’ll have to use Terminal, unless you use a GUI front-end.

### Install: 
[YouTube-dl](https://github.com/ytdl-org/youtube-dl#installation)

### Install keyboard shortcuts:



```
cat>>~/.zshrc
alias y='youtube-dl --write-description'
alias l='ls -alh'
alias ..='cd ..'
alias d='cd ~/Downloads'
```
