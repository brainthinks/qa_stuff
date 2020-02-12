# QA Curriculum <!-- omit in toc -->

A curriculum derived from [https://www.youtube.com/watch?v=rcaWHZb5kVo](https://www.youtube.com/watch?v=rcaWHZb5kVo)

## Table of Contents <!-- omit in toc -->

- [Test / Development Environment](#test--development-environment)
- [Install VirtualBox to run GNU/Linux](#install-virtualbox-to-run-gnulinux)
- [Set up your GNU/Linux environment](#set-up-your-gnulinux-environment)
- [Install some tools](#install-some-tools)
- [Basic terminal commands](#basic-terminal-commands)
- [Other stuff](#other-stuff)


## Test / Development Environment

Download a GNU/Linux ISO to install in your Virtual Machine, which you will use as your testing and development environment

1. Linux Mint
    * https://linuxmint.com/download.php
1. Ubuntu
    * LTS only! (Long Term Support) (https://wiki.ubuntu.com/LTS)
    * https://ubuntu.com/#download


## Install VirtualBox to run GNU/Linux

1. Create a folder in your bigass drive called "VM_stuff"
1. Enable Hardware Virtualization on your own computer via BIOS
    * https://www.isunshare.com/blog/how-to-enable-virtualizationvt-in-bios-for-hyper-v-windows-10/
1. Virtual Box
    * https://www.virtualbox.org/wiki/Linux_Downloads
1. Advanced: Vagrant
    * https://www.vagrantup.com/
1. Note, to get the mouse unlocked from VirtualBox, press Right Ctrl


## Set up your GNU/Linux environment

1. Install the virtual box guest additions
1. Open "Themes" -> enable dark theme options
1. open update manager
1. apply all updates and switch to a local mirror
1. Remember that if something is supported / installable in Ubuntu (or Debian), you can almost always install it / use it in Linux Mint


## Install some tools

1. Firefox
    * already installed
    * install ublock origin
    * make duckduckgo or google your default search engine
1. Chrome
    * have to get it from google's website
    * install ublock origin
1. Chromium
    * `sudo apt install chromium-browser`
    * F12 to open developer tools
    * install ublock origin
1. VSCode
    * https://code.visualstudio.com/
1. Postman
    * https://www.postman.com/


## Basic terminal commands

* `cd` - change to a different directory
* `ll` or `ls` - show directory contents
* `cat` - print raw file contents to terminal
* `nano` - a basic text editor


## Other stuff

* https://xkcd.com/1168/
