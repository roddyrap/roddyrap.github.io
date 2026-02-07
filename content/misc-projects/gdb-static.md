+++
title = 'Static GDB Builds'
summary = 'Static builds of `gdb` (and `gdbserver` of course), so you can run them on any machine, without any dependencies!'
+++

**Download**: Get the latest release from the [releases page](https://github.com/guyush1/gdb-static/releases/latest).

## Introduction

Who doesn't love GDB? It's such a powerful tool, with such a great package.  
But sometimes, you run into one of these problems:
- You can't install GDB on your machine
- You can't install an updated version of GDB on your machine
- Some other strange embedded reasons...

This is where `gdb-static` comes in! We provide static builds of `gdb` (and `gdbserver` of course), so you can run them on any machine, without any dependencies!

## Features

- **Static Builds**: No dependencies, no installation, just download and run!
- **Musl Based**: We use Musl in order to create distribution-independant binaries that can work anywhere.
- **Latest Versions**: We keep our builds up-to-date with the latest versions of GDB.
- **Builtin Python (Optional)**: We provide builds with Python support built-in.
- **XML Support**: Our builds come with XML support built-in, which is useful for some GDB commands.
- **Wide Architecture Support**: We support a wide range of architectures:
  - aarch64
  - arm
  - mips
  - mipsel
  - powerpc
  - x86_64

## Usage

To get started with `gdb-static`, simply download the build for your architecture from the [releases page](https://github.com/guyush1/gdb-static/releases/latest), extract the archive, and copy the binary to your desired platform.

You may choose to copy the `gdb` binary to the platform, or use `gdbserver` to debug remotely.

## Build types

We provide two types of builds:
1. Slim builds, that contains most of the features, beside the ones mentioned below.
2. Full builds that contains all of the slim build features, and also contains:
   * Python support
   * Cross-architecture debugging.
   Note that in order to enable cross-architecture debugging, we have to disable the simulator feature, since not all targets have a simulator.

Slim builds are approximately ~10MB. Full builds are approximately ~70MB.
You can edit the full_build_conf.sh file to disable full build exclusive features. 
