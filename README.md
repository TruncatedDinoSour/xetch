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
f746323295d5be8a261c696d04fee6a9c39839a3867c30262be0dd5a8c9ee7d62b67f78119043bb7c92a52fca368c92f594dfd845ac71d28e6b6639d35edc0cd
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
- and/or edit the colour palate


### Credits
#### [Roly - Art](https://roly.neocities.org/)
#### [Robert Furr (robtech21) - code fixes & active PRs](https://github.com/robtech21/)
#### [Tempora - support for portage](https://github.com/tempora/)

### Special thanks to
#### [pfetch - inspiration](https://github.com/dylanaraps/pfetch/)
