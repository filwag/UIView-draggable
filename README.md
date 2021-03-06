#UIView+draggable

[![Build Status](https://travis-ci.org/cevitcejbo/UIView-draggable.svg)](https://travis-ci.org/cevitcejbo/UIView-draggable)
[![Coverage Status](https://coveralls.io/repos/cevitcejbo/UIView-draggable/badge.svg)](https://coveralls.io/r/cevitcejbo/UIView-draggable)
[![Cocoapods](https://cocoapod-badges.herokuapp.com/v/UIView+draggable/badge.png)](http://cocoapods.org/?q=summary%3Auiview%20name%3Adraggable%2A)
[![Analytics](https://ga-beacon.appspot.com/UA-42282237-8/UIView-draggable/README)](https://github.com/igrigorik/ga-beacon)

UIView category that adds dragging capabilities

##Screenshot
![UIVIew+draggable](https://raw.githubusercontent.com/andreamazz/UIView-draggable/master/screenshot.gif)

##Setup with Cocoapods
* Add ```pod 'UIView+draggable'``` to your Podfile
* Run ```pod install```
* Run ```open App.xcworkspace```

###Objective-C
Import ```UIVIew+draggable.h``` in your controller's header file
###Swift
If you are using `use_frameworks!` in your Podfile, use this import:
```swift
import UIView_draggable
```

##Usage
```objc
// Enable dragging
[self.view enableDragging];
```

#MIT License
	The MIT License (MIT)

	Copyright (c) 2015 Andrea Mazzini

	Permission is hereby granted, free of charge, to any person obtaining a copy of
	this software and associated documentation files (the "Software"), to deal in
	the Software without restriction, including without limitation the rights to
	use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
	the Software, and to permit persons to whom the Software is furnished to do so,
	subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
	FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
	COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
	IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
	CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
