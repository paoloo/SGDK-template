# SGDK-BASE
An empty [SGDK](https://github.com/Stephane-D/SGDK) Sega Mega Drive game template.

## Files

```
.
├── README.md
├── definitions.h
├── main.c
├── res
│   └── resources.res
└── src
    └── boot
        ├── rom_head.c
        └── sega.s

3 directories, 6 files
```

## Build

- **Docker**
  Create an alias and build just running the command.
```bash
alias megabuild='rm -rf out && docker run --rm -it -v `pwd`:/src paoloo/sgdk'
```
  NOTE: a lot of times I have to remove the cache and regenerate all .o and resources, that's why I added it to the alias, to make things consistent

