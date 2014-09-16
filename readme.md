A browser-based Delaunay triangulation generator with drag-and-drop uploading. Delaunay triangulation produces a generally recognisable low-polygon version of the original image.

###[Click here to play with a working example of this code.](http://internets.computer/delaunay/)

Before and after:
![Example before and after image](https://github.com/timbennett/delaunay/blob/master/sample.jpg "Before and after Delaunay triangulation")

##Configuration options (index.js): 

    EDGE_DETECT_VALUE: Lower this to increase edge contrast sensitivity
    POINT_RATE: "Number of points distribution ratio of points (number) on the edge, detail, generated higher see console" (Google Translate of "エッジ上のポイントの分布比率, 高いほど詳細, 生成されたポイント数はコンソールを参照")
    POINT_MAX_NUM: Maximum points sampled. Higher = more detail.
    BLUR_SIZE: Smaller is more detailed.
    EDGE_SIZE: Larger is more detailed.
    PIXEL_LIMIT: Images may have this many pixels at most (width x height) or will be resampled. Have had no trouble setting this to ~10,000,000 or more.
    
##Wishlist:

* Expose the configuration options in the front end, to enable more fluid experimentation.

##Attribution & License

Forked from http://jsdo.it/akm2/xoYx

Images from Wikimedia Commons:

* http://commons.wikimedia.org/wiki/File:Lilac-Breasted_Roller_with_Grasshopper_on_Acacia_tree_in_Botswana_(small)_c.jpg
* http://commons.wikimedia.org/wiki/File:Red_Apple.jpg

Code Licensed under the MIT License (MIT):

Copyright (c) 2012 akm2

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
