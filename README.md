# PyGameElements so you dont have to make a gui for pygame every time you write a game

PyGameElements provides you with a way to use elements that scale along with the screen size. 

# Overview
There are several elements available at this moment:

Core elements (consisting of one thing): Line, Square, Ellipse, Label, Image

Combined elements (consisting of more then one core elements): Button, CheckBox, InputBox

## Usage

In the following paragraphs, I am going to describe how you can get and use PyGameElements for your own projects.

###  Getting it

To download PyGameElements, either fork this github repo or simply use Pypi via pip.
```sh
$ pip install pygameElements
```

### Testing it

```Python
from testPygameElements import testPygameElements
testPygameElements()
```

To see an example of what you can do with the elements.
You can inspect the file yourself at C:\Users\YOURNAME\AppData\Roaming\Python\YOURPYTHONVERSION\site-packages\pygameElements
to see how it works. 

![Example Square Element](https://raw.githubusercontent.com/QuetzalQatl/pygameElements/main/testPygameElements/images/SquareExamples.png?raw=true)


### Using it

```Python
from pygameElements import *

```



Here are the variables you can set with each element along with its defaults:

class Line():
    def __init__(self, blitToSurface=None, gameState='', name='', color=(255,255,255), startPosPromille=(0,0), endPosPromille=(1000,1000), widthLine=5, alphaValue=255, visible=True):

class Square():
    def __init__(self, blitToSurface=None, gameState='', name='', color=(255,255,255,255), horizontalMiddlePromille=500, verticalMiddlePromille=500, horizontalSizePromille=100,  verticalSizePromille=400, widthBorder=0, borderTopLeft=1, borderTopRight=1, borderBottomLeft=1, borderBottomRight=1, alphaValue=255, visible=True):

class Ellipse():
    def __init__(self, blitToSurface=None, gameState='', name='', color=(255,255,255), horizontalMiddlePromille=500, verticalMiddlePromille=500, horizontalSizePromille=500,  verticalSizePromille=500, widthBorder=0, alphaValue=255, visible=True):

class Label():
    def __init__(self, blitToSurface=None, gameState='', name='', text='', colorText=(255,255,255), horizontalMiddlePromille=500, verticalMiddlePromille=500, sysFont=True, fontName='timesnewroman', fontSizePromille=100, isBold=False, isItalic=False, antiAlias=True, alphaValue=255, visible=True, rotation=0):
    
class Image():
    def __init__(self, blitToSurface=None, gameState='', name='', fileName='', horizontalMiddlePromille=500, verticalMiddlePromille=500, horizontalSizePromille=500,  verticalSizePromille=500, rotation=0, stretch=True, alphaValue=255, visible=True):
    
class Button():
    def __init__(self, blitToSurface=None, gameState='', name='', horizontalMiddlePromille=500, verticalMiddlePromille=500, horizontalSizePromille=500,  verticalSizePromille=100, colorNormal=(190,190,190), colorHasFocus=(190,255,190),colorMouseOver=(190,190,255),colorMouseDown=(255,190,190), value=None, alphaValue=255, hasFocus=False, visible=True, onClick=None, text='button', enabled=True, sysFont=True, fontName='timesnewroman', fontSizePromille=80, antiAlias=True):

class CheckBox():
    def __init__(self, blitToSurface=None, gameState='', name='', horizontalMiddlePromille=500, verticalMiddlePromille=500, horizontalSizePromille=500,  verticalSizePromille=500, inColor=(190,190,190), outColor=(135,135,135), tickColor=(100,100,100), alphaValue=255, widthMargin=5, widthBorder=5, value=True, hasFocus=False, visible=True, onClick=None):  

class InputBox():
    def __init__(self, blitToSurface=None, gameState='', name='', text='', colorText=(255,255,255), horizontalMiddlePromille=500, verticalMiddlePromille=500, sysFont=True, fontName='timesnewroman', fontSizePromille=100, isBold=False, isItalic=True, antiAlias=True, alphaValue=255, visible=True, hasFocus=False, onClick=None, maxSize=15):


License
----

MIT License

Copyright (c) 2020 Bas Koning

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


Hire us: basknng@gmail.com

