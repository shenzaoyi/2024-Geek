# Git学习感想
>王若楠

> ## 目录

+ Git基本语言
+ 一个bug

## 基本操作

git的操作都是git+指令形式的，通过不同的指令可以完成创建，查看，添加等功能。

看教程的时候感觉这是一个简洁的工具，重用输入指令就可以完整任务，甚至与GitHub交互，特别方便。但当我去实践的时候，现实给了我一棒又一棒。

## 一个bug

尝试git最大的困难不是不理解，而是不断地排查，试错。

一开始，在我要把文件提交到本地库的时候，就失败了，显示出”nothing to commit...“的字样。于是，我开始了第一次排查。又进行了一轮add .、commit、push后，还是失败了。又在csdn上找说要看看有没有本地与远程的对应关系，想创建，它说已经存在了，想传递又说无法读取。就这两步我就反复试了好多次。求助亲友说不能用HTTP要用SSH,又开始研究怎么取消关联，再重来一遍。本来以为要大功告成，又告诉我什么连接超时，刷新几次都不管用，试了关闭VPN，试了重启，都没用。我已经失去所有力气和手段了，然后就抱着试试的心态把提示错因的那句话直接复制到csdn上，没想到还真查到了！但光是解决教程就看了两个，又东点西点研究半天，在.ssh里面输入一段神秘文字，好像是换了个端口，终于，解决了！

经历bug事件，我有开辟了一个新的解决问题的方法，就是直接把的提示错误的语句复制下来去查，万一有好结果呢。

感觉git是一个简单又复杂的工具，说它简单，是因为它的指令都很简洁；说它复杂，是因为它的每一个bug都能卡我很久，还是能力不够，仍需继续练习！
