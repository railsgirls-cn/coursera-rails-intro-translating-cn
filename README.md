《Ruby on Rails: An Introduction by Johns Hopkins University》in Chinese
=============================================


## 目的

> 旨在通过翻译技术文章学习编程，通过翻译协作认识朋友。


## 翻译哪些内容

1. 跟 RG 相关的
2. 跟 Ruby 相关的
3. 跟 Rails 相关的
4. 跟 Women in Tech相关的

## 参与流程

1. 联系翻译小组管理员 文洋，加入翻译小组。
2. 认领任务在规定日期内完成。
3. 使用 github 作为翻译工具。 Why Github? 给大家看一篇北京教练[翟英昌](http://weibo.com/u/2682424731?topnav=1&amp;wvr=5&amp;topsug=1)的文章[『协同写作的力量——中国开发者 9 天完成《Swift 语言》中文版』](http://36kr.com/p/212811.html?vt=0)
4. 校对

**如果想帮忙翻译或者校对，请联系「翻译小组」管理员文洋[@sundevilyang](https://github.com/sundevilyang)：[ywen8@asu.edu](mailto:ywen8@asu.edu)，谢谢！**



# 译者记录
1.  Week 1 
	- Welcome to Ruby on Rails An Introduction
		- Course Introduction
	- Installing Software
		- Setting Up the Development Environment
2. Week 2
	- Getting to Know Ruby
		- 0 Introduction to Ruby
		- 1 Ruby Basics by [@runajiang](https://github.com/runajiang)
		- 2 Flow of Control [@runajiang](https://github.com/runajiang)
		- 3 Functions [@runajiang](https://github.com/runajiang)
		- 4 Blocks [@runajiang](https://github.com/runajiang)
		- 5 Files [@runajiang](https://github.com/runajiang)
	- Collectios and String APIs
3. Week 3


# 贡献力量

如果想做出贡献的话，你可以：

- 帮忙校对，挑错别字、病句等等
- 提出修改建议
- 提出术语翻译建议

# 翻译建议

如果你愿意一起校对的话，请仔细阅读：

- fork过去之后新建一个分支进行翻译，完成后pull request这个分支，没问题的话我会合并到master分支中
- 翻译后的文档请放到source文件夹下的对应章节中，然后pull request即可
- 有其他任何问题都欢迎发issue，我看到了会尽快回复

谢谢！

# 关于术语

翻译术语的时候请参考这个流程：

- 尽量保证和已翻译的内容一致
- 尽量先搜索，一般来说编程语言的大部分术语是一样的，可以参考[微软官方术语搜索](http://www.microsoft.com/Language/zh-cn/Search.aspx)
- 如果以上两条都没有找到合适的结果，请自己决定一个合适的翻译或者直接使用英文原文，后期校对的时候会进行统一

## 使用 github 翻译操作流程



# 参考流程

有些朋友可能不太清楚如何帮忙翻译，我这里写一个简单的流程，大家可以参考一下：

1. 首先 fork [项目](https://github.com/railsgirls-cn/coursera-rails-intro-translating-cn) 
2. 把 fork 过去的项目也就是你的项目 clone 到你的本地
3. 在命令行运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/railsgirls-cn/coursera-rails-intro-translating-cn` 项目的库添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream master` 拉取我的库的更新到本地
8. 运行 `git rebase upstream/master` 将我的更新合并到你的分支

这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。

如果修改过程中我的库有了更新，请重复6、7、8步。

修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 `pull request` 按钮，点击它，填写一些说明信息，然后提交即可。





