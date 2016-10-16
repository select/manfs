# manfs
Print manual texts for your linux file system.

## Installation

Clone this repo and add the `manfs` script to your `PATH`.

```
git clone git@github.com:select/manfs.git
cd manfs
PATH=$PATH:`pwd`
```

For long term use add the manfs path to the `PATH` variable in your `.bashrc`.


## Usage
navigate to some path and get the man file
```
cd /usr
manfs
```
or pass a path directly to `manfs`
```
manfs /var
```
## Contributing

- I would love to add some more documentation for all kinds of folders like `~./ssh`
- It would be great to have documenation for files like `/boot/vmlinuz-4.4.0-43-generic`. To add this we could match it with e.g. `./data/boot/vmlinuz`
- Anybody want to help me build a `.deb` package?

Submit a pull request :D

## History

### [0.0.1] - 2016-10-16
- Initial version release

Added
- manuals for first level /* directories
- fallback suggestion if sub-directory is unknown

## Credits

All manual text are a shameless plug of "Linux Filesystem Hierarchy" by Binh Nguyen http://www.tldp.org/LDP/Linux-Filesystem-Hierarchy/html/index.html

The idea originates from using the ipython help `str ?` and reading an article about recreating the ps command (I can't find it anymore) that heavily relied on the "Linux Filesystem Hierarchy" linked above.

## License

TODO: Write license
