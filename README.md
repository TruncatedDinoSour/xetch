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
965aba50cea0e2ad7ba49df7a3eb7c0166069ad0de349aa0028c3cc3a88c8615626f21f60d23b4bb14b9e868b19faf45ad3820f72658330c224651ca9cc83faa
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
