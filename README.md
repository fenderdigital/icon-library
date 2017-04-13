# Fender Icon Library

## [Documentation](https://fenderdigital.github.io/css-utilities/icons/)


### [Development](https://fenderdigital.github.io/css-utilities/development/)

Adding icons shouldn't occur very often, The icons are set up to pair well with our Typography scaling

To add an Icon:
* Clone this repo
* Acquire new Icon SVG and add it to the `src-icons` folder.
* Go to [Icomoon](https://icomoon.io/app) and upload the `selection.json` file from root. This gives you the current icon set.
* Import the new icon SVG into to the set, named appropriately (it will default to the name of SVG).
* Check if new imported icons are set to the 16x16 grid.
* Click on Generate Font, to download a Zip with generated assets.
* Replace the `fonts` folder and `style.css` files in `/src` with what you got from Icomoon.
* Replace `selection.json` 

Run:

`npm install`

Then

`npm start`

This will output both minified and unminified versions of the library to the `/dist` folder, as well as copy over the fonts.

Open a PR with your changes.
