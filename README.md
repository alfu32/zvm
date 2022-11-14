# zvm
zig version manager

## installation

simple download:
```bash
curl https://raw.githubusercontent.com/alfu32/zvm/main/zvm > zvm
```


## usage 
run `zvm` to get available options
```output
commands :
        install         installs the specified version and architecture
        available       lists all avalable versions and system architectures
        autoupdate      zvm updates itself
```
### `zvm install` command 

Requires a release as the first parameter and an architecture as the second ( `./zvm install 0.10.0 x86_64-linux` )
to be able to determine the binary to download

if no architecture is specified, all available will be listed accompanied by the necessary command
`zvm install 0.10.0`


if no release version is specified all release versions will be listed accompanied by the necessary command
`zvm install`

calling zvm without full parameters will not do any change
### `zvm available` command 
when executed without prameters it lists all available versions
when executed with a specified version `zvm available 0.10.0` it will list all available packages for that version

## notes
 - if the downloaded version exists it will be replaced
 - will symlink zig to the downloaded version


