## VCS ##

We use **Git** for storing sources of our projects. You need to install Git for getting source codes of Winegame project.

## Installing Git ##

### Ubuntu, Debian, Mint and other Debian-based distros ###

```
sudo apt-get install git-core
```

### Gentoo, Calculate ###

```
emerge git
```


## Dependencies ##

  * FuseISO or kdesu/gksu
  * Qt 4.6 (GUI, Core, Network)
  * Loopback device support and ISO9660 support in Linux kernel
  * [Wine](http://winehq.org)
  * [Winetricks](http://tinyurl.com/winetricks)


## Getting source ##

```
git clone git://github.com/pashazz/winestuff.git #Winestuff library
git clone git://github.com/pashazz/winegame.git #Winegame
git clone git://gitorious.org/winestuff-tools/winestuff-packager.git #Winestuff Packager (GUI utility for creating winestuff packages
git clone git://gitorious.org/winestuff-tools/wst-listgen.git #wst-listgen - command-line utility for creating winestuff package lists
```

## Installation ##
See INSTALL files