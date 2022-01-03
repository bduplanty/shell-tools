# Shell Tools

My collection of shell tools.
1. jrnl aliases and functions to assist with TODO lists in jrnl files - future post to explain my process

## Notes
- I use zsh in MacOS to develop
- Will check in secured windows environment

# jrnlscr
- include in .zshrc
```
export JRNLTODO="test"  # either blank for default jrnl or the name of the jrnl file (set-up in jrnl config) you would like
if [ -f ~/shell/jrnlscr ]; then
    source ~/shell/jrnlscr
else
    print "404: ~/shell/jrnlscr not found."
fi
## replace ~/shell/jrnlscr to the location of the include file [jrnscr]
```
