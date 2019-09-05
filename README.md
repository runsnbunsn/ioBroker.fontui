<h1>
	<img src="admin/fontui.png" width="64"/>
	ioBroker.fontUI
</h1>

[![NPM version](http://img.shields.io/npm/v/iobroker.fontui.svg)](https://www.npmjs.com/package/iobroker.fontui)
[![Downloads](https://img.shields.io/npm/dm/iobroker.fontui.svg)](https://www.npmjs.com/package/iobroker.fontui)
[![Dependency Status](https://img.shields.io/david/runsnbunsn/iobroker.fontui.svg)](https://david-dm.org/runsnbunsn/iobroker.fontui)
[![Known Vulnerabilities](https://snyk.io/test/github/runsnbunsn/ioBroker.fontui/badge.svg)](https://snyk.io/test/github/runsnbunsn/ioBroker.fontui)

[![NPM](https://nodei.co/npm/iobroker.fontui.png?downloads=true)](https://nodei.co/npm/iobroker.fontui/)

**Tests:** Linux/Mac: [![Travis-CI](http://img.shields.io/travis/runsnbunsn/ioBroker.fontui/master.svg)](https://travis-ci.org/runsnbunsn/ioBroker.fontui)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/runsnbunsn/ioBroker.fontui?branch=master&svg=true)](https://ci.appveyor.com/project/runsnbunsn/ioBroker-fontui/)

## fontUI adapter for ioBroker


#### Widget collection using Font Awesome Icons
![Example](img/icon_example.png)

The icons(1500+) are easy to use and integrate in existing ioBroker VIS designs.
Searchable icon list: https://fontawesome.com/icons?d=gallery&m=free

## Functions

* Include icons with or without state in your existing designs with easy-to-use searchable icon list
* Apply animations like glowing or spinning to the icons
* Change size, color, rotation or animation speed
* (planned) additional animations
* (planned) icon touch buttons

### Displaying/hiding icons when a state changes

To create visualisations like "if state > 100 icon should glow red" just place two(or more) icons in top of each other
and use the already build-in visibility options from ioBroker VIS. Invisible icon animations don't waste Browser resources.

#### Using the icon font in other widgets
You can use the icons in any widget that allows HTML content. To display an icon within another widget just enter
 
 `<i class="fas fa-home fa-2x"></i>`
 
`home` is the icon name and `2x` is the relative size.

This should work with most widgets(I tested a few), but there may be some widgets where the icon doesnt display correctly.

#### Compatibility

FontUI Should work in most modern browsers like Chrome or Firefox(tested), go easy on the size of the icons when applying lots of animations, they can get very CPU intensive very fast.
### Changelog

### 0.1.1
* (runsnbunsn) update Font-Awesome to 5.10, adding about 300 new or changed icons

### 0.1.0
* (runsnbunsn) add searchable autocomplete list of icons with preview
* (runsnbunsn) add more animation options and settings
* (runsnbunsn) add translations


### 0.0.3

* (runsnbunsn) Fix ALL icons getting cutted on the top

### 0.0.2
* (runsnbunsn) Add options to rotate or spin the icons
* (runsnbunsn) Fix some icons getting cutted on the top

### 0.0.1
* (runsnbunsn) initial release

## License
MIT License

Copyright (c) 2019 Felix Mayerhofer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.