Install imagemagick and run the command in SVG flags folder to create a separate PNG files.
This will create separate PNG files that you can later convert into sprite online for example https://instantsprite.com/
```magick mogrify -resize 48x48 -format png -background none  *.svg ```

After downloading sprite run it via tinypng.com to compress the size