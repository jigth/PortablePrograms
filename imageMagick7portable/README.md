# Imagemagick 7 portable

## Compilation info and compatible platforms:

[This portable file](./imageMagick7.0.10-52portable.tgz) has been built using Ubuntu 20.04. It should work out of the box for Ubuntu and Ubuntu based distros.

It has been tested on Manjaro 19.0.2, Ubuntu 20.04 and Linux Lite 5.2

## Installation:

1. Download [ImageMagick's portable file](./imageMagick7.0.10-52portable.tgz)
2. Extract it
    
    > tar -xzf imageMagick7.0.10-52portable.tgz
3. Navigate to bin folder and use it directly or add it to the PATH
4. Enjoy C:

## Supported Delegates:

The portable was made to support JPEG and PNG delegates, with the default source code of ImageMagick.

## Build command:

The following command was used to build the portable file from source.

```bash
$ /configure --prefix=$MAGICK_HOME --disable-installed --disable-shared --enable-static --with-png=yes --with-jpeg=yes
```
