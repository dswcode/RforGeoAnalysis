# RforGeoAnalysis

### 说明

本库是个人实验代码合集，目前主要用于测试同步，代码临时存储。

### Git 指令

git commit 是"记录对存储库的更改"，是将本地修改过的文件提交到本地库中； 而git push是"更新远程引用和相关对象"，是将本地库中的最新信息发送给远程库。

因此，git commit用于连接本地存储库，操作的是本地库； 而git push用于与远程存储库交互，操作的是远程库。

### Rstudio中代码与Github.com同步

在Rstudio中，想要从本地库main上传至远程库 （Github.com上的main）需要：

1.  先点击Source pane 保存按钮，然后就可以在右侧Git pane看见提示（会显示M，说明该文档有了新的改动）。
2.  在右侧Git pane勾选当前文档前的复选框，然后点击Commit按钮，将更新提交至本地库main上，这时会弹出新的对话框，需要在Commit message上写明文档变动摘要。
3.  输入完 message后，点击Commit，更新就会提交到当地库
4.  然后点击窗口右上角的Push，将被地库的更新推送至Remote main （github.com)。

### Reference

[Git hands-on session with RStudio](https://inbo.github.io/git-course/course_rstudio.html)
