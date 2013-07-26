MDBlurView Demo
==================

![Screenshot](https://github.com/mochidev/MDPageControlDemo/raw/master/Artwork/Screenshot.png)

Purpose
-------

`MDBlurView` is a multiuse background view you can use for bluring in your iOS 7 Apps.
In addition, it provides some customizable properties that all adhere
to `UIAppearance`. Please visit the [MDBlurView](https://github.com/mochidev/MDBlurView)
repository for the actual code :)

If you use `MDBlurView` in your app, please add it to the
[list](https://github.com/mochidev/MDBlurViewDemo/wiki/Apps-That-Use-MDBlurView)!

Installation
------------

```bash
$ git clone https://github.com/mochidev/MDBlurViewDemo --recursive
```

To include it into your own projects either download the
[source](https://github.com/mochidev/MDBlurView), or run the following
on your git repo:

```bash
$ cd <your_repo>
$ git submodule add git@github.com:mochidev/MDBlurView.git <local_subpath>/MDBlurView
```

This will allow you to update it at anytime by running `$ git submodule update`.

Usage
-----

Simply add the
[MDBlurView](https://github.com/mochidev/MDBlurView) submodule to
your project, and add an `MDBlurView` to your view, either in Interface Builder,
or in code:

```obj-c
MDBlurView *blurView = [[MDBlurView alloc] initWithRect:CGRectMake(0, 0, 100, 100)];
```

Customization
-------------


To Do
-----


Coding Style Guidelines
-----------------------

Please see https://mochidev.com/codestyle

License
-------

Copyright (c) 2013 Dimitri Bouniol, Mochi Development, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software, associated artwork, and documentation files (the "Software"),
to deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in
   all copies or substantial portions of the Software.
2. Neither the name of Mochi Development, Inc. nor the names of its
   contributors or products may be used to endorse or promote products
   derived from this software without specific prior written permission.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Mochi Dev, and the Mochi Development logo are copyright Mochi Development, Inc.

Credits
-------

- Created by [Dimitri Bouniol](http://twitter.com/dimitribouniol) for [Mochi Development, Inc.](http://mochidev.com/)
