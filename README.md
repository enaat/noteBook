# 1. 首页效果图：
![image](https://github.com/enaat/noteBook/blob/master/src/assets/home.png)

# 2. 加入收藏以及取消收藏，收藏列表中相应的内容也会删除：
![image](https://github.com/enaat/noteBook/blob/master/src/assets/result1.png)

# 3. 右侧文本框可实现相应内容的同步更新：
![image](https://github.com/enaat/noteBook/blob/master/src/assets/result2.png)

# 4. 实现收藏的删除以及添加 -》 通过内容的比较来找到其索引值，从而删除收藏的相应内容
# （这里我之前忘记添加id值了，所以我是通过内容来比较的，下次一定注意）；

# 5. 在vuex中定义了一个变量，editIndex（存储当前被点击的列表项的索引值），便于后面实现删除以及数据更新等功能。

# 6. 使用keep-alive组件实现了路由切换时仍然会保持之前的点击状态。

# first-vue

> a vue project

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

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
