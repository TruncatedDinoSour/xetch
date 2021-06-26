### xetch
#### a simple GNU/linux tool for fetching sysinfo written in python
***
```
              ari@ari-gentoo
 _-----__     os       | Gentoo
 (       \\   kernel   | 5.10.27-gentoo-x86_64
 \\   0  \\   uptime   | 0h 24m 40s
  \\     )    packages | equery (265) [265]
 (     _/     disk     | 6/73GB [8%]
 \\    /      ram usage| 88/2020MB [4%]
   ⎻⎻⎻        terminal | st-256color
```

### Sha512 checksum (shasum -a 512) of /xetch: 
```
add462d784c537d5e45b4d80ebf3c31b29fc2ea6b5e54e7a86491f2ebaec9994e76e1b8f240dd55f35edde4e6b8806ab24cf43a33aaeb74f8dc45a5f7e87d6c2
```

### How to check a sha512 checksum of a file
```shell
$ shasum -a 512 [file]
```

### Installation
```shell
$ git clone https://github.com/TruncatedDinosour/xetch/
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
