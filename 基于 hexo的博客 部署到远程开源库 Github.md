# 基于 hexo的博客 部署到远程开源库 Github

介绍： Github 开源社区具有 page 功能，给每一个用户提供了一个域名

那么，我们就可以将我们的个人博客，挂到 github的服务器上去，这样通过 github给的域名，白嫖~

get到重点了吗？ 

全程 免费 

---
### 开始接 基础篇

修改hexo框架博客的配置文件
    
    _config.yml
最尾部的

    deploy ：
        type: git
        repo: http://github/*****/***.git github仓库的链接
        branch: master

注意：冒号后面必须接一个空格，不然会报错。
然后，完了。




hexo g 

将hexo 变为 静态文件.html    对应的目录为 public 目录



hexo d



部署博客到github

如果出现下面的问题：ERROR Deployer not found: git

解决：
    
    npm install --save hexo-deployer-git

至此，可以使用域名 访问你的博客了。域名就是你的github那个仓库，

such: https://yourrepo.github.io



提醒：可能有个坑，前面的基础篇讲过 ，借用GitHub的page 功能完成的，因此 ，对应使用的仓库，

要将 setting 中的GitHub Pages    打开