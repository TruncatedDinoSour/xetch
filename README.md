### xetch
#### a simple GNU/linux tool for fetching sysinfo written in python
***
```
               ari@ari-arch
      ,        os       | Arch Linux
     ,,,       kernel   | 5.10.24-1-lts
    ,,,,,      uptime   | 14h 32m 32s
   ,,,,,,,     packages | pacman (931) [931]
  .,*   *,.    / usage  | 43/233GB [18%]
 .,       ,.   memory   | 2341/3840MB [61%]
```

### Sha512 checksum (shasum -a 512) of /xetch: 
```
138fb2ed204a0a654b2285d15ed0ebda1f26eba87c33e5e3afe8b38643e93681cc0383dcf9fbf18b1a1b1e8fe0fe79c6b4fb45755b73d7bd501f6be5afd4db14
```

### How to check a sha512 checksum of a file
```shell
$ shasum -a 512 [file]
```

### Installation
```shell
$ git clone https://github.com/B00bleaTea/xetch/
$ cd xetch/install_uninstall/
$ chmod +x ./install
$ ./install
$ xetch
```

### Removal
```shell
$ git clone https://github.com/B00bleaTea/xetch/
$ cd xetch/install_uninstall/
$ chmod +x ./uninstall
$ ./uninstall
```

### Customization
```shell
$ sudo nano /usr/bin/xetch
```
- edit the ASCII art at the end of the file
- or edit the colour palate


### Credits
#### [Roly - Art](https://roly.neocities.org/)
#### [Robert Furr (robtech21) - code fixes & active PRs](https://github.com/robtech21/)
#### [Tempora - support for portage](https://github.com/tempora/)

### Special thanks to
#### [pfetch - inspiration](https://github.com/dylanaraps/pfetch/)
