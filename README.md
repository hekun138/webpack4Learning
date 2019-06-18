# webpack4Learning
## demo02 编译ES6
- babel-polyfill：es6内置方法和函数转化垫片
- babel-loader：负责es6语法转化
- @babel/preset-env：包含es6、7等版本的语法转化规则
- @babel/plugin-transform-runtime：避免polyfill污染全局变量
- 需要注意的是, babel-loader和babel-polyfill。前者负责语法转化，比如：箭头函数；后者负责内置方法和函数，比如：new Set()。


