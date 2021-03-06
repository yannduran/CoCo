[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE.txt) [![VS15](https://img.shields.io/badge/Visual%20Studio%20Marketplace%20%7C%20VS15-1.0.2-green.svg)](https://marketplace.visualstudio.com/items?itemName=GeorgeAleksandria.CoCo) [![VS17](https://img.shields.io/badge/Visual%20Studio%20Marketplace%20%7C%20VS17-1.0.2-green.svg)](https://marketplace.visualstudio.com/items?itemName=GeorgeAleksandria.CoCo-19226)

# CoCo
A Visual Studio 2015 and 2017 extension that uses Roslyn API's for analyzing C# source code
and colorize appropriate syntax nodes to different colors. It makes easily recognizabling the supported elements. 

Extension supports following elements:
* Namespaces
* Alias for namespaces
* Fields in the local scope
* Parameters
* Intstance methods and constructor
* Static and extension methods
* Events
* Properties
* Instance fields
* Enum fields

Use Visual Studio ***Fonts and Colors*** options to change colors for items. Look for items in ***Display Items*** that starts with `CoCo format:`

# Examples

(Extension doesn't contain the ***default*** colors, so you need to set they as pointed out above if you want to see how it works)

List of the values (that's represented in RGB) for the various CoCo colour settings in the Dark theme:

|Item name|Value|
|----------------------------------------|---------------------:|
|CoCo format: alias namespace            |(default) 220 220 220 |
|CoCo format: constructor method         |(default) 220 220 220 |
|CoCo format: enum field                 |  0 193 193 |
|CoCo format: events                     |(default) 220 220 220 |
|CoCo format: extenson methods           |233 122   1|
|CoCo format: fields                     |255 157 255|
|CoCo format: local fields               |128 128   0|
|CoCo format: methods                    |187  54   4|
|CoCo format: namespaces                 |(default) 220 220 220 |
|CoCo format: parameters                 |128 128 128|
|CoCo format: properties                 |255   0 255|
|CoCo format: static methods             |154  82   1|

![](https://georgealeksandria.gallerycdn.vsassets.io/extensions/georgealeksandria/coco-19226/1.0/1504035613003/277591/1/DarkExample.PNG)


List of the values (that's represented in RGB) for the various CoCo colour settings in the Light/Blue theme:

|Item name|Value|
|----------------------------------------|---------------------:|
|CoCo format: Alias namespace            |128   0 255|
|CoCo format: constructor method         |255   0   0|
|CoCo format: enum field                 |  0 193 193|
|CoCo format: events                     |200   0 128|
|CoCo format: extenson methods           |224 118   1|
|CoCo format: fields                     |174   0 174|
|CoCo format: local fields               |128 128   0|
|CoCo format: methods                    |187   0   0|
|CoCo format: namespace                  |  0 213   0|
|CoCo format: parameters                 |108 108 108|
|CoCo format: properties                 |255   0 255|
|CoCo format: static methods             |163  86   1|

![](https://georgealeksandria.gallerycdn.vsassets.io/extensions/georgealeksandria/coco-19226/1.0/1504035613003/277592/1/LightExample.PNG)

## Contributing
Requests for new features and bug reports will help the project, so please write an issue for they.

If you think that this project is useful and makes you work more comfortaibly and easily, please give it a star.
