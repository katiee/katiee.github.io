---
layout: post
category : tech
tags : [git, summary]
title: Git简要操作
---

* 创建新的git仓库
	git init

* 仓库克隆
	git clone /path/to/repository		# 本地仓库克隆
	git clone git@github.com:katiee/test.git		# 远程仓库克隆

* 连接远程仓库
	git remote add origin git@github.com:katiee/test.git 		# 增加仓库连接
	git remote rm origin		# 删除仓库连接

* 显示仓库状态
	git remote		# 显示当前仓库连接 origin
	git remote show origin		# 显示origin状态

* 添加与提交
	git add .		# 将本地修改提交到缓存区
	git commit -m "提交备注信息"		# 提交代码

* 推送
	git push -u origin master		# 将本地改动提交远程仓库

* 抓取
	git pull --all --tag		# 抓取远程更新 pull = fetch + merge

