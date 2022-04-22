in_1

# week1

## day 1

![image-20220222103155724](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222103155724.png)

![image-20220222110442665](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222110442665.png)

![image-20220222110448999](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222110448999.png)

确实是少了一个

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCsOVVh65Ee4R0fg6KzUeqtirQHbbWcrX0AUl5I84eyicO0nZJUmwG5Xs+4begQBARRbR9NB3BA9wPgJnwm1Mpc3p7GnLYOTcrc17NvsmOfy0AtHr9/raLppml/GZTwipbuXI1Zqro+Q5Cvs6a3D1ohocqFiDSebY0x+O2C2fX3WM+ARJK19sfm/WL58MUebxFiT7HjfiS87nlczWOE0sGfWndk9HMQ7J7w+sSJ1//s2W2PONk0VgnjtbKfFjoGWwaTfIvPN6r2Q6X1VnY5z0H7dgb9qO9ZxmskfKrSEM+bZirOIMp4Yr4gO+dnnGLpGUwQQl4NFh0su9XJz5DtuMTbfvIc7oCMv7hnoyxRKYefn1Bf+GazNJU6HxlEO6xWt2YUOIRn5pkIbUMkTIXtRkHSWVyd7nwL7ny1Td/TIJvvAuOzGDtmcG6QpKg9r9aKGxbc9wM1ilO/CwZRtXr+IgN0CA6A8agTPF3W3gykhrTEZICS/7D755dkimqApxucL48= 2448297223@qq.com



![image-20220328133113966](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220328133113966.png)

暂时没懂这是为了什么

![image-20220222110802474](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222110802474.png)

![image-20220222152909884](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222152909884.png)

这个应该是统一组件的意思 ；；

### react 文档在学习



在 React 应用中，数据通过 props 的传递，从父组件流向子组件

![image-20220222160313893](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222160313893.png)

![image-20220222160524437](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222160524437.png)

每次在组件中调用 `setState` 时，React 都会自动更新其子组件

当你遇到需要同时获取多个子组件数据，或者两个组件之间需要相互通讯的情况时，需要把子组件的 state 数据提升至其共同的父组件当中保存。之后父组件可以通过 props 将状态数据传递到子组件当中。这样应用当中所有组件的状态数据就能够更方便地同步共享了





一般来说，有两种改变数据的方式。第一种方式是直接*修改*变量的值，第二种方式是使用新的一份数据替换旧数据

![image-20220222162946447](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222162946447.png)

 this.state  this.prop 暂时不明白

![image-20220222163955364](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222163955364.png)

![image-20220222170626036](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222170626036.png)

我们建议从组件自身的角度命名 props，而不是依赖于调用组件的上下文命名

![image-20220222171353484](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222171353484.png)

![image-20220222172256103](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222172256103.png)

![image-20220222172359552](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222172359552.png)

State 的更新可能是异步的

暂时未知是什么玩意

你必须谨慎对待 JSX 回调函数中的 `this`，在 JavaScript 中，class 的方法默认不会[绑定](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_objects/Function/bind) `this`。如果你忘记绑定 `this.handleClick` 并把它传入了 `onClick`，当你调用这个函数的时候 `this` 的值为 `undefined`

![image-20220222191723129](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220222191723129.png)

## day2

https://react.docschina.org/docs/faq-state.html#what-is-the-difference-between-state-and-props

state和prop的区别

![image-20220223091953854](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223091953854.png)

![image-20220223092828845](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223092828845.png)

![image-20220223092823052](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223092823052.png)

### ES6再看文档

=== && ==

![image-20220223093548841](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223093548841.png)

```js
let sy = Symbol("KK");
console.log(sy);   // Symbol(KK)
typeof(sy);        // "symbol"
 
// 相同参数 Symbol() 返回的值不相等
let sy1 = Symbol("kk"); 
sy === sy1;       // false
```



![image-20220223100209562](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223100209562.png)



proxy && reflect

箭头函数



this指向问题 好奇怪啊

为什么第一个是全局第二个是自身啊



因为第一个this的实际调用者是setTimeout是windows对象的

![image-20220223112003095](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223112003095.png)

![image-20220223105855789](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223105855789.png)

https://www.cnblogs.com/huihuihero/p/11028252.html

hook相关 感觉这是个难点

![image-20220223164901281](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223164901281.png)

https://react.docschina.org/docs/hooks-state.html

![image-20220223165759839](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223165759839.png)

setCount的意义是更新

![image-20220223170003427](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223170003427.png)

![image-20220223170341839](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220223170341839.png)

划分问题，初学的时候不知道什么是够用的



## day3

开始自己的第一个react网页

开始捣鼓了

px、em、rem区别介绍

https://www.runoob.com/w3cnote/px-em-rem-different.html

开始用umijs

现在多是单页面多组件    这类相当于组件的切换

触类旁通的前提是触类

15：57 效率极低 吃了点水果感觉好多了

嵌套路由的概念

现在才觉得能全力以赴做一件事情是真的很幸福的事情

可能人生就是在追求这样的平衡吧

关于解决没有html文件的

然后是umijs ui的使用   这个好像没有什么用 

现目前的任务是完成第一个静态界面

https://blog.csdn.net/qq_43894292/article/details/121609076

vscode中yarn不能用的情况 参照如上链接



umijs和antd的关系

明天要搞懂路由相关

## day4

以后写文档的话一定一定要写清楚在哪个文件，哪里输入（命令行？）

这样要不然对新手太不友好了

1. 

![image-20220225090724399](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225090724399.png)

啧 就无语 唉 

但是不能唉声叹气，加油干

2. description标签

https://may90.com/jiaocheng/description.html

感觉是客户端搜索的时候需要用的

== 无语了 是description

https://ant.design/components/descriptions-cn/

早上的任务是看懂模板并且能修改模板



gre这个逻辑题好无语啊    感觉自己得多做题啊

11:11 准备开始改

下午 13：13开始干活

ConfigProvider没有的问题     升级dtd里面的版本号之后再重新安装

面包屑配置

![image-20220225135859683](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225135859683.png)

![image-20220225143056463](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225143056463.png)

这个部分是水印



应该再加一个选择树的组件（有人问就是好）

![image-20220225151030112](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225151030112.png)

关于id是在哪里被渲染的问题，这个和我最开始的想法很像

使用umi的话他就会给你自动弄好了

![image-20220225154832509](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225154832509.png)

问题在这里





突然想到一个比喻

使用工具的人和创造工具的人

就像是创造游戏的人和打游戏的人

没有打游戏的精彩操作，这个游戏没法常青





再次复习umijs中 路由部分

history再复习

```js
import { history } from 'umi';
// 跳转到指定路由
history.push('/list');
// 带参数跳转到指定路由
history.push('/list?a=b');history.push({  pathname: '/list',  query: {    a: 'b',  },});
// 跳转到上一个路由
history.goBack();
```

![image-20220225161639854](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225161639854.png)

![image-20220225161715893](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225161715893.png)

真正组件的位置

有个随时可以问的人就是好

问题是这个树型组件是如何添加上的



---

we are always distracted from something else from what we are doing , so list what we are now focusing on and further more we find that the process of solving problem give us a positive feedback, which can improve our study efficiency as well.

---



we need to locate the position of component firstly.

![image-20220225164248944](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225164248944.png)



then figure out how the two file interact with each other.

the color is confusing that the classify of file can be tell clearly. 

![image-20220225165217969](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225165217969.png)

add one RiverTree in the return sentence and the problem is solved :)

now we reform the page or we build a new one 

16:53

where is this kind of navigate bar's configuration

![image-20220225170136330](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225170136330.png)

we can find the layout in the   ` router.config.js`

we need to pay attention that following children path as we thought is not be contained in the parent path 

