# rendy-triangle
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Exaple of Rust program using [rendy](https://github.com/amethyst/rendy) and drawing colored triangle.

Source code was grabbed from official rendy-repo thanks to authors.

This repo was made to show how to build simple rendy-using program as a standalone project.

**DISCLAIMER!** I am not a pro in Rust or Rendy so don't consider this project a best practice.

## Build software requirements

If you work on Windows you need to install Cmake and [Ninja](https://github.com/ninja-build/ninja/releases) as they are needed to build Rendy dependency.

If you work on Mac OS you need to install XCode and Cmake.

## Supported platforms

Currently it works on Windows using Vulkan as rendering backend.

```
cargo run --features vulkan
```

Works on Mac OS with Metal backend.

```
cargo run --features metal
```

## History

### 0.1.0
 - Got something working!
