# learn-vue3

## lesson01

> 创建一个 html 文件，加载 vue。

## lesson02

> 创建一个 count 文件，编写一个计数器，认识了 data、mounted。

## lesson03

> 创建一个 demo 文件，编写一个按钮绑定事件，认识了 methods, v-on，@，v-if

## lesson04

> 创建一个 demo 文件，编写一个循环事件，认识了 v-for 循环指令，v-model 数据双向绑定.

## lesson05

> 创建一个 index 文件，编写一个组件，认识了 组件，v-bind 绑定。

## lesson06

> 创建一个 index 文件，认识了 createApp()和 mount(),学习了如何获取和使用根组件，在学习根组件的时候又讲解了 Vue 框架的基本模式是 mvvm，并对 mvvm 模式进行了具体讲解。

## lesson07

> 创建一个 index 文件，了解了 vue 的生命周期。

![](https://newimg.jspang.com/Vuelifecycle.png)

## lesson08

> 创建一个 index 文件，编写一个组件，认识了 v-once v-html。

## lesson09

> 创建一个 index 文件，了解了 v-on、v-bind 的简写和动态属性。

## lesson10

> 创建一个 index 文件，了解了 条件判断 三元运算和 v-if。

## lesson11

> 创建一个 index 文件，了解了 计算属性 computed。

## lesson12

> 创建一个 index 文件，了解了 侦听器（监听器）watch。

- computed VS watch
  计算属性 computed 必须要返回一个值，而且在页面渲染的同时就会执行里边的业务逻辑，也就是会先执行一遍你写的业务逻辑，而 watch 只有发生变化时才会执行，也就是说值没有变化，它是不执行里边业务逻辑的。

* methods computed watch 优先级
  method、watch 和 computed 三者如果都能实现相同的功能，它们之间的取舍和使用优先级。
  1. computed 和 method 都能实现的功能，建议使用 computed,因为有缓存，不用渲染页面就刷新。
  2. computed 和 watch 都能实现的功能，建议使用 computed，因为更加简洁。

## lesson13

> 创建一个 index 文件，了解了 模板样式绑定。
