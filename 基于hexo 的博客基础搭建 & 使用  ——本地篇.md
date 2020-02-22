# hexo 本地使用
hexo 依赖npm & git。

在电脑上预先装上 node.js  和  git

### 一、node.js的安装

搜索node.js官网下载。

然后，安装node.js,输入以下命令，查看版本
    
    node -v

接下来，需要npm包管理

由于npm是国外的服务器下载速度较慢，因此，我们可以通过下载挂在淘宝下的npm镜像。

    npm instal -g cnpm --registry.npm.taobao.org
cnpm包管理安装完成后，输入

    cnpm install -g hexo 
安装 hexo 框架。

安装完成，可 ``hexo -v`` 查看hexo相关。

### 二、安装 git 

git 官网下载 git 安装程序。

下载较慢，请耐心等待
。

安装完成后。


那么，我们的hexo 框架的本地博客基本完成了。

### 三、hexo 的使用

hexo init <博客名>

进入到 博客名 下：

hexo new "文章"   也可以直接将文件放到 博客目录下面的source下面的_post目录中

生成：

hexo g   // 生成静态网页，生成的文件存放在 public目录中



在本地预览：

hexo s   // 访问 localhost:4000






​    
