# 基于 hexo 的博客主题更换

### 更换主题

要换主题，所以我们得下载 主题 

我这里用的是 yilia 主题

通过git方式，命令行clone来的。


    git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia
    
主题弄完后，接下来只需要去修改下配置文件

_config.yml

    theme: yilia
    
注意：冒号后面必须接一个空格，不然会报错。

好的，这样将博客 重新部署到github 上，访问就可以看到主题已经更改了。

其他，主题类似操作。