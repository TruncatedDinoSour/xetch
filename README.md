### xetch
#### a simple GNU/linux tool for fetching sysinfo written in python
***
```
                 ari@ari-arch
       ,         os       | Arch Linux
      ,,,        kernel   | 5.12.9-arch1-1
     ,,,,,       uptime   | 1h 52m 1s
    ,,,,,,,      packages | pacman (601) [601]
   ,,,,,,,,,     disk     | 14/233GB [6%]
  .,,*   *,,.    ram usage| 903/3840MB [24%]
 .,         ,.   terminal | st-256color
```

### Sha512 checksum (shasum -a 512) of /xetch: 
```
2bb8ab76d92fdec7593755bae66a31b9a172904aaec893cbb6bbd9ed6a23ab408ee9f89d064b31dbe83ff65b770671062e7b3f76c129ee7fd196fe0e21db724c
```

### How to check a sha512 checksum of a file
```shell
$ shasum -a 512 [file]
```

### Installation
```shell
$ https://github.com/TruncatedDinosour/xetch/
$ cd xetch/install_uninstall/
$ chmod +x ./install
$ ./install
$ xetch
```

### Removal
```shell
$ https://github.com/TruncatedDinosour/xetch/
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
