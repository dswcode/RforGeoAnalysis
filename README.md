# RforGeoAnalysis

### 说明

本库是个人实验代码合集，目前主要用于测试同步，代码临时存储。

### Git 指令

git commit 是"记录对存储库的更改"，是将本地修改过的文件提交到本地库中； 而git push是"更新远程引用和相关对象"，是将本地库中的最新信息发送给远程库。

因此，git commit用于连接本地存储库，操作的是本地库； 而git push用于与远程存储库交互，操作的是远程库。

### Rstudio中代码与Github.com同步

在Rstudio中，想要从本地库main上传至远程库 （Github.com上的main）需要：

1.  先点击Source pane 保存按钮，然后就可以在右侧Git pane看见提示（会显示M，说明该文档有了新的改动）。
2.  在右侧Git pane勾选当前文档前的勾选框，然后点击Commit按钮，将更新提交至本地库main上
3.  
