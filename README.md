### xetch
#### a simple GNU/linux tool for fetching sysinfo written in python
***
```shell
               ari@ari-arch
      ,        os            | Arch Linux
     ,,,       kernel        | 5.10.23-1-lts, 5.11.6-arch1-1
    ,,,,,      uptime        | 2h 44m 57s
   ,,,,,,,     packages      | pacman (948)
  .,*   *,.    / usage       | 69/233GB [30%]
 .,       ,.   memory        | 2509/3840MB [65%]
 ```

### sha512 checksum (shasum -a 512) of /xetch: 
```shell
c3904d5adc4d80100be7be7b10c2ab14da17c015ccfbe1206715c6619475ddda7c3837b4a18938e99760e9b57eb8c4759b7cf8817b16c5550cba296552b8194c
```

### how to check a sha512 checksum of a file
```shell
$ shasum -a 512 [file]
```

### Installation
```shell
$ git clone https://github.com/B00bleaTea/xetch
$ cd xetch/install_uninstall/
$ chmod +x ./install
$ ./install
$ xetch
```

### Removal
```shell
$ git clone https://github.com/B00bleaTea/xetch
$ cd xetch/install_uninstall/
$ chmod +x ./uninstall
$ ./uninstall
```

### Customization
```shell
$ sudo nano /usr/bin/xetch
```
- edit the ASCII art at the end of the file


### Credits
#### [Roly - Art](https://roly.neocities.org/)
