# ggshell
Gregor Gorjanc's (bash) shell functions and scripts

## Description

A set of functions and scripts that make my life easier when working in shell/terminal.

Functions are stored in files named *func_foo.sh* while scripts are stored in
files named *foo.sh*.

## Instalation

1. Save the files in your ~/bin folder
2. Add ~/bin folder to your PATH variable, i.e., export PATH=~/bin:$PATH
3. Add the following code to your ~/.bashrc file for each function you want to use

if [ -f ~/bin/func_foo.sh ]; then
  source ~/bin/func_foo.sh
fi

