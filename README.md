### xetch
#### a simple GNU/linux tool for fetching sysinfo written in python
***
```
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
04d5d9c2e01bc0e0e5190b351528a3af94e107cde31bb344f7f5ea75406c41134ff584a44b4949c650dfef5013a09ccc96363f151103235e4f8c521c4aa398e1
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
