# unix tools

## Errday
```
pbcopy      pipe into your clipboard
pbpaste     pipe from your clipboard
time        check out how long a command took to run
cat         read a file to stdin
vim         cli version of atom, nice for small edits
```

## Process management
```
tail          with `-f` you can follow new changes on a file, useful for logs
ps            log running processes. Get PIDs. `ps -aux` is pretty common
*top          show sys info, available in different flavors (vtop is dope)
```

## npm
party tricks
```txt
npm ex <module name> <command> ... execute a command in the module dir
```

## dig
DNS lookup utility
```sh
# example
$ dig @127.0.0.1 -p 5000 something.foo +short
1.1.1.1
```

## vifm
Vim like file manager. Useful to do bulk directory operations. Offers different
views on files.

## smxi/sgfxi
System / gfx configuration tool.

- [website](http://smxi.org/)

## refind
boot manager

- [website](http://www.rodsbooks.com/refind/)