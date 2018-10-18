ghostwriter
===========
Fork of [Ghostwriter](https://github.com/wereturtle/ghostwriter). A beautiful cross-platform markdown editor, however this fork is intended to be compiled into VS 2017 (MSVC) x64.

This repository arises from the need to have a functional windows version that, as [announced by wereturtle](https://github.com/wereturtle/ghostwriter/issues/367), will no longer provide updates for Windows.

## Changes to the original structure

Each library used by ghostwriter was updated and moved to a separate VS2017 project, making it easier to maintain library updates.

## How to build

First of all, the following is necessary:

- Visual Studio 2017 (Desktop Development with **C++** installed)
- Qt 5.9 (MSVC 2017 64-bit) or greater.
- [annulen's fork of QtWebKit](https://github.com/annulen/webkit/releases) until the port to QtWebEngine is complete, `qtwebkit-5.212.0_alpha2-qt59-msvc2015-x64` is the newest version at the time of writing, however if you find an `msvc2017-x64` version, install that one.
