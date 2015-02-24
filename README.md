ngEmoticons
===========

An angularjs filter for converting text into emoticons.

Supports chat codes like :) :P :( 3:) :D :/ ;)  (y) (^) <3 </3 etc.

###Screenshot
---
![screenshot](https://raw.github.com/ritz078/ngEmoticons/emoji/demo/screen.png)

###Dependencies
---
+ AngularJs 1.2 or above
+ ng-Sanitize

###Getting Started
---
Install through bower
```html
bower install ng-emoticons --save
```
load css files
```html
 <link rel="stylesheet" href="path/to/ng-emoticons.min.css"/>
```

 Then load the following files
```html
<script src="bower_components/angular/angular.min.js"></script>
<script src="bower_components/angular-sanitize/angular-sanitize.min.js"></script>
<script src="path/to/ng-emoticon.min.js"></script>
```

Load 'Emoticons' as a dependency
```javascript
angular.module('ngEmoticonApp', ['ngSanitize','ngEmoticons'])
```

HTML:
```html
<div ng-bind-html="text | linky:'_blank' | emoticons"></div>
```

###Version 0.2.0
---
Using font instead of images provided by icomoon.


###License
---

The MIT License (MIT)

Copyright (c) 2014 Ritesh Kumar

Permission is hereby granted, free of charge, to any person obtaining a
copy
of this software and associated documentation files (the "Software"), to
deal
in the Software without restriction, including without limitation the
rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE
SOFTWARE.


