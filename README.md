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
06f1b209fe7f48a2c37f6992f1d9728e9f4e0342d53f93a79371fd7638346077bc61bb62b15d122d35e871acb952fbae6e2801b9ccda32c208021791cb79cb96
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
#### [Robert Furr (robtech21) - code fixes & active PRs](https://github.com/robtech21/)
#### [Tempora - support for portage](https://github.com/tempora/)
