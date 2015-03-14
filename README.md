# WatchKit 'wrong image' glitch demo

This demo app demonstrates a bug in WatchKit.

## How to reproduce

1. Add to images to the WatchKit app with names `image_1@2x.png` and `image_10@2x.png`.
2. Set the first image to the interface image: `image.setImageNamed("image_1")`

## Expected behaviour

First image `image_1@2x.png` is shown.

## Actual behaviour

Second image `image_10@2x.png` is shown.

