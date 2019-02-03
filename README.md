# Jians

 一个简洁的[hexo]主题，模仿[简书网](https://www.jianshu.com/) .

- [效果预览](https://qiuchi.me/)
- [详细文档](https://qiuchi.me/wiki)

## 配置和安装

### 安装
进入博客根目录，执行
``` bash
$ git clone https://github.com/huoher/hexo-theme-jians.git themes/jians
```

**Jians 需要 Hexo 2.4或更高版本** 如果你需要开启 RSS,你还将需要安装插件 [hexo-generator-feed](https://github.com/hexojs/hexo-generator-feed) .

### 启用主题

将你的主题配置文件  `_config.yml` 中`theme`一项修改为 `Jians`.

### 更新主题

``` bash
cd themes/jians
git pull
```

## 其他配置
主题目录`/theme/jians/_config.yml`文件
下列内容与样板保持一致，请自行修改，有更多需要请查询[详细文档](https://qiuchi.me/wiki)
``` yml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Sidebar
sidebar: right
widgets:
- category
- tag
- tagcloud
- archives
- recent_posts

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID



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
- [Node.js]
- [Ejs]

[Hexo]: https://hexo.io/
[Fancybox]: http://fancyapps.com/fancybox/
[Font Awesome]: http://fontawesome.io/
[Grunt]: http://gruntjs.com/
[Node.js]: https://nodejs.org/
[hexo-generate-feed]: https://github.com/hexojs/hexo-generator-feed
[Ejs]: https://github.com/tj/ejs.git
"# hexo-theme-jians" 
"# hexo-theme-greenautumn" 
