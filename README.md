#v-if指令
 v-if是条件渲染指令，它根据表达式的真假来删除和插入元素

#v-show指令
 v-show也是条件渲染指令，和v-if指令不同的是，使用v-show指令的元素始终会被渲染到HTML，它只是简单地为元素设置CSS的style属性。

#v-else指令
 可以用v-else指令为v-if或v-show添加一个“else块”。v-else元素必须立即跟在v-if或v-show元素的后面——否则它不能被识别。

#v-for指令
 v-for指令基于一个数组渲染一个列表
 v-for="item in items"

#v-bind指令
 v-bind指令可以在其名称后面带一个参数，中间放一个冒号隔开，这个参数通常是HTML元素的特性（attribute），例如：v-bind:class

#v-on指令
 v-on指令用于给监听DOM事件，它的用语法和v-bind是类似的，例如监听<a>元素的点击事件：
 <a v-on:click="doSomething">

#v-bind和v-on的缩写
 Vue.js为最常用的两个指令v-bind和v-on提供了缩写方式。v-bind指令可以缩写为一个冒号，v-on指令可以缩写为@符号。


博文地址：http://www.cnblogs.com/keepfool/p/5619070.html

