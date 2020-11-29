# zcash-lightwallet-proto

This repository holds gRPC definitions for the Zcash lightwalletd protocol.

Servers, clients, and other tools can use these common definitions, through a variety of means, such as fetching release tarballs, using `git subtree`, or `git submodule`.

## Status

Currently `lightwalletd` defines these protocols inside its source repository. Clients, such as `zecwallet-light-cli` maintain their own copies of these files. This approach doesn't work as nicely with tarball fetching, or `git subtree/submodule` because the entire source of `lightwalletd` is fetched/tracked.
