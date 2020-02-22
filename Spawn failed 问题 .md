# 	Error: Spawn failed

``FATAL Something's wrong. Maybe you can find the solution here: https://hexo.io/docs/troubleshooting.html``

``Error: Spawn failed
    at ChildProcess.<anonymous> (D:\resp\blog\node_modules\hexo-util\lib\spawn.js:51:21)
    at ChildProcess.emit (events.js:321:20)
    at ChildProcess.cp.emit (D:\resp\blog\node_modules\cross-spawn\lib\enoent.js:34:29)
    at Process.ChildProcess._handle.onexit (internal/child_process.js:275:12)``



出现原因，远程库和当前库版本不一致。



**解决**：

修改hexo框架 .deploy_git文件夹下面的 .git 文件。

添加两行命令

	autocrlf = false
	safecrlf = false
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
	<font color="red" >autocrlf = false <br/>	safecrlf = false</font>

...

开始查了比较多的方案，这应该是最简单的方案了，果然是 no pains ,no gains。