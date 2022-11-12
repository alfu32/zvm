# zvm
zig version manager

it requires a release as the first parameter and an architecture as the second ( `./zvm 0.10.0 x86_64-linux` )
to be able to get a single version

if no architecture is specified, all available will be listed accompanied by the necessary command
`zvm 0.10.0`


if no release version is specified all release versions will be listed accompanied by the necessary command
`zvm`

calling zvm without full parameters will not do any change

