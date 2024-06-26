# The CUDA workstation

This page contains guidelines to install the iCub nVidia CUDA
Workstation.

We assume you have installed a working Debian or Ubuntu on the laptop. You can freely decide to install 32 bit or 64 bit, the code compiles on both architectures.

Be aware that if you plan to share the repository with other machines, all machines need to have the same architecture (32 versus 64 bits, same versions of the libraries). A possibility would be to share the same code directory and different builds.

## Prerequisite : basic system setup for a iCub machine

Please follow the instructions on page [Generic iCub machine
installation instructions](generic-machine.md), in order to prepare a generic machine for the iCub network. Then, follow the steps below to customize it as the iCub Laptop

## Note

**In the following instructions, we assume that the installed OS is a Debian GNU/Linux Wheezy. If you are using a different distribution os release, please modify the instructions accordingly.**

## Installation steps

### Install CUDA toolkit

#### From Distribution repository (Debian / Ubuntu, quite old versions)

- DEBIAN : from Debian **non-free** repository, install the following
    packages

`nvidia-cuda-toolkit nvidia-cuda-dev`

- UBUNTU : from **multiverse** repository, install the following
    packages

`nvidia-cuda-toolkit nvidia-cuda-dev`

#### From the nVidia Developer website (Ubuntu, always the latest version)

Install the package for your distribution and architecture from
[https://developer.nvidia.com/cuda-downloads](https://developer.nvidia.com/cuda-downloads)
