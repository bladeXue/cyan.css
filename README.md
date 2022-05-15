规范采用SMACSS，业务代码采用BEM

以Pure为底板（雅虎的，本身就是SMACSS规范），一些设计参考了tt和material，部分组件风格上看了weui。反正最终效果就是多抄抄[https://github.com/primer/css](https://github.com/primer/css)，因为它的组件实在是太多了

在实现原型的过程中，融合了一些pure site的代码，尽量做减法，确保样式的纯净，同时对于一些default属性，我还是选择不将其写出来（但是填写到注释里），因为这样后面改写的时候，会更有目的性，会更加方便一些

布局学习参考了learnlayout

## 目录

可以看看kube的sass目录，其衍生版本superkube是个纯scss项目

## 栅格

参考unsemantic，因为有sass

## 预处理器

用了预处理器，主要包括：

1. 变量
2. 操作符
3. 混合器
4. 嵌套
5. 函数
6. 插值
7. 文件导入
8. 扩展/继承

## 图标

字体图标的选用：

1. Ionicons有457个图标，可以纯SVG使用
2. css.gg来自reddit有704个图标
3. eva-icons稍微有一点花哨

## 关于angular和框架

angular本身提供了非常多的轮子，比如一个flex系统，我的本意是做一个学习用的css框架，同时可以独立于框架，不依赖任何一个，所以我的态度还是学习这些轮子，整合进我的css，平时工作时候，具体用轮子还是自己的，再做选择，总是我的框架一定是要不断进步的。










