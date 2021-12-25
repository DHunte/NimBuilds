# Nim-Builds

![darwin workflow](https://github.com/DHUNTE/NimBuilds/actions/workflows/macos.yml/badge.svg)
![windows workflow](https://github.com/DHUNTE/NimBuilds/actions/workflows/windows.yml/badge.svg)
![linux workflow](https://github.com/DHUNTE/NimBuilds/actions/workflows/ubuntu.yml/badge.svg)

This project is a place-holder containing pipelines to execute builds of the nim programming language. 
The goal of the project is simply to mirror, build and release the current version of nim for all platforms.

## Why?

This was simply an easier way to reduce the number of CI steps required for multi-platform builds using nim as the official
page does not include pre-built binaries for macos and so requires builds steps prior to installation.

## Notes

The windows and linux binaries are directly downloaded as they are already available here https://nim-lang.org/install.html
