# Hugo Flickity Carousel

![carousel.gif](carousel.gif) 

This [theme component](https://gohugo.io/hugo-modules/theme-components/#readout) for [Hugo Static Sites](https://gohugo.io/) allows you to embed image carousels based on [flickity](https://flickity.metafizzy.co/). 

## Features

## Installation

Put this folder in your themes folder in your hugo website. You can use git submodules to do this:

```bash
git submodule add git@github.com:madskjeldgaard/hugo-flickity-carousel.git themes/hugo-flickity-carousel
```

Then add it your list of themes:

Note: It has to be the last component, after your main theme.

```toml
theme  = [ "exformal-hugo-theme", "hugo-flickity-carousel"]
```  

The theme component **expects you to have jquery installed**.

## Usage

### Shortcode

You can insert an image carousel using the following shortcode. This expects the images to be in the `static` folder of your website:

```
{{< image-carousel images="[{ \"src\": \"/DSCF8028.jpg\", \"alt\": \"Image 1\" }, { \"src\": \"/DSCF8032.jpg\", \"alt\": \"Image 2\\" }, { \"src\": \"/DSCF8033.jpg\", \"alt\": \"Image 2\\" }]" >}}
```
