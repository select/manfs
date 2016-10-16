# manfs
Print manual texts for your linux file system.

## Installation

Clone this repo and add the `manfs` script to your PATH.

```
git clone git@github.com:select/manfs.git
PATH=$PATH:/
```

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

I would love to add some more documentation for all kinds of folders like ~./ssh

Submit a pull request :D

## History

### [0.0.1] - 2016-10-16
- Initial version release
#### Added
- with man for /* directories
- fallback suggestion if sub-directory is unknown

## Credits

All manual text are a shameless plug of "Linux Filesystem Hierarchy" by Binh Nguyen http://www.tldp.org/LDP/Linux-Filesystem-Hierarchy/html/index.html

## License

TODO: Write license
