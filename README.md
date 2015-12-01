# apps

Repo for already compiled apps

## Setup for uploading files

### Install git lfs

*This is probably not needed... *

First you need to download [git-lfs](https://git-lfs.github.com/)

### Add extension to keep track of it

    git lfs track "*.bin"

### Work with the binaries as with any other file

	git add mycompiledfile.bin

## Contributing

Create a new directory containing

* A README.md Please host PNGs or other images to a different repo. Point to the source either in the MBED environment or somewhere else
* A app.json file with:

    {
		author: "Author names",
		name: "Program name",
		version: "Program version",
		license: "Apache, GPL or whatever",
		source: "Source code link"
	}
* The binary file itself, called `firmware.bin`
* Modify [`firmware_list.json`](firmware_list.json) and add your app to make it appear in the directory.
