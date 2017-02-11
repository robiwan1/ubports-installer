## Ubports installer

This is still under development and is currently not 100% working

### How to install

```
git clone git@github.com:ubports/ubports-installer.git
sudo apt install gir1.2-glib-2.0 libglib2.0-dev libselinux-dev libssl-dev zlib1g-dev
npm install
```

### How to start GUI

```
npm start
```

### How to use CLI

*Please note that the cli is made for testing purposes.*

```
$ ./cli.js

Usage: cli [options]

Options:

  -h, --help               output usage information
  -V, --version            output the version number
  -d, --device <device>    Specify device
  -c, --channel <channel>  Specify channel (default: ubuntu-touch/stable)
  -v, --verbose            Verbose output
  -b, --bootstrap          Flash boot and recovery from bootloader
```