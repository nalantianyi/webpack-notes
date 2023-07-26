# webpack-notes[持续更新中]

一份webpack的学习和深入分析的教程，针对webpack5系列，使用教程，深入实战，源码分析，一些面试题分享
从0到1，从1到多，一步一个脚印

## 思路

先从现有的webpack入手，了解使用和实战部分，然后尝试自己手写webpack内核，跑通对应的webpack生态的插件，跑通官方测试用例，并替换到项目的demo中【对我来说非常有挑战】

## 目录拆分

| 目录       |   作用   |    备注  |
| --------- | ----    | ---- |
| docs/     |  文档    | 教程文档 |
| packages/ |    源码  | 自己从0开始撸一个webpack核心 |
| examples/ |  demos    | 教程对应的实践代码 |
| tests/		| 测试用例 ||

## 环境
建议使用pnpm进行管理

## 有点话说

虽然现在例如vite，snowpack等打包工具也都非常优秀，也日趋成熟，作者并不想去比较技术和轮子之间的优劣，各有千秋，仅仅是本着学习和强化自身认识的角度去写这么一个系列，对作者本身而言一是温故，二也是从头开始系统性地从0开始审视和分析下这么一个经久不衰的强大工具。


webpack最初的版本可以追溯到11年前，也就是2012年，正如它当初的目标一样，在那么一个年代，诞生了这么一款经历历史检验的打包工具，还是相当难得的，后面会有专门的章节去回溯下往事。

- bundle CommonJs modules for browser
- reuse server-side code (node.js) on client-side
- create multiple files which are loaded on demand
- dependencies managed for you
- faster page load in big webapps

由于作者能力有限，针对本系列中的一些错误或者不如，还请大家积极指正



## 参考资料

1. [官网](https://webpack.js.org/)

**更多分享可以关注**

<img src="https://raw.githubusercontent.com/nalantianyi/my-pics-base/master/202307251603062.jpg" alt="" style="zoom:25%;" />

**觉得作者写的还行的话加wx聊一聊**

<img src="https://raw.githubusercontent.com/nalantianyi/my-pics-base/master/202307251602453.jpg" alt="3171690254350_.pic" style="zoom:20%;" />

**或者打赏杯咖啡**

<img src="https://raw.githubusercontent.com/nalantianyi/my-pics-base/master/202307251603949.jpg" alt="3161690254349_.pic" style="zoom:25%;" />