# Image-Viewer

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

Hi! **Image-Viewer** is a Windows image viewer based on Python 3.8.

## Using:

You must download "Image-Viewer.exe" from the root of the repository. Then you have to open the image with "Image-Viewer.exe".

![OpenFile](https://image.prntscr.com/image/wbp7ZkYURHW2kH31pf-TFA.png)

Then you will see a window like this:

![Picture](https://image.prntscr.com/image/Xem6tkkkT8SKmUA9bZi-aQ.png)

## Modules Used:

1. pillow

Python 3.8 or higher is recommended for using this program. You need to install the pillow module. You can do this with the following command:

> pip install -r requirements.txt

**Pillow** is the friendly PIL fork by Alex Clark and Contributors. **PIL** is the Python Imaging Library by Fredrik Lundh and Contributors.

## Compilation

Image-Viewer is compiled with pyinstaller. This command is used for this.

> pyinstaller -F -i icon.ico -w -n Image-Viewer main.py

You can see what these parameters mean in the [pyinstaller documentation](https://pyinstaller.readthedocs.io/en/stable/usage.html#options).

## Versioning

**Image-Viewer** uses [Semantic Versioning](https://semver.org/).

## License

This project is licensed under the MIT License, see the [LICENSE](https://github.com/RIDERIUS/Image-Viewer/blob/main/LICENSE) file for details.