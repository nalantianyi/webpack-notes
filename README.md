# webpack-notes[持续更新中]
一份webpack的学习和深入的里程，针对webpack5系列，使用教程，深入实战，源码分析，可能的一些面试题分享
[webpack官方仓库传送门](https://github.com/webpack/webpack)
## 思路
先从现有的webpack入手，了解使用和实战部分，然后尝试自己手写webpack内核，跑通对应的webpack生态的插件，跑通官方测试用例，并替换到项目的demo中【对我来说非常有挑战】
## 目录拆分

## 有点话说
虽然现在例如vite，snowpack等打包工具也都非常优秀，也日趋成熟，作者并不想去比较技术和轮子之间的优劣，各有千秋，仅仅是本着学习和强化自身认识的角度是写这么一个系列

![image.png](https://cdn.nlark.com/yuque/0/2023/png/471977/1690261907360-5045bf7e-b9c6-4218-86ad-d42b92e97c06.png#averageHue=%23f5f5f4&clientId=u303db131-1b0a-4&from=paste&height=739&id=u6a0305de&originHeight=1478&originWidth=2478&originalType=binary&ratio=2&rotation=0&showTitle=false&size=399424&status=done&style=none&taskId=ubddd1708-0d03-465e-a6a4-32c5a0c15e7&title=&width=1239)
webpack最初的版本可以追溯到11年前，也就是2012年，正如它当初的目标一样，在那么一个年代，诞生了这么一款经历历史检验的打包工具，还是相当难得的，后面会有专门的章节去回溯下往事。

- bundle CommonJs modules for browser
- reuse server-side code (node.js) on client-side
- create multiple files which are loaded on demand
- dependencies managed for you
- faster page load in big webapps

由于作者能力有限，针对本系列中的一些错误或者不如，还请大家积极指正

**更多分享可以关注**
![扫码_搜索联合传播样式-标准色版.jpg](https://cdn.nlark.com/yuque/0/2023/jpeg/471977/1690253880304-5aec5234-756e-43d9-a03d-370d005191e0.jpeg#averageHue=%23fdfefc&clientId=u303db131-1b0a-4&from=paste&height=178&id=TJFwL&originHeight=624&originWidth=1710&originalType=binary&ratio=2&rotation=0&showTitle=false&size=143140&status=done&style=none&taskId=uabc4731d-4c22-4420-9f09-4f0d9f269ba&title=&width=487)
**觉得作者写的还行的话加wx聊一聊或者打赏杯咖啡**

![image.png](https://cdn.nlark.com/yuque/0/2023/png/471977/1690254376341-b85949e1-aa91-45ec-85ac-acfd702e8fb9.png#averageHue=%23d5d5d5&clientId=u303db131-1b0a-4&from=paste&height=259&id=QHwnx&originHeight=1575&originWidth=1194&originalType=binary&ratio=2&rotation=0&showTitle=false&size=250949&status=done&style=none&taskId=u3b347e08-9b67-4e30-bca4-412834b122b&title=&width=196)![image.png](https://cdn.nlark.com/yuque/0/2023/png/471977/1690254391914-9b48b4dd-7a14-45e0-98a2-2519e9a88631.png#averageHue=%23f9f9f4&clientId=u303db131-1b0a-4&from=paste&height=281&id=tOPzD&originHeight=1124&originWidth=828&originalType=binary&ratio=2&rotation=0&showTitle=false&size=124326&status=done&style=none&taskId=u9a142675-b88c-4db8-aa3c-3358e6be3f1&title=&width=207)
