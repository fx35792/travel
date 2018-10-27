# travel

> A Vue.js project

## install vue
``` bash
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

## create vue
``` bash
npm init webpack travel
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

### 单页应用
``` bash
优点：页面切换快
缺点：首屏时间稍慢，SEO差
```

### 多页应用
``` bash
优点：首屏时间快，SEO好
缺点：页面切换慢
```
### 准备工作
``` bash
1.reset.css     //初始化标签
2.border.css    //解决有些手机 border一像素的问题
3.faseclick     //解决移动端点击延迟300毫秒的问题
4.iconfont      //通过字体来解决一些小的图标显示问题    优化图片 响应速度会更快
```

