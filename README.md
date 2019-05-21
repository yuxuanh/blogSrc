# blogSrc
- This is the src code for https://github.com/yuxuanh/yuxuanh.github.io
- link: https://yuxuanh.github.io/

```cmd
npm install
hexo g
hexo s

ps:
hexo s = hexo server
hexo g = hexo generate
hexo d = hexo deploy
hexo n = hexo new
```

## change theme
- 下载主题，将下载好的主题文件夹，粘贴到站点目录的themes下，eg: hexo-theme-matery
- 更改站点配置文件_config.yml 的theme字段，为主题文件夹的名称，eg: hexo-theme-matery
  
## problem fix
  如果一直no layout的错，基本99%是theme下面的主题文件夹名错了，跟_config.yml不一致，别问我为什么这么确定，因为我花了几个小时在查错，因为我是download zip，文件夹带branch名。。。。
  
## More
https://hexo.io/docs/

## New Post
-hexo new post "test"
-然后模范hello world来加标签和写文章
-图片放在/source/images下面，然后文章引用
```html
<img src="/images/tian_kong_zhi_cheng.jpg">
```
生成静态html和发布：hexo g -d

## Edit social icon in index page
edit themes/hexo-theme-matery/_config.yml socialLink  
and themes/hexo-theme-matery/layout/_partial/social-link.ejs  
https://github.com/blinkfox/hexo-theme-matery#modify-social-links
the icon is using http://www.fontawesome.com.cn/ v4.7, ctrl-F to find icon in http://www.fontawesome.com.cn/faicons/