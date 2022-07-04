<!--
 * @Descripttion: ----描述----
 * @version: 1.0
 * @Author: 张鹏
 * @Date: 2022-07-04 16:35:02
 * @LastEditors: 张鹏
 * @LastEditTime: 2022-07-04 16:45:50
-->

# Shepherd Vue

基于 shepherd.js 封装的 Vue.js 版本的新手引导组件。

## 快速开始

1、安装

```bash
# npm
npm i @springsheep/shepherd-vue

# yarn
yarn add @springsheep/shepherd-vue
```

2、导入。

支持两种导入方式使用。第一种是全局导入：

```js
import Vue from 'vue'
import Shepherd from '@springsheep/shepherd-vue'

Vue.use(Shepherd)

// 会在 Vue 实例上挂载 $shepherd 函数，通过调用 `$shepherd` 函数来使用
this.$shepherd(config)
```

另一种是局部导入使用：

```js
import { shepherd } from '@springsheep/shepherd-vue'

// 使用
shepherd(config)
```

`config` 的具体配置参见[这里](https://shepherdjs.dev/docs/index.html)

## License

[MIT](/LICENSE)
