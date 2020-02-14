# 配置本地Git库和远程Github库连接
由于Github 可以使用ssh(Secure Shell)加密方式进行的远程连接。

本地Git库和远程的github库，之间github需要配置本地库物理机的公钥 ，本地物理机具有特有的私钥。这样github就能根据公钥判断，推送的（push）人对不对。

所以，我们现在要先获得本地Git的公钥和私钥。
在cmd命令行窗口，输入以下命令。

    ssh-keygen -t rsa -C "youremail@example.com"
    
youremail@example.com
:   你自己的电子邮箱

然后，一路enter，最后打开你的系统盘，找到

`` 用户->你的计算机名->.ssh->id_rsa.pub
``
> .ssh
>> id_rsa  这个文件里面的就是你的私钥<br>
>> id_rsa.pub 这个就是公钥

打开公钥，复制内容，打开github，在

``setting->SSH and GPG keys ``

将内容沾到 ssh 框内，title 随意。