they are at the **same level**

![image-20220225170732390](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225170732390.png)

 In the next time my first assignment is to figure out the layer of the react component

![b0bf95241268e2099125bf06e7b7219](https://gitee.com/chenweigen13/photo/raw/master/img/b0bf95241268e2099125bf06e7b7219.jpg)





Each pop-up is a new component



now I can really modify the frame 17:56 



have a nice week :)

![image-20220225180200569](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220225180200569.png)







# week2

## day 1

continue the project

- try to add a Rivertree component

![image-20220228091312422](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228091312422.png)



![image-20220228092609785](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228092609785.png)

It seems that the label Tooltip does not work

![image-20220228092810274](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228092810274.png)

> JSX 表达式必须具有一个父元素

缺什么就import什么

如何让他随着事件触发而显示   == 好像不太现实啊,本身存在的话就意味着一进来就要render 所以如果这样想的话只能是   单独再路由出去？

![image-20220228094347786](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228094347786.png)

并且页面缩放也不正常了  -> 应该是css的问题

![image-20220228101202095](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228101202095.png)

一个相当于组件一个相当于路由

什么时候return哪个    单独本身界面就return  路由出去就history.push

![image-20220228102632155](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228102632155.png)

这类怎么用

- 组件间传参

![image-20220228103304482](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228103304482.png)

确实是这么传递参数的

- Modal
- ![image-20220228110646261](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228110646261.png)

13:23 开始改造



目标

