cardview
========

This is a little control to browse through a collection of items like they were cards in a deck or in rolling file device (rolodex). Mostly useful on mobile, but desktop compatibility has been added for ease of debugging.

To reduce memory footprint only 3 cards are loaded at any given time but you can browse an infinite number of items. Also the collection is loopable.

The code is still a bit messy and betaish but maybe you can make good use of it.

=========

HomePage：http://jiangzhizi.github.io/cardview/


对其做了如下修改：

- 增加了Effect gallery，
- 增加了部分API，
- 增加了CMD支持，
- 对代码其它部分进行了较多改动。

=========

### API:

 - Config:
    - direction: 'v', // h 、v 
    - effect: 'rotate', //rotate 、 zoom 、 slide 、 gallery
    - loop: true, //循环播放
    - pageDotShow: false, //进度提示点，样式可自定义
    - pageDotContainer: 'body',
    - deg: 25,
    - duration: .28,
    - perspective: '300px',
    - resizePolling: 100,
    - dataset: [], //必传
 - Event:
    - onUpdateContent: function(el,data,dataIndex) {}
 - Method:
    - destroy()
    - enable()
    - disable()

### Demos：

- [gallery](http://jiangzhizi.github.io/cardview/demos/gallery/index.html)

- [rotate](http://jiangzhizi.github.io/cardview/demos/rotate/index.html)

- [slide](http://jiangzhizi.github.io/cardview/demos/slide/index.html)

- [zoom](http://jiangzhizi.github.io/cardview/demos/zoom/index.html)

感谢原作者。

