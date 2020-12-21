# dgkiss

My personal [GKISS](https://github.com/gkisslinux/grepo) repository.

## dgkiss

This repo houses pure 64-bit libraries and applications. Some highlights:

- melonDS
- MultiMC
- tcc
- chrony
- openjdk11-hotspot-bin

## multilib

NOTE: This repository does not work yet! A lot of the packages aren't even built
for 32-bit yet, and I am just now organizing them into this new repo. Don't
waste your time trying to use this until further notice.

This repo houses libraries and applications that are to be built as both 32-bit
and 64-bit. To use this repo you'll have to put it before the official GKISS
and KISS repos, or else `kiss` will prefer their packages to these ones.

The intention here is to allow applications like Wine and Steam that require
32-bit versions of certain libraries to run properly.
