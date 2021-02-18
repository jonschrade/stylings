# General Stylings

This repo is to help keep all of my CSS in one place to help create a more consistent look to the various sites.

## Usage

Actual documentation for Sass can be found here: https://sass-lang.com/documentation  
For a few examples, you can follow the example.scss file provided. There is more you can do with SCSS, but I haven't needed it yet. I will update the example.scss file with more when I use it myself.

## Building .CSS Files

After you've created your files, you can build  
*Note: I have only done this on Windows using node-sass. I know there are other ways, but this is how I do it*  
```
node-sass {{path-to-repo}}/example.scss {{path-to-destination}}/example.css
```  
Replace `{{path-to-repo}}` and `{{path-to-destination}}` with the file path to where the respective locations