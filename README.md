[![npm version](https://badge.fury.io/js/vue-lazyloadimg.svg)](http://badge.fury.io/js/vue-lazyloadimg)
[![NPM Downloads](https://img.shields.io/npm/dm/vue-lazyloadimg.svg)](https://www.npmjs.com/package/vue-lazyloadimg)

[![NPM](https://nodei.co/npm/vue-lazyloadimg.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/vue-lazyloadimg/)

[![NPM](https://nodei.co/npm-dl/vue-lazyloadimg.png?height=3)](https://nodei.co/npm/vue-lazyloadimg/)

# How do use?
## [中文](README.CN.md)
![效果展示](http://ww3.sinaimg.cn/large/882a72d0gw1f7qycyxootg20i70hd7wh.gif)
## step 1 install
```javascript
npm install --save vue-lazyloadimg
```

## step 2 use vue
import vue-lazyloadimg
```javascript
import vueLazyImg from 'vue-lazyloadimg';
import vue from 'vue';
vue.use(vueLazyImg);
```

## step 3 .vue setting image
module read class `lazyimg` and cache to onscroll event.
``` html
<img src="{{'1x1 transform png'}}" :data-src="{{need load img url}}" class="lazyimg" alt="">
```

# build script
use babel.