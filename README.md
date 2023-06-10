# appz : one app to rule them all

```
$ appz
appz [mngr] [i|r|l|C|u|U|s|S|I|c|h] [pkg]...
-> i | install install one or more packages
-> r | remove  remove one or more packages
-> l | list    list installed packages
-> C | count   count installed packages
-> u | update  update package lists
-> U | upgrade upgrade all packages
-> s | search  search for a package
-> S | show    show information about a package
-> I | info    same as show
-> c | clean   clean up leftover files/caches/orphans
-> h | help    show this message
```

## Supported managers : 
- pacman
- yay
- pipx

## Installation
```bash
git clone https://github.com/MyOS-ArchLinux/appz
cd appz
...
```

## License
[GPLv3](https://github.com/MyOS-ArchLinux/appz/blob/main/LICENSE)

inspired by [cpm](https://github.com/willeccles/cpm) - MIT License
