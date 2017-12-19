Encode Explorer
==================================

Encode Explorer is a file browser written in PHP, XHTML and CSS. It displays the list of files in a folder. It was designed to be used in safe mode and so it is kept simple and functional. Free for everyone.

* Files can be sorted by name, size and editing time
* You can move in folders
* Thumbnails for images and pdf files.
* File uploading (needs PHP full mode)
* Logging and notifications
* Optional password protection
* Interface for mobile devices

Original Author : Marek Rei (marek at siineiolekala dot net)

Original Homepage : http://encode-explorer.siineiolekala.net

Demo kris : https://xoofoo.org/demo/encode-explorer/


System requirements
----------------------------------
- Apache Webserver (recommended), Nginx or IIS
- PHP version 5.6 or greater


Installation
----------------------------------
- Download a copy from https://github.com/krisxoofoo/encode-explorer/archive/master.zip and unpack it on your webserver.
- Open your web browser and go to the script at http://www.yourdomain.com/index.php


Configuration
----------------------------------
- Edit inc/conf.php and you can edit several settings.
- Comments are in english.
- Comments needed for configuring are in english.
- If you change anything, save with UTF-8 without BOM! Otherwise you may encounter problems, especially when displaying images.
- An example (in doc folder) of how to protect direct Access through .htaccess (apache) is available and must be adjusted to the webserver.


Troubleshooting
----------------------------------
If you are having problems installing or using Encode-Explorer modified by kris, please post issue here: https://github.com/krisxoofoo/encode-explorer/issues


License
----------------------------------
This software is distributed under The MIT License (MIT).

Copyright (c) 2015 Marek Rei

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

