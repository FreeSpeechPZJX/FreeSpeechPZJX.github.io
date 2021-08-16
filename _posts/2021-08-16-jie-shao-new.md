---
layout: post
title:  新的介绍
date:   2021-08-16
categories: sticky
tags: 介绍
description: 介绍网站
is_sticky: true
---
## 请注意
本介绍文档是对[上一篇](https://freespeechpzjx.github.io/sticky/2021/07/10/jie-shao.html)介绍文档的补充。 请务必在查看文档前阅读[上一篇](https://freespeechpzjx.github.io/sticky/2021/07/10/jie-shao.html)介绍文档。 2021年8月16日之后，新的提交方式将与[上一篇](https://freespeechpzjx.github.io/sticky/2021/07/10/jie-shao.html)介绍文档同时推出 . 当然，新方法更适合有一定动手能力的人。
## 投稿道路的补充
第一条声明：这个言论自由平台完全借鉴了[端点星计划](https://github.com/Terminus2049)，这个想法几乎来源于[这个](https://telegra.ph/%E6%88%90%E9%83%BD%E5%98%89%E7%A5%A5%E4%BA%8C%E4%B8%89%E4%BA%8B-09-12)文章。
在这里解释新方法：
### 需要的基本技能

- 熟悉使用 Markdown 基本标记语法
- 熟悉 Markdown 文本编辑器（可选项）：这些工具适用于对 Markdown 语法不熟悉的协作者
  - [MarkdownPad](http://markdownpad.com/)
  - [Atom](https://atom.io/)
  - html 转成 markdown：浏览器插件「[简悦](http://ksria.com/simpread/)」
- 熟悉 GitHub 平台使用

### PR 步骤说明

1. 注册并登录 [GitHub](https://github.com/) 帐号

2. fork FreeSpeechPZJX 仓库到自己的 GitHub: 访问[FreeSpeechPZJX](https://github.com/FreeSpeechPZJX/FreeSpeechPZJX.github.io) GitHub页面，点击右上角 **Fork** 按钮。

3. 编辑文章：在自己帐号里面的 FreeSpeechPZJX.github.io 仓库，编辑添加文章。

    - 第一种方式：直接在线编辑添加
      1. 点击进入 `_posts/` 文件夹，点击上面的 **Create New File**
      2. 命名文章标题：统一格式为「Year-Month-Day-title.md」，例如 `2018-01-01-biao-ti.md`
      3. 在下方 **Edit new file** 空白区域编辑内容，编辑格式看下方[格式编辑要求](#格式编辑要求)
      4. 点击 **Preview** 可预览效果
        ![add_new_post.PNG](https://i.loli.net/2021/08/16/G8wgkJAsUelHfvS.png)

    - 第二种方式：从本地上传已编辑的 md 文档
      1. 点击进入 `_posts/` 文件夹，点击 **Upload files**
        ![drag_files.PNG](https://i.loli.net/2021/08/16/gkFQNoH48vfCwY6.png)
      2. 从本地选择要上传的 md 文档

4. 填写 **commit changes**
  ![commit_changes.PNG](https://i.loli.net/2021/08/16/AcxU29FzjwP4XTZ.png)

5. 向原仓库提交 PR
    
    在自己的仓库页面，点击 **new pull request**，再点击 **create pull request**，填写 PR 描述并提交。
    ![create_pull_request.PNG](https://i.loli.net/2021/08/16/a5XGYHhKjy2egIs.png)
    （上图中单击 **Create pull request**，会出现下图的情况）
    ![create_pull_request1.PNG](https://i.loli.net/2021/08/16/9RY8sFVKPJ1zXSu.png)

6. 等待 Zhang Feng 查看 PR ，符合要求的内容会 merge(合并）。

### 格式编辑要求

1. 头部格式：

    ```
    ---
	layout: post
	title:  知乎回答备份2021.7.15
	date:   2021-07-15
	categories: 存档备份
	tags: 知乎
	description: 知乎回答备份
	is_sticky: false
	---
	```
	 
    - layout: post 保持不变
    - title: 随意取一个标题+日期（格式如上）
    - date: 与标题的日期保持一致，但是请注意格式不同
    - categories: 个人文章就填写“言论自由” 备份他人文章就填写“存档备份”
    - tags: 标签（在FreeSpeechPZJX查看是否已有相关标签）
    - image_feature: "如果文章有合适的图片可作为封面图，图片链接填在这里，若无则不填写"
    - description: 可用文章的导语做简述
    - is_sticky: false 保持不变（除非十分重要请填写true）

2. 图片编辑

	- 使用 [https://sm.ms](https://sm.ms) 或 [https://imgur.com](https://imgur.com) 图床平台生成链接。
	- 图注用 `<center>图注</center>` 居中。