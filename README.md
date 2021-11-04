![](https://img-blog.csdnimg.cn/20211014155507732.png)
# Lua_game_scripts

## 1.项目简介

使用触动精灵工具编写的游戏王自动匹配脚本，自动登录，全自动匹配，出牌，实现增长人物经验。

## 2.环境简介

语言：lua

开发工具：触动精灵

## 3.项目截图

无

## 4.开发流程与代码逻辑简述

1. 根据触动精灵官网文章搭建所需开发环境
2. 启动触动精灵程序，启动游戏
3. 通过触动精灵的比色函数，判断当前是哪个游戏画面
4. 根据不同的游戏画面，执行不同的操作，比较常见的操作为滑动和点击，触动精灵均提供了函数。
5. 重复步骤3，4即可实现复杂逻辑的处理，初比色函数外，还有识图，识字等功能。

## 5.技术准备

- [lua基础语法](https://www.runoob.com/manual/lua53doc/contents.html)
- [按键精灵官网文档](https://www.touchsprite.com/developer)
- 其他开发者分享的教学视频，用以学习完整的游戏脚本开发思路与搭建开发环境。

## 6.总结

上一次玩手机游戏已经是六个月前了，玩着玩着突然发现有很多重复的步骤，就想弄一个脚本自动挂机。虽然没有游戏脚本开发的相关经验，不过凭借着极大的兴趣，这几乎是工作这两年来最刻苦的日子，只要能摸到电脑，就在学习，编写和完善脚本的路上。到后面游戏成了检验脚本成功率，测试脚本的工具，游戏本身已经丝毫没有吸引力了。可能是太累了吧，现在对手机游戏都没有什么兴趣了。不过成就感是很大的，自己所学真真切切的改善了自己的生活。

简单描述一下学习过程，给对游戏脚本感兴趣的同学一点帮助。首先讲一下工具的比色原理，就是实时的将手机屏幕截图保存，开发者指定像素点，传入色值，工具把开发者传入的色值和截图上的色值进行比较，将比较结果返回。最开始学习的话是技术选择，能做同样事情的工具有很多，选择了触动精灵是因为对lua语言比较感兴趣，触动精灵的文档确实写的很详细，是一个不错的选择，这类公司主要通过脚本APP分发限制来进行赚钱，有机会的话会支持一下。选定技术之后就去B站上搜索了相关视频，视频难免会有些过时，一定要结合官方文档，学习其他计算机技术也一样。然后就是根据自己的游戏场景编写脚本代码。

值得一提的是通过这次写脚本的过程，自己对面向对象有了更深刻的认识。在开发脚本的后期，主要是对脚本的代码结构做优化，让代码更加清晰易读，lua是面向过程的语言，在最后的代码结构优化过程中，发现面向对象就是最好的优化，代码更加的清晰易读，使用lua中的`Table`，实现了面向对象的类，属性，方法，继承，封装等特性。不过随着对游戏逐渐失去兴趣，脚本的功能也没有进一步的丰富，不过最核心的功能还是有的。

![](https://img-blog.csdnimg.cn/c66cc07b674c424ba11ec6825e22a640.png)

![](https://img-blog.csdnimg.cn/46f9ed15f914479ab130d47e9578e721.png)
