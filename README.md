# WatchKit 'wrong image' glitch demo

This demo app demonstrates a bug in WatchKit.

## How to reproduce

1. Add images to the WatchKit app with names `image_1@2x.png` and `image_10@2x.png`.
2. Set the first image to the interface image: `image.setImageNamed("image_1")`

## Expected behaviour

First image `image_1@2x.png` is shown.

## Actual behaviour

Second image `image_10@2x.png` is shown.

## Tested in Xcode

* Version 6.2 (6C131e)
* Version 6.3 (6D532l)

