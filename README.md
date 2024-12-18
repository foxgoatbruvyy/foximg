# foximg

Simple image viewer built in Rust using [Raylib](http://www.raylib.com/).

# Features

- Drag and drop image to load it and its folder.
- Click the buttons on the side (Or press A or D) to go through the photo library.
- Support for:
    - PNG
    - Bitmaps
    - JPEG
    - DDS
    - HDR
    - ICO
    - QOI
    - TIFF
    - Netpbm
    - OpenEXR
    - WebP (Static and Animated)
    - GIF
- Basic photo manipulation:
    - Rotating 90 degrees
    - Mirroring
    - Zooming in and out
    - Draging across a zoomed in image
- Customizable Theme.
    **Windows only:** Default style based on your desktop theme.

# Installation

foximg creates config files and other miscelanious files while running. I strongly reccomend to install this in its own seperate folder. For now I don't distribute packages for this project. Download the source code and build it yourself.

## Supported Platforms

| Windows            | Linux              | macOS |
|--------------------|--------------------|-------|
| :heavy_check_mark: | :heavy_check_mark: | ❔     |

# Goals of the Project

foximg is in version 0.x. There's a lot of things missing until I believe it's stable or complete. I will try to actively use the issues page to document milestones and planned features.

The general goals I want to accomplish with this app are for it to be:
- Easy to use
- Fast
- Very customizable
- Relatively portable (Small install size)
- Pretty to look at (Clean UI)
