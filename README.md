# apps

Repo for already compiled apps

## Contributing
### Upload your projet using the following folder structure
	./<projectName>
	./<projectName>/firmware.bin
	./<projectName>/cover.png (64x64 / optional)
	./<projectName>/README.md

### Update de JSON file using the following structure

```json
{
  "name": "anim",
  "version": "0.0.1",
  "author": "victor",
  "filename": "anim",
  "id": 1,
  "type": "",
  "image": "yes", 
  "md5": "" 
}
```


### Remember to :
* Point to the source either in the MBED environment or somewhere else
* Create a README.md Please host PNGs or other images to a different repo. 
