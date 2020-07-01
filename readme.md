# Circle country flags sprite
All country flags in circle format and PNG sprite in 24x24-@2x size.
Easily customizable via SCSS params and imagemagick SVG to PNG command.

# How to use the sprite?
Go into "dist" folder and copy the image and CSS to your project

# How to create sprite in a different size?
1. Download or clone the project
2. ```npm install```
3. Use imagemagick to convert SVG to PNG in desired size (see info.md in src/imagemagick) and create a sprite for example with https://instantsprite.com/
4. Place the sprite file in dist folder replacing the existing sprite file
4. Modify the SCSS file to match the desired size
5. ```npm run sass```
6. Go to ```dist``` folder and get the sprite css code