# 立即执行函数IIFE

## 什么是立即执行函数

一个立即执行的匿名函数,英文全称(Immediately-invoked function expression)

## 立即执行函数的写法
``` javascript
// 写法一
(function(name) {
  console.log(`hello${name}`)
})('yeyi')

// 写法二
(function(name) {
  console.log(`hello${name}`)
}('yeyi'))

// 写法三(!还可以用 + 、 - 代替)
!function(name) {
  console.log(`hello${name}`)
}('yeyi')
```

## 立即执行函数的优点

* 匿名函数，不占据变量名，避免命名冲突
* 创建独立作用域，避免变量污染
* 函数执行完，释放内存

欢迎大家关注我的[笔记](https://github.com/yeyi361936738/notebook),每天记录一篇知识点