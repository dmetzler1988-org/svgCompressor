# SVG Compressor

This little script compress the svg files and remove all unnecessary code elements from files.

## Installation and usage

1. Switch to folder after clone repository
2. Execute command `npm install`
3. Copy files in folder `svg`
4. Execute command `npm run comp`
5. Check the compressed files in folder `compressedSvg`

### Commands available

- `npm run comp`: delete the destination folder and compress the file on normal way
- `npm run compBase64`: delete the destination folder and compress the file as base64
- `npm run compUriEncoded`: delete the destination folder and compress the file as URI encoded
- `npm run compUriUnencoded`: delete the destination folder and compress the file as URI unencoded
- `npm run clean`: clean up the folder `svg` and `compressedSvg` for a clean start

## Tools which are used

- NPM: [https://www.npmjs.com/](https://www.npmjs.com/)
- SVGO: [https://github.com/svg/svgo](https://github.com/svg/svgo)
