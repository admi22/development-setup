# Development Setup 

This file gives some pointers on how I assembled my development setup (03.02.2022). The whole setup is inspired by Scott Hanselman.

Installing WSL is pretty easy under Windows 11. I mainly followed this guide: [Windows 11 WSL + Terminal styles](https://www.youtube.com/watch?v=VT2L1SXFq9U&ab_channel=ScottHanselman)

## PowerShell

The Windows PowerShell is customized based on Hanselman's tutorial. See above link for the installation.

## Linux shell

For the Linux shell I use zsh with the oh-my-zsh extension and the PowerLevel10k theme. Installation is not too complicated - they have nice installation wizards.
Additional zsh-extensions:
- https://github.com/zsh-users/zsh-autosuggestions
- https://github.com/zsh-users/zsh-syntax-highlighting

## LF file manager
Allows to navigate folder structure inside shell.  
Installation: 
- download lf-linux-amd64.tar.gz from https://github.com/gokcehan/lf/releases
- unzip with `tar xvf lf-linux-amd64.tar.gz`
- make file executable `chmod +x lf`
- and move it `sudo mv lf /usr/local/bin`  
  
Tutorial: https://github.com/gokcehan/lf/wiki/Tutorial  
Usage guide: https://www.youtube.com/watch?v=2oWqD3JCXuI&ab_channel=EricMurphy


