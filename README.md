# Why this?

This repository is a clone of [pykeio > ort-artifacts](https://github.com/pykeio/ort-artifacts). The original repository builds and releases **ort** binaries, which are used for [static linking](https://ort.pyke.io/setup/linking).

However, at Sasha we needed the freedom to build our own version of the binaries in order to incorporate new features and bugfixes early. That way we are decoupled from the official release cycle.

> **Actions > Build** runs the workflow that builds the binaries for several platforms.
>
> Out of all the produced binaries, [`sasha-lib`](https://github.com/Sasha-ApS/sasha-lib) only uses the ios ones:
> - `_-aarch64-apple-ios`
> - `_-aarch64-apple-ios-sim`
>
> <img width="320" height="271" alt="image" src="https://github.com/user-attachments/assets/d716914c-08e2-43bb-85d9-9dd35e8c5ef4" />

## Changelog
- 

