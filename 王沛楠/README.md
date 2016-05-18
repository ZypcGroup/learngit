# 说说自己初次学习git时遇到的问题
* 没有搞清楚git 与 github 的关系.
* 在git 申请ssh-key的时候细节问题
* 如何与ZypcGroup链接并clone 时错误提示：fatal: remote origin already exists.
***
以下是我遇到的三个问题的解决方案：
1. *  Git是一款免费、开源的分布式版本**控制系统**，用于敏捷高效地处理任何或小或大的项目。
  * GitHub是一个可以提供Git仓库托管服务的网站，所以，只要注册一个GitHub账号，就可以免费获得Git远程仓库。
2. * 在申请SSH-key的时候，作为一个新手，不要手贱去输入任何信息你一位理所当然的信息，直接敲回车就好了，git会自动在你的用户目录下创建一个.ssh文件夹。里面存放的两个文件一个是 id_rsa. 一个是 id_rsa.pub.  （前者是你的私有密码，后者是公共密码）。在github添加ssh协议的时候用到的是id_rsa.pub.
3. * 如果你想从ZypcGroup上Clone文件时遇到了这个错误提示，你只需要把链接的地址从原来的改为ZypcGroup就行了。操作指令为 git remote add origin git@github.com:ZypcGroup/learngit.git (注：learngit是你从ZypcGroup上clone的库)。
4. * 附上错误提示的解决与简单git命令归纳的csdn地址。 [点击这里](http://blog.csdn.net/qyf_5445/article/details/8737913)

# 关于MarkDown 标记语言的学习
* MarkDown 真的很方便很好用！
   主要体现在 语法结构简单，简洁清晰，十分容易上手，不愧为**轻量级的标记语言**。
* 还要说一点，十分重要的一点！
# 阿修做的在线MarkDown编辑真的超好用！