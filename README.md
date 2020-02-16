# grid-system1
实现栅格系统

### 栅格系统
Bootstrap和Foundation等前端库都提供了一套响应式的栅格（网格）系统，方便开发者实现各种形式的网页布局。栅格系统的主要目标是为开发者摆脱复杂的CSS布局代码，通过建立行(Row)与列(Column)的概念，就可以轻易创建规范的布局，开发者需要的是只是将内容放进栅格系统。

### 实现原理
栅格系统暴露给开发者的概念只有行(Row)和列(Column)，但其内部实现还是CSS布局的应用，在CSS中最常用的布局方式一般有两种float和position。Boottrap中的栅格系统主要是使用了float来实现，这是一种比较浏览器兼容的布局方法。 一个栅格系统主要包含三部分 1. container(容器) 2. row(行) 3. column(列) 4. gutter(间距)

[预览链接](http://js.jirengu.com/lepot/3/edit?html,css,output)
