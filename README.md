# Greenautumn

 一个简洁的[hexo]主题，模仿[思否](https://segmentfault.com/) .

- [效果预览](https://qiuchi.me/)
- [详细文档](https://qiuchi.me/wiki)

## 配置和安装

### 安装
进入博客根目录，执行
``` bash
$ git clone https://github.com/huoher/hexo-theme-greenautumn.git themes/greenautumn
```

**Jians 需要 Hexo 2.4或更高版本** 如果你需要开启 RSS,你还将需要安装插件 [hexo-generator-feed](https://github.com/hexojs/hexo-generator-feed) .

### 启用主题

将你的主题配置文件  `_config.yml` 中`theme`一项修改为 `greenautunm`.

### 更新主题

``` bash
cd themes/greenautunm
git pull
```

## 其他配置
主题目录`/theme/jians/_config.yml`文件
下列内容与样板保持一致，请自行修改，有更多需要请查询[详细文档](https://qiuchi.me/wiki)
``` yml
site:
  description: 前事不忘后事之师
menu:
  Home: /
  Archives: /archives/
  Github: https://github.com/huoher
footermenus:
  Home: /
  Archives: /archives
  About: /about/
copyright:
  is: false
  icp: 沪ICP备00000001号
  anbei: 浙公网安备 33010602002000号
  anu: 所有权利保留 转载请联系作者
  author: Huoher. Inc

banner:
  title: 在 SegmentFault，学习技能、解决问题
  content: 每个月，我们帮助 1000 万的开发者解决各种各样的技术问题。并助力他们在技术能力、职业生涯、影响力上获得提升。

announcement:
  content: 祝各位社区开发者 2019 春节快乐！一起来聊聊你的春节都怎么过？
  url: /about
```


## 依赖

### 版本最低要求

- [Hexo] 2.6+
- [Node.js] 8.0+



### 授权
[MIT License](https://opensource.org/licenses/MIT)

请自觉遵守开源协议，共同营造良好社区氛围

## 鸣谢
本主题离不开下列开源项目的无私开源
- [Hexo]
- [hexo-generate-feed]
- [Node.js]
- [Ejs]
- [Highlight.js]

[Hexo]: https://hexo.io/
[Font Awesome]: http://fontawesome.io/
[Highlight.js]: https://highlightjs.org/
[Node.js]: https://nodejs.org/
[hexo-generate-feed]: https://github.com/hexojs/hexo-generator-feed
[Ejs]: https://github.com/tj/ejs.git
