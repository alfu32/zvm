# zvm
zig version manager

# installation

simple download:
```bash
curl https://raw.githubusercontent.com/alfu32/zvm/main/zvm > zvm
```


# usage 

Requires a release as the first parameter and an architecture as the second ( `./zvm 0.10.0 x86_64-linux` )
to be able to determine the binary to download

if no architecture is specified, all available will be listed accompanied by the necessary command
`zvm 0.10.0`


if no release version is specified all release versions will be listed accompanied by the necessary command
`zvm`

calling zvm without full parameters will not do any change

# notes
 -  does not unistall existing versions
 - if the downloaded version exists it will be replaced
 - will symlink zig to the downloaded version


