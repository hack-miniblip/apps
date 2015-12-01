# apps

Repo for already compiled apps for the MiniBLIP board

## Contributing new apps

### Upload your projet using the following folder structure
	./<projectName>
	./<projectName>/firmware.bin
	./<projectName>/cover.png (64x64 / optional)
	./<projectName>/README.md

### Update de JSON file using the following structure

```json
{
  "name": "anim",
  "author" : "Your GitHub/MBED id",
  "version": "0.0.1",
  "tags": ["light","sound","game"],
  "md5": "efefefababab" ,
  "cover": true,
  "license": "GPL, Apache or whatever",
  "source": "http://github.com/this/is/the/source"
}
```

`anim` would be the name of the subdirectory. Remember to add the comma at the end. Please pull from this repo before modifcation to avoid conflicts; if it happens just pull, solve the conflict and do the pull request again.

Compute the md5 signature with

    md5sum firmware.bin

and copy it above

### Remember to :

* Point to the source either in the MBED environment or somewhere else
* Create the README.md 
* Name the binary file as `firmware.bin`
