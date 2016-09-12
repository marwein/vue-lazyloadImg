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