## 快速开始
## 安装APP

1.进入Inkstone示例网站后， 会弹出提示如图，按照指示下载这个app

<img src="/images/guide.png" alt="安装指引图" width="400" height="500">

2.然后打开GitHub，随便找到一个你的公开(public)的项目进入点击setting，让找到GitHub Apps,点击后出现这个页面则表示InKstone 下载完成 

<img src="/images/IGA.png" alt="安装指引图2" width="600" height="200">

3.然后点击Configure，点击Save

<img src="/images/CS.png" alt="安装指引图3" width="516" height="400">

## 授权登录
1.登录页面分为两个，一个直接登录，一个GitHub登录，直接登录的方式，点击跳过就行，跳过后只能使用编辑器的基础功能，比如在本地创建一个文件等，一般都是推荐GitHub登录。当你没点跳过登录的话，正常刷新页面都可以自动延续之前的登录状态，本软件也会自动存储token，刷新后，不小心退出，点击登录会直接自动登录。


2.现在就可以随时随地的在[Inkstone](https://hugo-editor.1think2program.cn/main)中修改你的md文件或者修改博客。
进入这个网站后，先打开梯子，因为要GitHub授权登录，然后选择选择你要编辑的项目,然后选择你要编辑的分支。

<img src="/images/CYP2.png" alt="授权登录" width="516" height="400">

## 基本操作

1.进入后，点击资源管理器，在这里有三种模式，混合，本地，和远程(GitHub那边)，我们编辑文件就是进入混合模式，最右边有个GitHub的图标，点击后会下载到本地，这个本地文件你不主动删除一直都在，然后远程模式目前只是只读文件名(后期会修改，只读文件的整个内容，然后就可以对比你修改了哪里)。
在混合模式修改完内容后，得主动保存，ctrl+s 或者点击编辑框上面的工具栏。

<img width="194" alt="image" src="https://github.com/user-attachments/assets/2e81938c-19bf-48b9-8dcb-265df6bde628" />

这样即为成功。

2.编辑前的GitHub中的REAMDE.md文件，我打算在Inkstone中删除下面的日期

<img src="/images/EG.png" alt="授权登录" width="616" height="500">



3.这是Inkstone 中的REAMDE.md文件 

<img src="/images/INKEG.png"  width="616" height="500">

4.我们删除下面的日期，然后保存，然后点击提交。如图

<img src="/images/PUSH.png"  width="316" height="500">

5.点击后，就可以看到本次更改了哪些文件，如果你更新了多个文件，在这里也可以选择只提交一个特有的文件，不要想的文件可以放弃更改。

<img src="/images/PD.png"  width="316" height="500">

6.现在我们提交上去，记得打开VPN然后在提交，不然会出现404或者502等等的问题，会出现一直转圈的情况。
提交成功后会出现 commit success的小弹窗，或者打开开发者工具，查看console日志,看到README.md UPDATE后，则表示提交成功。

<img src="/images/SP.png"  width="516" height="400">

7.出现这种的 则表示README.md文件更新成功。我们现在刷新一下GitHub查看一下是否修改成功。

<img src="/images/RESULT.png"  width="616" height="500">

可以看到已经成功在远程的GitHub里面删除了下面的一行日期。

