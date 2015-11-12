# Source Serif Pro

Bower package for the [Source Serif Pro](https://github.com/adobe-fonts/source-serif-pro) web font.

## Usage

Add the following `HTML` to your website:

````html
<link href="/css/source-serif-pro.css" rel="stylesheet" type="text/css">
````

Alternatively, you can use the minified version:

````html
<link href="/css/source-serif-pro.min.css" rel="stylesheet" type="text/css">
````

Use the following `CSS` to integrate the font into your website:

````css
font-family: "Source Serif Pro", serif;
````

## Customization

To compile your own stylesheet, open `scss/source-serif-pro.scss` and remove any font styles you're not using:

````scss
@import "regular";
@import "bold";
````

To generate an **unminified** stylesheet and source map file, run the following command:

````bash
gulp
````

To generate a **minified** stylesheet, run the following command:

````bash
gulp --production
````