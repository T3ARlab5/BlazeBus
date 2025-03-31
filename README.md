# BlazeBus 
> [!CAUTION]
> **Still in Development**\
> This project is still in its concept phase, actual PCBs will be ordered and tested soon™.

# Overview
The goal for this project is the development of an opensource, high temperature toolheadboard for 3D printers that is compatible with CAN and USB setups.\
While budget considerations are taken into account, this is not a cheap approach and tries to avoid cutting corners.

## Table of Content
* [Features](#features)
* [To Do](#to-do)
* [Schematic](#schematic)
* [Layout](#layout)
* [BOM](#bom)
* [Setup](#setup)
* [Disclaimer](#disclaimer)
* [Changelog](#changelog)
* [License](#license)

## Features
These are some of the planned features for the BlazeBus Toolheadboard:\
* All components rated to atleast 105°C
* All selfheating components rated to atleast 125°C
* Compatible with CAN or USB setups
* Support for 2/4-wire PT100/PT1000
* Triple thermistor setup (HE,HB,Chamber)
* 
* Easy toolchanger setup using upcoming BlazeHub distribution board
* Published under CC BY-NC-SA 4.0

## To Do
- [x] Publish initial V1-0 schematic
- [ ] Get feedback and implement changes
- [ ] Repeat until satisfied
- [ ] Finalize BOM and layout
- [ ] Order and test prototypes
- [ ] Publish "finished" design :tada:

## Schematic
Preview of the schematic pages, more details can be viewed in the [PDF version](Schematic/BlazeBus_Schematic.PDF). Page 3 will be used for not assembled parts e.g. plugs and crimps.
![Preview image of schematic page 1. Also available as PDF in subfolder.](https://github.com/T3ARlab5/BlazeBus/blob/main/Media/BlazeBus_Schematic-1-V1-1.jpg)
![Preview image of schematic page 2. Also available as PDF in subfolder.](https://github.com/T3ARlab5/BlazeBus/blob/main/Media/BlazeBus_Schematic-2-V1-1.jpg)
![Preview image of schematic page 3. Also available as PDF in subfolder.](https://github.com/T3ARlab5/BlazeBus/blob/main/Media/BlazeBus_Schematic-3-V1-1.jpg)

## Layout
TBD

## BOM
TBD

## Setup
TBD

## Disclaimer
BlazeBus is an open source project and has absolutely no warranty, or guarantees on functionality or reliability! The authors of this project accept absolutely no liability for any harm or loss resulting from its use.

## Changelog
| Revision | Release Date | Description  |
| ------------- | ------------- | ------------- |
| V1-1  | Feb 08, 2025 | Change to TMC2240 and support of two USB connections |
| V1-0  | Mar 20, 2025 | Initial version |


## License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/T3ARlab5/BlazeBus">BlazeBus</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/T3ARlab5">T3ARlab5</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>
