# Unity Package of the Burst Compiler

## Requirements

This package is working with the Unity 2018.1 and above.

## Installation

Inside your game folder, go to the folder `Packages`

You can then either:

- `git clone git@github.com:Unity-Technologies/com.unity.burst.git`
- or download the zip file of the repository (see download as zip on the side of this repository) and extract it in the folder `com.unity.burst`

You can also work with the development environment by compiling the `Burst` repository on your machine and setting the environment variable `UNITY_BURST_RUNTIME_PATH`

Example to work with a local build:

```
set UNITY_BURST_RUNTIME_PATH=PATH_TO_YOUR_LOCAL_BURST_REPO/build/bin/Debug
```

## Important

This repo contains some custom modifications to simplify supporting it [Rider Unity plugin](https://github.com/JetBrains/resharper-unity/).
