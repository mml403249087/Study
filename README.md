# Study
<pre>
1.记录每天学习的内容，归纳总结
2.第一次更新Git仓库方法：
  创建Git仓库->git init
  把本地代码或文件更新到本地仓库中->git add .->git commit
  添加本地仓库到GitHub上->git remote add study https://github.com/mml403249087/Study.git (更新网址在每个项目中的clone安定download中)
3.在第二次更新仓库的时候遇到问题，git push study master命令没有反应。没有任何文件更新到GitHub上。
  原因是：我在commit的时候并没有成功，因为输入命令git commit的时候出来需要写入commit注释，但这里我直接:q退出，导致出现错误：Aborting commit due to empty commit message. 没有看到，输入注释之后成功上传文件到GitHub。
</pre>