![react](https://gitee.com/chenweigen13/photo/raw/master/img/react.png)



routes为什么这么设置

为什么这几个是同级别

![image-20220228133901547](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228133901547.png)



小悟一下 因为这是单页面 相当于这是四个页面

![image-20220228135404160](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228135404160.png)

暂未完成component编写

![image-20220228141022446](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228141022446.png)

为什么呢

![image-20220228143347626](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228143347626.png)

这里会默认生成index

- 如何添加这个

![image-20220228143517334](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228143517334.png)

![image-20220228143627592](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228143627592.png)

这种叫什么呢   不是下面这个

就是一个单纯的tree

![image-20220228151822342](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228151822342.png)

![image-20220228151838336](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228151838336.png)

要注意这里还得是一个可以搜索的

![image-20220228152257829](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228152257829.png)

- 如何添加进去呢, 这类js/ts控件

![image-20220228155848399](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228155848399.png)

![image-20220228160127899](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228160127899.png)

但是其实是传进来了的

暂时找不动了,看react去了

问题是rivertree的less 中height高度不够



现在是在react中修改css

学习这部分的内容

![image-20220228165916970](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220228165916970.png)



## day2 3 1 

看如何添加事件

![image-20220301090908140](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301090908140.png)

这样是不可以的

![image-20220301092203339](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301092203339.png)

![image-20220301093050099](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301093050099.png)

怀疑是要加这个

效果爆炸

![image-20220301093117780](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301093117780.png)

如何只返回部分    现在确实可以跳转了

用api接口

![image-20220301100312475](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301100312475.png)

![image-20220301103832984](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301103832984.png)

mission complete

- 现在是要获取节点

![image-20220301104759804](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301104759804.png)

在组件内是不能console的

再看箭头函数    已经能够获取每个节点?

- 如何给每个节点添加路由    要对应 

先拿一个数组保存?  达咩    应该就是在每个子节点里面自己加path

- 成功

![image-20220301135948493](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301135948493.png)

- 连起来试试

![image-20220301140640392](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301140640392.png)

可以了 

path是路径   路径是相对应的组件

- 绝对路径相对路径

 注意：相对路径使用“/”字符作为目录的分隔字符，而绝对路径可以使用“\”或“/”字符作为目录的分隔字符。由于“img”目录是“第2章”目录下的子目录，因此在“img”前不用再加上“/”字符。

在 相对路径里常使用“../”来表示上一级目录。如果有多个上一级目录，可以使用多个“../”，例如“http://www.cnblogs.com/”代表上上级目录。假设 “s1.htm”文件所在目录为“E:\book\网页布局\代码\第2章”，而“bg.jpg”图片所在目录为“E:\book\网页布局\代码”，那 么“bg.jpg”图片相对于“s1.htm”文件来说，是在其所在目录的上级目录里，则引用图片的语句应该为：

<body background="../bg.jpg">

- map()

![image-20220301141258375](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301141258375.png)



== 当时怎么把树pia进去的啊   直接把data放进去的

![image-20220301143849248](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301143849248.png)

出现这种情况key的值不能是一样的

key的值可以是中文字符串

如何让这两部分不变呢

![image-20220301145704330](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301145704330.png)

等待问人 

hooks再学习

如何解决服用麻烦的问题



![image-20220301150744987](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301150744987.png)

渲染属性指的是使用一个值为函数的prop来传递需要动态渲染的nodes或组件

- 自己写一个单独的内容组件 组件写好了(应该)

弄完之后要完整的梳理一下这个流程

- 路由层级问题

![image-20220301155455841](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220301155455841.png)

又是这个问题

对于每一次可执行代码都应该保存保存

## day3

尝试把路由弄好   把第一个完整的页面功能完成

为什么就是找不到路径啊

- 什么是脚手架

**在前端范畴中 脚手架是一个工具，安装完脚手架之后可以通过一些命令来快速实现 我们项目基础环境的搭建，不用一个一个自己去配置各种文件，帮我们自动生成了规范性的项目文件目录**

- 生命周期函数

https://blog.csdn.net/weixin_43851769/article/details/88188325

![image-20220302093346900](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302093346900.png)

- 为什么不可以

因为route不行 ==routes==  

![ ](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302094328743.png)

![image-20220302095049387](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302095049387.png)

要注意这里是path不是组件的路径     

- 更改css 

 怎么更改啊 。。。。

div class 和div className

![image-20220302102728872](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302102728872.png)

![image-20220302104046013](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302104046013.png)

 这个实在Taildwindcss里直接改的

- 回顾一下完整的过程



- 注意每一个层次问题

- 什么是一个component 什么是一个新的页面       

- 前后端如何交互
- 我们自己使用的时候vue和react哪个好

前后端交互原理

https://www.jianshu.com/p/f090cc647f22   

看下面这个

https://blog.csdn.net/Gefangen/article/details/83472898

有点计算机网络复习的样子了



![image-20220302144319411](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302144319411.png)

![image-20220302145837502](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302145837502.png)

​	找到了uci的具体方向  现在开始复习计网相关

你要工作的内容和你在学校里学的东西只能说相关联度很低

![image-20220302151240919](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302151240919.png)

```js
//主要就是ajax部分，这里用到了JQuery中的$.ajax函数，详细用法请参照JQ文档
$.ajax({
    'url':'login.php',//第一个参数url，PHP脚本的位置，我要把参数传到什么位置
    'data':{"username":$('#userName').val(),"password":$('#password').val(),},//传递什么数据，这里我用的是json格式，如果不知道什么是json数据，可以自己搜索一下
    'success':function(data){//success表示，当服务器返回数据成功后，该做什么，返回的数据储存在data中，我们直接把data传入函数中。
        switch(data.type){
            case 0:alert('账户不存在');break;
            case 1:{
                $('#userMsg').children('li').eq(2).find('span').html(' '+data.gouwuchenum+' ');
                $('#loginMsg li').eq(1).empty().html('<span>'+data.name+'</span>');
                $('#loginMsg li').eq(2).empty().html('<a href="javascript:tuichu()">退出</a>');
                $('.login').animate({right:-180,opacity:0},400,function(){
                    $(this).css('display','none');
                });
                break;
            }
            case 2:alert('密码错误');break;
        }
    },
    'type':'post',//type是ajax的方法，可以用post可以用get，两种方法的区别可以自己查阅资料
    'dataType':'json',//传递的数据类型，对应我上面的数据格式，这里用json。数据类型也可以是html/xml等
});
```

- json数据 的学习

![image-20220302152524095](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302152524095.png)

![image-20220302152925245](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302152925245.png)

status是哪里来的

![image-20220302154554418](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220302154554418.png)

json文件数据路径的问题



关于前后端https://www.jianshu.com/p/b6e0a0df32ec交互的问题



- 微信云开发
- http://www.axios-js.com/ axios的学习



## day4

- promise的学习

**无阻塞高并发，是nodeJS的招牌，要达到无阻塞高并发异步是其基本保障**

### promise https://www.jianshu.com/p/1b63a13c2701     (未完成)

1. promise==是一个对象==，对象和函数的区别就是==对象可以保存状态，函数不可以==（闭包除外）

2. 并未剥夺函数return的能力，因此无需层层传递callback，进行回调获取数据

3. 代码风格，容易理解，便于维护

4. 多个异步等待合并便于解决

结论：promise作为队列最为重要的特性，我们在任何一个地方生成了一个promise队列之后，我们可以把他作为一个`变量`传递到其他地方。

- CDN

来简单介绍CDN的工作原理

CNAME && A

这样一来当你访问www.abc.com的时候自动跳转到www.cba.com，而且浏览器上显示的域名仍然是www.abc.com

把cName和转向功能混为一谈了。cName只能保证www.abc.com的解析和www.cba.com同步起来，如果是共享ip的主机

- GET POST

get和post请求是HTTP与服务器交互方式

![image-20220304093620034](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304093620034.png)

axios浏览了一次



- SDK概念https://www.zhihu.com/question/21691705
- REACT中Children的概念

- WeChat 开发文档

![image-20220303105227158](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220303105227158.png)

第二三条没有说可不可以

*完成了2月份总结（NUS）*

- ![image-20220303141425851](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220303141425851.png)

接口调用成功的返回函数

### promise再学习 

promise 是一个有着三种状态的对象

当处于 Pending 状态时，无法得知目前进展到哪一个阶段（刚刚开始还是即将完成）

- async

async 函数返回一个 Promise 对象，可以使用 then 方法添加回调函数。

### 云函数相关

![image-20220303151445673](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220303151445673.png)

在小程序中调用这个云函数前，我们还需要先将该云函数部署到云端

云托管可以看做是云函数的高阶版本，更自由灵活，支持任意语言、任意框架、常驻运行，同时也拥有云函数的微信天然鉴权等优势

![image-20220303154419608](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220303154419608.png)

这个好像很方便





- 尝试把小程序布置到网页上

![image-20220303170503132](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220303170503132.png)

如何请求后端的数据

大致思路类似   先看看微信开发文档

![image-20220303174008673](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220303174008673.png)





## day5 

- 第一件事看Fetch

![image-20220304090208864](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304090208864.png)

### ajax和fetch

- 与服务器请求函数的有哪些

- Request()

- 待解决问题     如何用react请求云服务器的东西

onreadystatechange 事件

当请求被发送到服务器时，我们需要执行一些基于响应的任务。

每当 readyState 改变时，就会触发 onreadystatechange 事件。

XML

### 微信云开发尝试



> wx2a68296075573be6 

这个ID可以云开发,另一个不行,不太知道为什么

- 代码写在哪个部分

![image-20220304104420828](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304104420828.png)

图形化创建

- 为什么循环的时候要加key

![image-20220304104930992](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304104930992.png)

如何在云函数内写代码呢     ->     看文档

![image-20220304105816978](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304105816978.png)

https://blog.csdn.net/qq_37954086/article/details/85058796?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164636361916780271982125%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=164636361916780271982125&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-3-85058796.pc_search_result_cache&utm_term=%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%A8%8B%E5%BA%8F%E4%BA%91%E5%BC%80%E5%8F%91&spm=1018.2226.3001.4187

![image-20220304141213080](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304141213080.png)

现在模板里面弄懂云函数的操作机制

没弄明白

关于入口配置的问题

![image-20220304150723111](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304150723111.png)

现在看yapi

### yapi

- mock mock就是对于某些不容易构造或者不容易获取的对象，用一个虚拟的对象来创建的方法。项目开发和测试过程中，遇到以下的情况时，就需要模拟结果返回。

为什么数据不是输入的呢



- react 请求服务器

http://www.axios-js.com/zh-cn/docs/react-axios.html

react 获得了数据并且成功打印

尝试用umijs+antd做电脑端的

这个是有pro布局的

![image-20220304175203750](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220304175203750.png)



- 新的项目来了   这个是后端的暂时不管

- 熟悉antdprolayout





# week3  

要开始接项目了

## day1 307 

scbb学习以及自己的网页

![image-20220307093017089](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220307093017089.png)



尝试添加一个表格   成功

![image-20220307101431881](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220307101431881.png)

现在需要具体一下页面的功能

==尝试添加一个表格==

![image-20220307102240864](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220307102240864.png)

![image-20220307112310949](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220307112310949.png)

- 如何获取到json的数据

为什么要找中介   自己需要获得什么中介能够提供但是我自己不能的

现在可以获得数据，但是不能获得**相对应**的数据



- 看云函数了     关于如何开启本地调试这一点









## day2 308

![image-20220307174440399](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220307174440399.png)

要新建右键node.js文件

然后是如何调用

*部署完成后，我们可以在小程序中调用该云函数*    在哪调用

- 开会    感觉效率很低
- JSX必须有父元素





关于如下形式

https://blog.csdn.net/hyupeng1006/article/details/109331589

![image-20220308133528490](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220308133528490.png)

目前要求效果图

![image-20220308134411242](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220308134411242.png)

![image-20220308135145770](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220308135145770.png)

要把这个给拔下来

pageheader 无法使用

css折腾半天是因为没安装tailwindcss

css颜色问题暂时不知道怎么办

那个form的问题

## day3 309

### 添加组件

![image-20220309095304955](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309095304955.png)

基础完成大概了这个页面

现在更改其交互按钮

### 在JSX中使用console.log

console.log(text)   no

{console.log(text)}   yes    圆括号里面是表达式

![image-20220309105649479](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309105649479.png)

如何与事件绑定呢

### English

![image-20220309131908776](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309131908776.png)

![image-20220309132407754](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309132407754.png)

这类题目比较容易想到第一个大点

![image-20220317195603116](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220317195603116.png)

doing more extra work or assignments that are required



1. The leader can judge your contribution by the result of your assignments.

The process and result of your what you have done can be seen while the result of contributing an idea usually not. 

1. The additional experience by doing assignments will assist you to solve the relative problem in the future. To be more specific, generating an idea can not help you in improving the ability of solving problems while practicing does. 

   Take myself as an example, in my first year in the university, I joined many clubs and study groups, proposing many ideas and trying to exercise my ability of thinking. However, at the examination of the first semester, I found that I can only have many thoughts of how to solve the questions but I could not solve them in reality. Finally the grades indicate that proposing ideas can not improve the grades efficiently. So, I then started to do more assignments, trying to change the bad situation. After a long time of exercising, in the next semester, I had done much more assignments than others. And then at that examination, I found that I can solve all questions quickly, because I had done the similar question in my extra homework while others not. Some questions on paper are even totally same as what I have done. According to my own experience, I agree to do more extra work.

2. The leader usually give more awards to the worker who finishes more than the one who speaks more. It is known that all leaders are not interested in those people who can only propose ideas without solutions. 

   For instance, and this is also my experience. Last summer vacation, I had a short internship in an Internet company, which has many projects to do. So we frequently had meeting during that time due to some bugs in projects. In these conferences, my partner were more active to propose ideas. However, these recommendations did not take into account the difficulty of the solution. At first, the leader suggested him to think twice before speaking but he did not change his habits, which means he still proposed many unreasonable ideas. Many times later, the leader finally could not stand him and my partner was failed in the internship. 

我总是先想到解释再想到主题句



---

Furthermore the fact of `point` indicates that`reason`

character -> process -> result 

Take the case of `character`, who `process`. As a `result`  

Had it not been for  *process paraphrase*, *character* would never *result*









background   background-color

![image-20220309141944980](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309141944980.png)

![image-20220309145337425](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309145337425.png)

![image-20220309150427668](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220309150427668.png)

问题在于有没有花括号

- import花括号的区别

https://www.cnblogs.com/ranyonsue/p/11468727.html

- react创建组件的方式

https://blog.csdn.net/qq_18913129/article/details/105491090

- ts和js的区别

https://www.zhihu.com/question/25421196

## day 4 310 

- 提取组件
- 弄个清楚路径问题

@/   ../     ./



![image-20220310101356871](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220310101356871.png)

- 子绝父相
- css中子元素的各自安排     position的问题

子绝父相就是指子元素设置绝对定位，而父元素设置相对定位，然后设置子元素的*top*、*left*、*right*、*bottom*的值，我们就可以让子元素到达相应的位置

- children的使用  react中

- 准备去开会了

- 回来讨论留学

- 再开会

  样式有些奇怪

![image-20220310173856595](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220310173856595.png)

![image-20220310175431483](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220310175431483.png)

就不要用rivertree



## day 5 311

- 弄懂搜索框

![image-20220311101831464](../AppData/Roaming/Typora/typora-user-images/image-20220311101831464.png)

这样的组件可以直接写进来





# week4 

## day1 314

完成小项目的东西   

- trial里面
- 看云函数如何上传数据

云函数如何调试   云函数的更新一定要把原先的调试窗口关掉

- 云数据库的使用

1. 如何创建

![image-20220314104647240](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314104647240.png)





- 现在完成代码清理

![image-20220314125445820](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314125445820.png)

完成搜索框的问题





- 这个就是查询了

![image-20220314132359147](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314132359147.png)

- 为什么我的点击没有用呢

![image-20220314134144812](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314134144812.png)

调用函数的问题

![image-20220314135240517](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314135240517.png)









### 测试任务

![image-20220314141127623](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314141127623.png)

![image-20220314141246073](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314141246073.png)



![image-20220314171954577](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220314171954577.png)

==  这个测试就真的很无用功，是个人就能做 1.3.3 明天继续

---

我听见雨点

然后开始思考自己未来的出路

我很确信一点 我真的很幸福   有追求自己梦想的权利

我能干什么呢, 我适合干什么呢, 我想干什么呢   我的梦想是什么呢,我有点忘记了

教育 , 经济  政治   历史   生在理科的人对文科有着无限的向往.

进Google, 然后呢, 我到底想做什么

教托福  写文书  还是机器人  还是人工智能  操作系统   

疫情之后我想去见识见识外面的世界,那些风土人情, 我想看看世界到底是什么样子的 

上位者的视角和我们普通人的视角又有什么不同的呢

这三者是有顺序的

------



English writing:

1. The large crowds will have a negative impact on our good feeling.  To be more specific, the long queue will waste your time on meaningless waiting. Take myself as an example. Last summer vacation, I invited my family to the Tai Mountain, which is the most popular mountain that time. At the beginning of the travel, I was happy and could not waiting to arrive at the destination. However, when we got to the parking place, we saw a 50 meters long car queue, which means we need to take an hour at least to park the car. Not only at the parking place we waited, but also we consume a long time at the entrance. 

3. It is cheaper to cook at home. To be more specific, if I choose to cook at home with all gradients prepared, the cost will be controlled in a reasonable range, which is often a quarter of the cost spending in restaurant.

   Take myself as an example. Especially for vegetable, you can purchase 1 kilogram tomatoes, which can be cooked for a week, for 6 yuan, but you need to pay 4 times for one dish in a common restaurant that even do not have a full tomato.  Even if we buy the so-called organic vegetable, the cost is still lower than half of the bill in restaurant. What's worse, the cost is higher in some metropolitans. Last summer vacation during my internship, I tried to cook at home to shorten the daily cost. To my surprise, I found that 



现在讲完一个例子之后不知道下一个怎么



## day2 315

测试任务

任务挂起

![image-20220315095426149](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315095426149.png)

 测试任务基本完成

下午13：25 完成测试任务

开始看小程序的数据库



有一说一这个小程序的文档写的是真的差   总之就很不适合新手

获取数据的时候

![image-20220315105102705](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315105102705.png)

![image-20220315132855442](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315132855442.png)

是这个问题么

![image-20220315134602048](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315134602048.png)

![image-20220315134629609](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315134629609.png)

![image-20220315151929912](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315151929912.png)

数据获取到了但是为什么为空

![image-20220315152415995](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315152415995.png)

不是数据库的命名问题，是权限问题 == 好烦哦

![image-20220315154114475](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315154114475.png)

- 为什么这样写无法赋值

没有具体的id的话是无法赋值的





PC端如何获取数据库的数据

https://www.cnblogs.com/yuyujuan/articles/10134020.html

这简直是大好人啊





==pc端如何访问小程序的数据==

https://www.jianshu.com/p/8ee1f870add6



**首先，如果需要访问腾讯云数据库，那么你需要申请access_token，别担心，这个非常简单，按照下面的网址结构替换成你的小程序APPID与app密钥即可**

https://api.weixin.qq.com/cgi-bin/token?grant_type=client_credential&appid=wx5a8c47dfa9ee6850&secret=5be1767f4b3141ff508e4713eecd2639

![image-20220315164011959](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315164011959.png)

```json

{"access_token":"54_mzoKyQJ6qGXUYKhUtnSFIFca8SLaIZi_8u9yO6vyfWKAnOM88YK6NtEZxK1hqfg6RkdsBiwMgW8ptD-JDsXt_6cJrcVifKvqPiPtL5_oU2km_qVEZXLScD6janJOWn9IXfBXNAlGMlem0N5EJRPjABANVT","expires_in":7200}
```



```
https://api.weixin.qq.com/tcb/databasequery?access_token=54_mzoKyQJ6qGXUYKhUtnSFIFca8SLaIZi_8u9yO6vyfWKAnOM88YK6NtEZxK1hqfg6RkdsBiwMgW8ptD-JDsXt_6cJrcVifKvqPiPtL5_oU2km_qVEZXLScD6janJOWn9IXfBXNAlGMlem0N5EJRPjABANVT
```

![image-20220315165000350](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315165000350.png)

![image-20220315165427460](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315165427460.png)

![image-20220315165447894](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315165447894.png)





![image-20220315170622160](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315170622160.png)

![image-20220315170448598](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315170448598.png)





看下面

![image-20220315171716662](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315171716662.png)

https://blog.csdn.net/qq_42042787/article/details/116756332

![image-20220315174102959](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315174102959.png)

不明白













### 前后端对接

前端请求数据请求的是

**在这个条件下返回的后端数据**

![image-20220315141950158](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220315141950158.png)























## day3 316



小程序数据库的事情

### Proxy

为什么要用Proxy

![image-20220316092245479](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220316092245479.png)

我觉得可能是因为这个





==

![image-20220316100931769](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220316100931769.png)



### koa框架

捷径没有了； ；

就得重新来过



![image-20220316103248780](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220316103248780.png)

- 客户端和服务端  前端后端





- 中间件

从这个意义上可以用一个等式来表示中间件：中间件=平台+通信

![image-20220316111544208](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220316111544208.png)





从学习的角度来说我觉得完成流程是最重要的，精细讲解或者是一些目录结的更清晰的划分我建议在完成业务功能之后

 Take myself as an example, my aim is to figure out the flow of data, which means that details do not matter much. However, you can find that the all existed videos or tutorials will introduce each part specifically. I am not say that they are meaningless at all, but they can help little in my process.





重新定义现目前的任务



小程序上传表单数据+电脑端显示

=》

小程序和PC端直接和koa联系，koa和后端联系





koa 脚手架   +   mysql

就得自己学

https://www.jianshu.com/p/8c2489f73f3d

- 脚手架问题 安装依赖的时候免得出错

![image-20220316132111858](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220316132111858.png)

- **async**







对组件的修改原则  

自己的就自己解决，不要让别人改动自己的部分

- 父对子的数据传递拿好了

![image-20220316163559928](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220316163559928.png)

如何对自己定义的组件传数据呢



## day 4  小项目丢一边吧 考完托福再说  现在专注考试

1. 为什么要配置代理
2. ahooks
3. 数据流程

![image-20220317105320956](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220317105320956.png)





- 请求参数和路径参数

请求路径@PathVariable与请求参数@RequestParam的区别





umi使用参数问题

https://www.jianshu.com/p/26ac58f73a90















```json
{"code":200,"description":"请求成功","data":{"total":1,"list":[{"id":null,"tenant":null,"dataSourceName":null,"tableName":"std_jianpei_test_94","tableDesc":"测试表","fieldName":null,"fieldDesc":null,"fieldType":null}],"pageNum":1,"pageSize":10,"size":1,"startRow":1,"endRow":1,"pages":1,"prePage":0,"nextPage":0,"isFirstPage":true,"isLastPage":true,"hasPreviousPage":false,"hasNextPage":false,"navigatePages":8,"navigatepageNums":[1],"navigateFirstPage":1,"navigateLastPage":1}}1



{"code":200,"description":"请求成功","data":{"total":1,"list":[{"id":null,"fieldName":"name","tableName":"std_jianpei_test_94","updateTime":null,"secrecyLevel":2,"fieldDesc":"姓名","fieldType":"string"}],"pageNum":1,"pageSize":10,"size":1,"startRow":1,"endRow":1,"pages":1,"prePage":0,"nextPage":0,"isFirstPage":true,"isLastPage":true,"hasPreviousPage":false,"hasNextPage":false,"navigatePages":8,"navigatepageNums":[1],"navigateFirstPage":1,"navigateLastPage":1}}
```

已经完成了数据的请求

现在要完成数据的获取





![image-20220317190934694](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220317190934694.png)

这样直接拿到的data不能直接使用









## day 5

1. 对hooks的理解

![image-20220318102654982](../AppData/Roaming/Typora/typora-user-images/image-20220318102654982.png)

![image-20220318102707506](../AppData/Roaming/Typora/typora-user-images/image-20220318102707506.png)

2. 为什么是data:{table} = {}
3. table?.

![image-20220318103415139](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220318103415139.png)

![image-20220318103520537](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220318103520537.png)



![image-20220318104921003](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220318104921003.png)



![image-20220318153633881](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220318153633881.png)





我们建议从组件自身的角度命名 props，而不是依赖于调用组件的上下文命名



这个调用父组件到底是哪个调用哪个





```
import React from 'react';
import { Button, Modal, Table } from 'dtd';
import { Col, Form, Row, Select, Input } from 'dtd';
import PageTitleHeader from '@/components/PageTitleHeader';

import { useAntdTable } from 'ahooks';
import { PaginatedParams } from 'ahooks/lib/useAntdTable';
import request from 'umi-request';

// eslint-disable-next-line @typescript-eslint/no-shadow


function onBlur() {
  console.log('blur');
}

function onFocus() {
  console.log('focus');
}

function onSearch(val) {
  console.log('search:', val);
}
function onChange(value: any) {
  // data has been modified as the value chaneged
  console.log(`selectedValue ${value}`);
  this.handleOk(value)
  // this.data_up.secrecyLevel = value
}



// const [form] = Form.useForm();
class Edit_Modal extends React.Component {
  // eslint-disable-next-line @typescript-eslint/no-useless-constructor
  state = { visible: false };
  // { data } = props;
  
  showModal = () => {
    this.setState({
      visible: true,
    });
  };
  
  handleOk = e => {
    console.log('333333333333',this.props.onOk);
    // const data_up= form.getFieldValue()
    this.props.onOk(
      this.props.data
    );    
    console.log('6666666', this.props.data);
    this.setState({
      visible: false,
    });
    
  };
  handleCancel = e => {
    console.log(e);
    this.setState({
      visible: false,
    });
  };
  // onChange =(value)=>{
  //   this.props.hanleOk(value)
  // }
  render() {
    //  const [form] = Form.useForm();
    const level = this.props.data.level

    return (
      <div>
        <div>
          <a style={{ color: 'green' }} onClick={this.showModal}>
            编辑
          </a>
        </div>
        <Modal
          title="修改保密级别"
          visible={this.state.visible}
          onOk={this.handleOk}
          onCancel={this.handleCancel}
        >
          <p>
            <Select
              showSearch
              style={{ width: 200 }}
              placeholder="修改保密级别"
              optionFilterProp="children"
              onChange={onChange}
              onFocus={onFocus}
              onBlur={onBlur}
              onSearch={onSearch}
              filterOption={(input, option) =>
                option.children.toLowerCase().indexOf(input.toLowerCase()) >= 0
              }
            >
              {/* 应该也是从外面取的数据 */}
              <Option value="1">1</Option>
              <Option value="2">2</Option>
              <Option value="3">3</Option>

            </Select>
          </p>
        </Modal>
      </div>
    );
  }
}


export default Edit_Modal;

function value(value: any, level: any) {
  throw new Error('Function not implemented.');
}

```

## additional 

https://blog.csdn.net/sinat_36146776/article/details/106207583

如何完成表单的搜索功能

为什么没有自动请求

是因为参数不符合吗







---

Some own opinions,

We should be aware that every one has diverse personalities. The traditional China has a tradition that a man should be a god. To be more specific, a man should own all good virtue and has no disadvantage, which means you are rich and powerful but you must be kind and generous as well. I am strongly against this idea. 

We always watch the film that the main character is kind, handsome and would love to give his hand to anyone who needs. However, there are some differences between reality and art. The man will have some disadvantages due to his life road, which may have many obstacles. 

They are two questions. 

The 

说的真好

只要还在合法范围内买

那我就买

管我什么事情啊

![image-20220320121139880](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220320121139880.png)

*high level* points 要用最贴切的词语    然后在paraphrase的时候高级词汇





# week 5 

## day1

兄弟之间传递参数、

子组件传递给父组件

就是父组件的方法调用子组件

![image-20220321144845225](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220321144845225.png)

```

import React from 'react';
import { Button, Modal, Table } from 'dtd';
import { Col, Form, Row, Select, Input } from 'dtd';
import PageTitleHeader from '@/components/PageTitleHeader';

import { useAntdTable } from 'ahooks';
import { PaginatedParams } from 'ahooks/lib/useAntdTable';
import { runInContext } from 'lodash';

const treeData=[];


const treeDataaaa = [
];
for (let i = 0; i < 5; i++) {
  treeDataaaa.push({
    key: i,
    tableName: `Edward King ${i}`,
    tableDesc: `London, Park Lane no. ${i}`,
  });
}
//这是为左侧表格添加数据

class Table_left extends React.Component {


  

  state = {
    selectedRowKeys: [], // Check here to configure the default column
    loading: false,
  };

  start = () => {
    this.setState({ loading: true });
    // ajax request after empty completing
    setTimeout(() => {
      this.setState({
        selectedRowKeys: [],
        loading: false,
      });
    }, 1000);
  };


  onSelectChange = selectedRowKeys => {
    console.log('selectedRowKeys changed: ', selectedRowKeys);
    const { onDataSelect, runGetField } = this.props;
    onDataSelect();
    this.setState({ selectedRowKeys });
    runGetField({
      page:1,
      pageSize:10,
      tableNames:selectedRowKeys
    }
      );

  };

  render() {

    const col_li = this.props.columns
    const treeData = this.props.dataSource
    const { selectedRowKeys } = this.state;
    const rowSelection = {
      renderCell: (checked, record, index, node) => {
        return node;
      },
      // checkAllPosition: 'both',
      selectedRowKeys,
      onChange: this.onSelectChange,
      selections: [
        {
          key: 'all-data',
          text: '选择所有页数据',
          onSelect: () => {
            const allRowKeys = treeData.map(({ key }) => key);
            this.setState({
              selectedRowKeys: allRowKeys,
            });
          },
        },
      ],
    };

    return <Table
      rowSelection={rowSelection}
      columns={col_li}
      dataSource={treeData}
      rowKey={record => record.tableName}
    />;
  }






}


export default Table_left


// import { Table, Switch } from 'dtd';

// const columns = [
//   {
//     title: 'Name',
//     dataIndex: 'name',
//     key: 'name',
//   },
//   {
//     title: 'Age',
//     dataIndex: 'age',
//     key: 'age',
//     width: '12%',
//   },
//   {
//     title: 'Address',
//     dataIndex: 'address',
//     width: '30%',
//     key: 'address',
//   },
// ];

// const data = [
//   {
//     key: 1,
//     name: 'John Brown sr.',
//     age: 60,
//     address: 'New York No. 1 Lake Park',
//     children: [
//       {
//         key: 11,
//         name: 'John Brown',
//         age: 42,
//         address: 'New York No. 2 Lake Park',
//       },
//       {
//         key: 12,
//         name: 'John Brown jr.',
//         age: 30,
//         address: 'New York No. 3 Lake Park',
//         children: [
//           {
//             key: 121,
//             name: 'Jimmy Brown',
//             age: 16,
//             address: 'New York No. 3 Lake Park',
//           },
//         ],
//       },
//       {
//         key: 13,
//         name: 'Jim Green sr.',
//         age: 72,
//         address: 'London No. 1 Lake Park',
//         children: [
//           {
//             key: 131,
//             name: 'Jim Green',
//             age: 42,
//             address: 'London No. 2 Lake Park',
//             children: [
//               {
//                 key: 1311,
//                 name: 'Jim Green jr.',
//                 age: 25,
//                 address: 'London No. 3 Lake Park',
//               },
//               {
//                 key: 1312,
//                 name: 'Jimmy Green sr.',
//                 age: 18,
//                 address: 'London No. 4 Lake Park',
//               },
//             ],
//           },
//         ],
//       },
//     ],
//   },
//   {
//     key: 2,
//     name: 'Joe Black',
//     age: 32,
//     address: 'Sidney No. 1 Lake Park',
//   },
// ];

// // rowSelection objects indicates the need for row selection
// const rowSelection = {
//   onChange: (selectedRowKeys, selectedRows) => {
//     console.log(`selectedRowKeys: ${selectedRowKeys}`, 'selectedRows: ', selectedRows);
//   },
//   onSelect: (record, selected, selectedRows) => {
//     console.log(record, selected, selectedRows);
//   },
//   onSelectAll: (selected, selectedRows, changeRows) => {
//     console.log(selected, selectedRows, changeRows);
//   },
// };

// function Table_left() {
//   const [checkStrictly, setCheckStrictly] = React.useState(false);
//   return (
//     <>
//       <div style={{ margin: '16px 0' }}>
//         CheckStrictly: <Switch checked={checkStrictly} onChange={setCheckStrictly} />
//       </div>
//       <Table
//         columns={columns}
//         rowSelection={{ ...rowSelection, checkStrictly }}
//         dataSource={data}
//       />
//     </>
//   );
// }

// export default Table_left









// import React, { useState } from 'react';

// import { Button, Modal, Table } from 'dtd';

// import { Col, Form, Row, Select, Input } from 'dtd';

// import PageTitleHeader from '@/components/PageTitleHeader';



// import { useAntdTable } from 'ahooks';

// import { PaginatedParams } from 'ahooks/lib/useAntdTable';

// import { runInContext } from 'lodash';

// import { render } from 'react-dom';



// // const treeData = [];





// // const treeDataaaa = [

// // ];



// //这是为左侧表格添加数据



// const Table_left: React.FC<{}> = (props) => {



 

//  const [selectedRowKeys, setSslectedRowKeys] = useState([]);

//  const { onDataSelect, onRowSelect, runGetField, setSerecord, id, columns, dataSource } = props



//  const onSelectChange = (selectedRowKeys) => {

//   console.log('selectedRowKeys changed123: ', selectedRowKeys);

//   setSslectedRowKeys(selectedRowKeys);

//   if (selectedRowKeys.length != 0) {

//    runGetField({

//     page: 1,

//     pageSize: 50,

//     tableNames: selectedRowKeys,

//     tenant: 9,

//    });

//    setSerecord(selectedRowKeys);

//    console.log('hhhhhhhhhhhhhhhhhh', selectedRowKeys)

//   } else {

//    setSerecord(null);

//    runGetField({

//     page: 1,

//     pageSize: 50,

//     tableNames: null,

//     tenant: 9,

//    });

//   }

//  };

//  const onSelectAll = () => {

//   console.log('iiiiii', dataSource);

//   if (dataSource[0].tableName) {

//    // const allRowKeys = data.map(({ item }) => item.tableName);

//    const allRowKeys = [];

//    for (let index = 0; index < dataSource.length; index++) {

//     allRowKeys[index] = dataSource[index].tableName;

//    }

//    setSerecord(allRowKeys);

//    for (let index = 0; index < allRowKeys.length; index++) {

//      selectedRowKeys.push(allRowKeys[index])

//    }

//    // setSslectedRowKeys(allRowKeys);

//    console.log('allRowKeysallRowKeys332', allRowKeys)

//    console.log('selectedRowKeys332', selectedRowKeys)

//    runGetField({

//     page: 1,

//     pageSize: 50,

//     tableNames: allRowKeys,

//     tenant: 9,

//    }).then((res) => {

//     console.log('resresres', res);

//    });

//    console.log('00000000000000', selectedRowKeys)

//   }

//  }



//  const rowSelection = {

//   renderCell: (checked, record, index, node) => {

//    return node;

//   },

//   checkAllPosition: 'top',

//   onSelectAll:onSelectAll,

//   selectedRowKeys,

//   selections: [

//    {

//     key: 'all-data',

//     text: '选择所有页数据',

//     onSelect: () => {



//     },

//    },

//   ],

//   onChange: onSelectChange ,

//  };



//  return (

//   <Table

//    rowSelection={rowSelection}

//    columns={columns}

//    dataSource={dataSource}

//    rowKey={record => record.tableName}

//   />

//  )

// }





// export default Table_left





import React from 'react';

import { Button, Modal, Table } from 'dtd';

import { Col, Form, Row, Select, Input } from 'dtd';

import PageTitleHeader from '@/components/PageTitleHeader';



import { useAntdTable } from 'ahooks';

import { PaginatedParams } from 'ahooks/lib/useAntdTable';

import { runInContext } from 'lodash';



const treeData=[];





const treeDataaaa = [

];

for (let i = 0; i < 5; i++) {

 treeDataaaa.push({

  key: i,

  tableName: `Edward King ${i}`,

  tableDesc: `London, Park Lane no. ${i}`,

 });

}

//这是为左侧表格添加数据



class Table_left extends React.Component {





 



 state = {

  selectedRowKeys: [], // Check here to configure the default column

  loading: false,

 };



 start = () => {

  this.setState({ loading: true });

  // ajax request after empty completing

  setTimeout(() => {

   this.setState({

​    selectedRowKeys: [],

​    loading: false,

   });

  }, 1000);

 };





 onSelectChange = selectedRowKeys => {

  console.log('selectedRowKeys changed: ', selectedRowKeys);

  const { onDataSelect, runGetField } = this.props;

  onDataSelect();

  this.setState({ selectedRowKeys });

  runGetField({

   page:1,

   pageSize:10,

   tableNames:selectedRowKeys

  }

   );



 };



 render() {



  const col_li = this.props.columns

  const treeData = this.props.dataSource

  const { selectedRowKeys } = this.state;

  const rowSelection = {

   renderCell: (checked, record, index, node) => {

​    return node;

   },

   // checkAllPosition: 'both',

   selectedRowKeys,

   onChange: this.onSelectChange,

   selections: [

​    {

​     key: 'all-data',

​     text: '选择所有页数据',

​     onSelect: () => {

​      const allRowKeys = treeData.map(({ tableName }) => tableName);

​      this.setState({

​       selectedRowKeys: allRowKeys,

​      });

​     },

​    },

   ],

  };



  return <Table

   rowSelection={rowSelection}

   columns={col_li}

   dataSource={treeData}

   rowKey={record => record.tableName}

  />;

 }


}


export default Table_left



```







# My study 

##  koa



![image-20220326145718632](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220326145718632.png)




![image-20220326145308178](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220326145308178.png)

![image-20220326145624419](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220326145624419.png)

![image-20220326154109325](https://gitee.com/chenweigen13/photo/raw/master/img/image-20220326154109325.png)







# week 6 

## day 1 328

![image-20220328131811159](../AppData/Roaming/Typora/typora-user-images/image-20220328131811159.png)

重新走ssh

![image-20220328134248609](../AppData/Roaming/Typora/typora-user-images/image-20220328134248609.png)





![image-20220328134607784](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220328134607784.png)





<img src="../AppData/Roaming/Typora/typora-user-images/image-20220328134813822.png" alt="image-20220328134813822" style="zoom:150%;" />

![image-20220328150331272](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220328150331272.png)

![image-20220328152356731](../AppData/Roaming/Typora/typora-user-images/image-20220328152356731.png)



![image-20220328153935376](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220328153935376.png)



卡再这咋办呢

无语了

![image-20220328162244798](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220328162244798.png)



## day 2





1. 下次提前组长或产品经理或是组内交接人商量好每一个功能节点的初始化界面。对于默认项不能以不了了之的态度对待。

2. 开发时代入产品使用者的视角，切换思想，对产品进行自我评估。提出自己对产品功能不适合处的建议，以及产品优化性能级使用体验的方法。

3. 开发完成后需要清空思路，再次以使用者的心态自我测试代码的质量和效果，避免出现“灯下黑”的情况。

4. 在对待使用新组件时，先仔细浏览相关文档，而不是拿着一个可以用的代码就用，对模板代码应该有自己的想法。要有我来运用代码的想法而不是根据模板更改代码。

5. 提示可以让用户的使用体验提升，这点应作为自己以后开发的一个小规则。提示也能够让程序员能够在平时及时的发现错误从而进行更正，而不是需要打开源码进行调试。

   

1. 下次提前组长或产品经理或是组内交接人商量好每一个功能节点的初始化界面。对于默认项不能以不了了之的态度对待。
2. 开发时代入产品使用者的视角，切换思想，对产品进行自我评估。提出自己对产品功能不适合处的建议，以及产品优化性能级使用体验的方法。
3. 开发完成后需要清空思路，再次以使用者的心态自我测试代码的质量和效果，避免出现“灯下黑”的情况。
4. 对于可以更改数量级别或者是其他的字符变量，都应该考虑初始化以及使用的问题，即不能只考虑使用而不考虑归原。



1. 第一次接触前后端对接业务，在业务上不熟练的地方没有其他的办法，只有多练多思考，多问导师和其他的同事。
2. 在使用组件的时候，应该更具“功能”决定组件，而不是根据”组件“来修改到符合功能的地步
3. 对于现成组件不能解决功能需求的问题，我不应该放弃修改代码，更不能放弃该功能需求。对组件的不熟悉是部分原因，更重要的是思维不能拘泥于组件。
4. 完成功能需求的方法有很多，不一定吊死在一个组件上。
5. 有时候自己最初的笨笨的想法其实是能行的通的，重要的是耐心。



1. 因为是第一次和后端对接业务，能力比较差，没有提前想到提交参数的字符串应该处理。
2. 在处理字符串的时候应该和后端商量好，因为这不是一定要前端或者后端做的事情，所以对于这种都能做的事情更应该积极沟通，努力协商，不能最后变成两边都不做了
3. 自己在进行测试的时候测试用例的范围应该更广。测试用例固然该符合逻辑思维，显示情况，但是我们不能保证误触或者特殊情况一定不会发生，所以自己在测试的不仅要对中英文进行处理，还要对？《%等特殊符号进行测试
4. 对于后端的知识应该多学习多交流多沟通，不应该局限在拿到数据就干活，丢回数据的想法中。更应该主动的去了解整个数据流程。



开始托福口语 

啧



![image-20220329165540292](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220329165540292.png)





一个还是两个

两个 语速一定要适当提升

==我还差得远==

## 330 day 3

改完了进度条正常显示

但是现在有新项目了

是一个聊天框   加紧时间完成计赛



---

in the most time, what we have seen is much more. 

Here, what is the difference between socialism and capitalism. 

why we are proud of the nation but have no hope for the future. 

Should I go abroad for being a graduate?

what the kind of work should be my career 

what is my dream 

新的任务

![image-20220330161903460](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220330161903460.png)



![image-20220330162105564](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220330162105564.png)



![image-20220330170224117](../AppData/Roaming/Typora/typora-user-images/image-20220330170224117.png)





开始调样式



```

{
  "compilerOptions": {
    "emitDecoratorMetadata": true,
    "experimentalDecorators": true,
    "baseUrl": ".",
    "paths": {
      "@/*": ["./src/*"]
    }
  }
}



```



```
import React from 'react';
import PageHeaderWrapper from '@/components/PageHeaderWrapper';
import { Popover, Button } from 'dtd';
import './index.css';

import {
  HomeOutlined,
  SettingFilled,
  SmileOutlined,
  SyncOutlined,
  LoadingOutlined,
} from '@dtfe/icons';

const oval = {
  width: " 36px",
  height: "126px",
  // borderRadius: "90%/50%",
  backgroundColor: "white",
  borderRadius: "18px",
  boxShadow: " 0 2px 4px 0",
  display: "block",
  // marginLeft: "1388px",
  // marginTop: "645px",
   marginLeft: "200px",
  marginTop: "200px",
}
const icon = {

}
// 欢迎咨询
const textStyle = {
  borderColor: "black",
  width: " 14px",
  paddingTop: "32px",
  paddingLeft: "11px"
}


const text = <div
  style={{
    fontFamily: "MicrosoftYaHei",
    fontSize: '14px',
    color: "#307BFF",
    lineHeight: "20px",
    fontWeight: "400",
    width: "205px",
    height: "71px",
    paddingTop: "10px",
    paddingLeft: "16.49px",
    paddingRight: "20.51px",
  }
  } > 应急业务助手
  < div style={{
    fontFamily: "MicrosoftYaHei",
    fontSize: "12px",
    color: "#999999",
    fontWeight: "400",
    paddingTop: "5px",

  }}> 智能定位，快速锁定应急业务
  </div >
</div >





let titleStyle = {
  fontFamily: "MicrosoftYaHei",
  fontSize: '14px',
  color: "#307BFF",
  backgroundColor: "red",
  lineHeight: "20px",
  fontWeight: "400",
  width: "205px",
  height: "71px",
  paddingTop: "10px",
  paddingLeft: "16.49px",
  paddingRight: "20.51px",
}



const Welcome: React.FC<{}> = () => {

  const Blue = () => {
    console.log('hihihi')
  }
  const content = (
    <div>

      <a style={titleStyle} onMouseEnter={Blue}  >  平台使用助理 </a>
      {/* <p>在线解答，快速解决使用问题</p> */}
      < div style={{
        fontFamily: "MicrosoftYaHei",
        fontSize: "12px",
        color: "#999999",
        fontWeight: "400",
        paddingTop: "5px",

      }}> 在线解答，快速解决使用问题
      </div >
    </div>
  );


  return (

    <>
      <div className="pro bg-red"
        style={oval}
      >
        <Popover placement="leftTop" title={text} content={content} trigger="click">
          {/* <HomeOutlined /> */}
          <div className='icon' style={icon}> </div>

          <div className='text' style={textStyle}>   欢迎咨询</div>
        </Popover>



      </div>


    </>
  );

};

export default Welcome;


```



完成任务

现在要整理代码？

明早上来吧要不然看起来我又没事情



## day 4 

1. 完成任务
2. https://github.com/pazguille/horwheel
3. 英语作文一篇
4. 基础知识：布局 class和className

6. 开始研究demo 

![image-20220331094215999](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220331094215999.png)

### cdn

![image-20220327161227781](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220327161227781.png)

大家可能觉得，这个不就是“镜像服务器”嘛？其实不一样。镜像服务器是源内容服务器的完整复制。而CDN，是部分内容的缓存，智能程度更高。

5. http https



![image-20220331130656064](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220331130656064.png)

https://www.cnblogs.com/ostrich-sunshine/p/12397133.html

![image-20220331140038958](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220331140038958.png)

![image-20220331145405838](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220331145405838.png)

使用 flex布局  align-item end



然后看了看力扣刷题 以及 考研的问题

咱不说其他的 对自己狠一些 ==完成自己设定的任务==

就这都很难了

c语言走第一轮刷题 python第二轮

## day 5 

![image-20220401091529250](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220401091529250.png)

## day 6 

canvas

![image-20220402092627515](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220402092627515.png)

![image-20220402093145449](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220402093145449.png)

![image-20220402095710635](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220402095710635.png)

再看promise

![image-20220402100122898](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220402100122898.png)





得出结论 

canvas上加文字 

难上加难

![image-20220402110208596](../AppData/Roaming/Typora/typora-user-images/image-20220402110208596.png)

![image-20220402110548600](../AppData/Roaming/Typora/typora-user-images/image-20220402110548600.png)

















## 413 day 3

Delete/Insert `␍`eslint(prettier/prettier)错误



![image-20220413164443325](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413164443325.png)

![image-20220413170337962](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413170337962.png)

preventDefault()



![image-20220413185156742](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413185156742.png)

![image-20220413185640053](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413185640053.png)

![image-20220413190047447](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413190047447.png)

展开语法

这个prev是什么

![image-20220413192611230](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413192611230.png)

```
inputRef.current.innerText = '123';
inputRef.current.innerHTML = '345';
```







![image-20220413193155404](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220413193155404.png)











## 414 

看rendermsg怎么弄的

D:\myproject\InsightConfig-master\InsightConfig-master\src\pages\robot\manage

![image-20220414143240324](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414143240324.png)

```
1.全面深化改革取得重大突破，全面依法治国取得重大进展，全面从严治党取得重大成果，国家治理体系和治理能力现代化加快推进，中国共产党领导和我国社会主义制度优势进一步彰显；
2.经济实力、科技实力、综合国力跃上新的大台阶，经济运行总体平稳，经济结构持续优化；
3.脱贫攻坚成果举世瞩目，五千五百七十五万农村贫困人口实现脱贫；
4.粮食年产量连续五年稳定在一万三千亿斤以上；
5.污染防治力度加大，生态环境明显改善；
6.对外开放持续扩大，共建“一带一路”成果丰硕；
7.人民生活水平显著提高，高等教育进入普及化阶段，城镇新增就业超过六千万人，建成世界上规模最大的社会保障体系，基本医疗保险覆盖超过十三亿人，基本养老保险覆盖近十亿人，新冠肺炎疫情防控取得重大战略成果；
8.文化事业和文化产业繁荣发展；
9.国防和军队建设水平大幅提升，军队组织形态实现重大变革；
10.国家安全全面加强，社会保持和谐稳定。

```

![image-20220414190809689](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414190809689.png)

![image-20220414191130839](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414191130839.png)

为什么所有事件都是4呢

![image-20220414192623957](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414192623957.png)

总而言之，就是菜

![image-20220414193212855](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414193212855.png)

## 415

https://www.runoob.com/js/js-async.html

学习异步

==document就找不到==？

![image-20220414194838902](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414194838902.png)

https://www.cnblogs.com/liugang-vip/p/5616484.html

```js
for (var i = 0; i < 5; i++) {
            //创建小圆
            var circle = document.createElement('div');
            circle.innerHTML = dataTxt[i]
            // 下面的4个变量 代表小圆随机位置  和 随机持续时间和延迟
            var bottom = randomNum(10, 1000);
            var left = randomNum(-200, 200);
            var duration = randomNum(10, 30) / 1;
            var delay = randomNum(0, 50) / 10;
            //  animation:move ${duration}s linear ${delay}s infinite;
            //给生成的每个小圆 加上动画和位置属性
            if (i % 2) {
                console.log('i%1', i);
                circle.id = i;
                circle.style.cssText += `
            animation:move2 ${duration}s linear ${delay}s infinite;
            animation-fill-mode: forwards;
            bottom:${bottom}px;
            cursor:default;
            left:${left}px;
            display:flex;
            `;
            } else {
                circle.id = i;
                console.log('2 i%1', i);
                circle.style.cssText += `
            animation:move1 ${duration}s linear ${delay}s infinite ; 
            animation-fill-mode: forwards;
            bottom:${bottom}px;
            cursor:default;
            left:${left}px;
            display:flex;
            `;

            }
            console.log('in the loop i ',i)

            circle.className += " dot";
            console.log('CIRCLE', i, circle)
            //把每个小圆 都加入这个div
            circleBox.appendChild(circle);
          
        };
        console.log('AAAAA', circleBox);
        divList=circleBox.querySelectorAll(".dot")


        console.log('divlist',divList)
```

![image-20220414205517468](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220414205517468.png)





![image-20220415103942912](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220415103942912.png)

<img src="https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220420152007465.png" alt="image-20220420152007465" style="zoom:200%;" />

https://www.cnblogs.com/echolun/p/11544045.html

the action of business man will have some negative impact on the sale,

while the quality of the products is the core part of the whole business

![image-20220421105051906](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220421105051906.png)

![image-20220421105144853](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220421105144853.png)

![image-20220421175117954](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220421175117954.png)

![image-20220421175302899](../AppData/Roaming/Typora/typora-user-images/image-20220421175302899.png)

![image-20220421175925003](../AppData/Roaming/Typora/typora-user-images/image-20220421175925003.png)







![image-20220421180108344](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220421180108344.png)

![image-20220421180232876](https://raw.githubusercontent.com/RNCHEN/photo-326/master/blogImg/image-20220421180232876.png)



![image-20220421181110613](../AppData/Roaming/Typora/typora-user-images/image-20220421181110613.png)

上传图床遇到如此愚蠢的问题该怎么办

