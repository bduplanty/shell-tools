# Shell Tools

My collection of shell tools.
1. jrnl aliases and functions to assist with TODO lists in jrnl files - future post to explain my process
2. bash aliases, fuctions, and set-up (color, prompt) for decent and consistent bash shell setup

Note: zsh can use print and is preferred - bash only uses echo

## Notes
- I use zsh in MacOS to develop
- Will check in secured windows environment

# jrnlscr
- include in .zshrc or .bashrc
```
export JRNLTODO="test"  # either blank for default jrnl or the name of the jrnl file (set-up in jrnl config) you would like
if [ -f ~/shell-tools/jrnlscr ]; then
    source ~/shell-tools/jrnlscr
else
    echo "404: ~/shell-tools/jrnlscr not found."
fi
## replace ~/shell-tools/jrnlscr to the location of the include file [jrnscr]
```
# bashsrc - bash set-up and aliases
- include in .bashrc
```
if [ -f ~/shell-tools/bashscr ]; then
    source ~/shell-tools/bashscr
else
    echo "404: ~/shell-tools/bashscr not found."
fi
```
