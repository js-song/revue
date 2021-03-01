<!--
 * @Author: song
 * @Date: 2021-03-01 14:19:58
-->
- data: {} 和 data() {}
- vue页面刷新会闪现占位符{{anything}}
    - 解决方法: 添加v-cloak
- computed 属性默认只有getter没有setter，不过可以自定义setter
- 当需要在数据变化时执行异步或开销较大的操作时，使用watch
- 用 key 管理可复用的的元素
- v-if 和 v-show
  - v-show不支持\<template>元素，也没有v-else
  - v-show只是简单的css样式切换
- v-if 和 v-for 不推荐一起使用，v-for优先级更高
- v-for 遍历对象时，Object.keys(),不能保证在不同的js引擎下都一致
