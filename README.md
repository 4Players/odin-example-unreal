# 4Players ODIN Unreal Sample Project

This is an Unreal Engine sample project using the [ODIN code plugin](https://github.com/4Players/odin-sdk-unreal).

[Online Documentation](https://www.4players.io/developers)

## Prerequisites

- Unreal Engine 4.26 or any later version (including 5.x)

## Getting Started

To check out the project for development, clone the git repo into a working directory of your choice.

This repository uses [LFS](https://git-lfs.github.com) (large file storage) to manage pre-compiled binaries, assets and Unreal Engine map files. Note that a standard clone of the repository might only retrieve the metadata about these files managed with LFS. In order to retrieve the actual data with LFS, please follow these steps:

1. Clone the repository (with submodules):  
   `git clone --recursive https://github.com/4Players/odin-example-unreal.git`

2. Cache the actual LFS data on your local machine:  
   `git lfs fetch`

3. Replaces the metadata in the binary files with their actual contents:  
   `git lfs checkout`
