node-gotapi-plugin-onvif
===============

The node-gotapi-plugin-onvif is an ONVIF Plug-In for the node-gotapi.

---------------------------------------
## Table of Contents
* [Installation](#Installation)
* [Sample application](#Sample-application)
* [API Reference](#API-Reference)
* [License](#License)

---------------------------------------
## <a name="Installation">Installation</a>

### Dependencies

* [Node.js](https://nodejs.org/en/) 6 +
* [node-onvif](https://www.npmjs.com/package/node-onvif) 0.0.5 +

### How to install

```
$ cd ~
$ npm install node-gotapi-plugin-onvif
```

---------------------------------------
## <a name="Sample application">Sample application</a>

The node-gotapi-plugin-onvif packages a sample web application "onvif-manager". You can find the "onvif-manager" in the `html` directory of the node-gotapi-plugin-onvif. Copy the "`onvif-manager`" directory to the document root of the Web Server for front-end application of the node-gotapi.

```
$ cd ~/node_modules/node-gotapi-plugin-onvif/html
$ cp -rf ./onvif-manager ~/node_modules/node-gotapi/html
```

Restart the node-gotapi in order to load the `node-gotapi-plugin-onvif`. You can access this sample application at:

```
https://localhost:10443/onvif-manager/index.html
```

---------------------------------------
## <a name="API-Reference">API Reference</a>

*work in progress*

---------------------------------------
## <a name="License">License</a>

The MIT License (MIT)

Copyright (c) 2017 Futomi Hatano

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
