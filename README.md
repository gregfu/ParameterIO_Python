# Parameter I/O (ApplicationPlugin, Python)
Fusion 360 Application Plugin that enables exporting and importing 
model parameters into a  *comma seperated values (CSV)*  file.

## Intallation

This plugin is available directly from Autodesk's App Store where you can
download it with a convenient installer for you platform. However, if you 
would like to make modification to the source python source code an installation
from source may be the right thing for you.


## Installation from source (Mac):

*Ensure to restart Fusion 360 after installation of this plugin.*

### Create directory for the source

```
$ cd ~
$ mkdir src
$ cd src
```

### Clone the github repository

```
$ git clone https://github.com/gregfu/ParameterIO_Python.git
```


### Copy the bundle to your plugins directory
```
$ cp -r ParameterIO_Python/ParameterIO.bundle ~/Library/Application\ Support/Autodesk/ApplicationPlugins
```

### Restart Fusion 360


## Older docs:

### Usage:

First see [How to install sample Add-Ins and Scripts](https://rawgit.com/AutodeskFusion360/AutodeskFusion360.github.io/master/Installation.html)

Then have a look at the [help file](https://rawgit.com/AutodeskFusion360/ParameterIO_Python/master/ParameterIO.bundle/Contents/docs/Parameter%20I_O.html)

## License
Samples are licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

## Written by

Written by Wayne Brill <br /> (Autodesk Developer Network)
