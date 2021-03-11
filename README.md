### Features

- Latest and updated login pages.
- Mask URL support 
- Beginners friendly
- Docker support (checkout `docker-legacy` branch)
- Multiple tunneling options
  - Localhost
  - Ngrok (With or without hotspot)


### Installation

You will need to use a linux distro this has been tested on Ubuntu 20.04 LTS you can download a distro for free if using windows you can use the windows subsystem for linux feature and download ubuntu from the microsoft store https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab after enabling WSL Then after that follow these instructions.

- Just, Clone this repository -
```
$ git clone git://github.com/htr-tech/zphisher.git
```

- Change to cloned directory and run `zphisher.sh` -
```
$ cd zphisher
$ sudo bash zphisher.sh
```

- On first launch, It'll install the dependencies and that's it. `Zphisher` is installed.

### Run on Docker
```
$ docker pull htrtech/zphisher
$ docker run --rm -it htrtech/zphisher
```

### Dependencies

**`Zphisher`** requires following programs to run properly - 
- `php`
- `wget`
- `curl`
- `git`

> All the dependencies will be installed automatically when you run `Zphisher` for the first time.

> Supported Platform : **`Termux`**, **`Ubuntu/Debian/Kali`**, **`Arch Linux/Manjaro`**, **`Fedora`**
