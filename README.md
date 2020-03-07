.tmux
=====

Installation
------------

Requirements:

  - tmux **`>= 2.1`** (soon `>= 2.4`) running inside Linux, Mac, OpenBSD, Cygwin
    or WSL
  - awk, perl and sed
  - outside of tmux, `$TERM` must be set to `xterm-256color`

To install, run the following from your terminal: (you may want to backup your
existing `~/.tmux.conf` first)

```
$ cd
$ git clone https://github.com/dskindell/.tmux.git
$ ln -s -f .tmux/.tmux.conf
```

Install external/third-party tools

OSX

```
$ pip install --user urlscan
$ brew install tmux-mem-cpu-load
$ brew install gawk
$ brew isntall fpp
$ brew install ansifilter
```

