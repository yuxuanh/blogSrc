# yuxuanh.github.io

```cmd
npm install hexo -g
hexo init
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