# Awesome Git

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![jaywcjlove/sb](https://jaywcjlove.github.io/sb/lang/chinese.svg)](./README_zh-Hans.md)

收集一些有关 Git 的工具、资源清单列表。

## 加入我们
如果你有其他有趣的 Git 工具/项目/资源推荐，欢迎提交 Pull Request 请求到本仓库中。

## 目录
- [Awesome Git](#awesome-git)
	- [Tutorial](#教程)
  - [Client](#客户端)
  - [Repository Hosting](#第三方代码托管平台)
  - [Self-Hosted Repository](#自建代码托管平台)
  - [Workflow](#工作流)
  - [Hook management](#钩子管理策略)
  - [Tools](#工具)
  - [Extensions](#拓展)

## 教程
*畅游互联网，我们可以找到很多 Git 学习资料。*

* [Flight rules for Git](https://github.com/k88hudson/git-flight-rules) - 该教程在你遇到 Git 错误的时候有效地指导你。
* [Try Git](https://try.github.io/) - 利用 15 分钟时间，在该网站提供的伪终端上实践 Git 操作。
* [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/) - 这是一系列关于 Git 的综合教程。
* [Use gitk to understand git](https://lostechies.com/joshuaflanagan/2010/09/03/use-gitk-to-understand-git/) - 使用可视化工具 gitk 来学习 Git 的重要知识(Commit，SHA，Branch，Merge，Rebase 等)。
* [Learn Version Control with Git](https://www.git-tower.com/learn/) - 来自 Tower 制造商 fournova Software 的免费电子书，该系列与付费视频课程相关。
* [Pro Git](https://git-scm.com/book/) - 免费、较为权威的 Git 电子书，采用 CC BY-SA 3.0 协议对外授权使用。
* [The Git Community Book](https://schacon.github.io/gitbook/) - 由 Git 社区数十人维护编写的 Git 教程(译者注：此链接已被上一条所列教程归并)。
* [Git Pocket Guide](http://chimera.labs.oreilly.com/books/1230000000561) - O'Reilly 出版商出版的一本关于 Git 的简明书籍。
* [Git Real: Code School](https://www.codeschool.com/courses/git-real/) - 来自 Code School 的付费培训课程。
* [Git Branching](http://pcottle.github.io/learnGitBranching/) - 以可视化的方式深入理解 Git 分支。
* [Learn Git in a Month of Lunches](https://www.manning.com/books/learn-git-in-a-month-of-lunches) - Manning Publications 出版的 Git 教程。
* [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/index.html) - 免费在线看的 Git "魔法"指南。
* [Git from the bottom up](https://jwiegley.github.io/git-from-the-bottom-up/) - 有关 Git 的一系列精彩文章。
* [Git-it](https://github.com/jlord/git-it-electron) - 在 Mac、Linux 或 Windows 客户端上学习 Git。
* [Git How To](http://githowto.com) - 跟着教程一步一步的学习 Git
* [Migrating to Git LFS](http://vooban.com/en/tips-articles-geek-stuff/migrating-to-git-lfs-for-developing-deep-learning-applications-with-large-files/) - 在已存仓库上使用 Git LFS 来更好地管理大型文件。
* [Explain Git with D3](http://onlywei.github.io/explain-git-with-d3/) - 使用 D3.js 可视化库来展现几个基本的 Git 概念：commit，branch，checkout，reset，revert，merge，rebase，fetch，pull，push，tag。
* [Making Sense of Git – A Visual Perspective](https://appendto.com/2015/06/making-sense-of-git-a-visual-perspective/) - 从时间轴和层级的角度来看 Git 命令。

## 客户端
*Git 客户端被各大电脑及手机平台广泛支持着。*

* [TortoiseGit](https://tortoisegit.org/) - Windows 平台上的一个易于使用的 Git 客户端，并被完美集成在 Windows 资源管理器上。
* [GitHub Desktop](https://desktop.github.com/) - Github 官方出品的 Git 客户端，可与 GitHub 和 GitHub Enterprise 无缝协作。
* [SourceTree](https://www.sourcetreeapp.com/) - 较为知名的免费 Git 客户端，只能运行在 Windows 和 Mac 平台上。
* [Tower](http://www.git-tower.com/) - 较为知名的收费 Git 客户端，只能运行在 Windows 和 Mac 平台上。
* [SmartGit](http://www.syntevo.com/smartgit/) - 一个商业的 SCM 跨平台客户端，完美支持 Git，SVN 和 Mercurial，可运行在 Windows，Mac 和 Linux 上。
* [RabbitVCS](http://rabbitvcs.org/) - TortoiseSVN 版本控制系统的图形工具，集成了 Nautilus 和 Thunar（译者注：这里的翻译意思尚不明确）。
* [gitg](https://wiki.gnome.org/Apps/Gitg/) - 一个开源的 GTK+ Git 客户端。
* [git-cola](http://git-cola.github.io/) - 一个跨平台的 Git 客户端。
* [SGit](https://github.com/sheimi/SGit) - 为 Android 4.x 量身定制的 Git 客户端。
* [Ungit](https://github.com/FredrikNoren/ungit) - 使用最便捷的方式学习 Git，你可以在任何地方任何环境使用它（译者注：该项目包括 npm 安装以及 Atom、VS Code 的插件形式）。
* [GitKraken](https://www.gitkraken.com/) - 一个基于 Electron 的跨平台 Git 客户端，同时支持免费版和高级付费版。
* [GitUp](http://gitup.co) - 一个干净、简介的 Git 客户端，只能运行在 MacOS 系统上。
* [GitExtensions](https://gitextensions.github.io/) - 这是一个 Visual Studio 2010-2015 的拓展插件，和一个独立的 Git 存储库工具。
* [WorkingCopy](https://workingcopyapp.com) - IOS 平台上的一个强大的 Git 客户端，除需内置付费解锁 push 功能外其它功能均免费使用。

## 第三方代码托管平台
*我们拥有很多不同的选择来托管项目的源代码。*

* [GitHub](http://github.com/) - 事实上的首选 Git 托管平台，与大多数外部服务完美整合。
* [BitBucket](http://bitbucket.org/) - 因在其中可建立免费的私人仓库而闻名（最多支持 5 人协作）。
* [CodePlex](https://www.codeplex.com/) - 微软的项目托管平台，上面有很多 SP/C# OSS 项目。
* [Kiln](https://www.fogcreek.com/kiln/) - 付费的 Git 仓库托管平台。
* [GitLab.com](https://about.gitlab.com/gitlab-com/) - 由 GitLab EE 提供服务的免费 Git 仓库托管服务，每个人都可以建立无限的仓库并和任意数量的合作者协作。
* [AWS CodeCommit](https://aws.amazon.com/codecommit/) - Amazon Web Service 在其高可用性基础设施上提供的 SaaS 服务，轻松地托管安全且高度可扩展的私有 Git 仓库。
* [Codeplane](https://codeplane.com/) - 一个没有贡献者数量限制的付费代码托管平台。
* [Deveo](https://deveo.com/) - 一个同时支持 Git, Subversion, Mercurial 和 WebDAV 的付费代码托管平台。

## 自建代码托管平台
*或许你需要使用自己搭建一套代码托管服务平台。*

* [Gitolite](http://gitolite.com/gitolite/) - 拥有细粒度访问控制机制的简易托管平台。
* [GitHub Enterprise](https://enterprise.github.com/) - Github 提供的自建代码托管平台解决方案。
* [Bitbucket Server](https://www.atlassian.com/software/bitbucket/server) - Atlassian 提供的自建代码托管平台，与 JIRA 和其他 Atlassian 产品良好集成。
* [GitLab CE/EE](https://gitlab.com/) - 一个受欢迎的 Git 自建托管平台，提供 CE 免费版和 EE 付费版。
* [Upsource](https://www.jetbrains.com/upsource) - Jetbrains 旗下托管服务平台，10 个协作者以内免费使用，与 YouTrack 和 TeamCity 良好的整合。
* [GitBucket](https://github.com/takezoe/gitbucket/) - 一个仿照 Github，使用 Scala 编写的自建代码托管平台。
* [Gogs](http://gogs.io/) - 一个使用 GO 语言编写的自建代码托管平台。
* [GitBlit](http://gitblit.com/) - 用于管理，查看和服务 Git 仓库的纯 Java 堆栈。
* [Apache Allura](https://allura.apache.org/) - 一个代码托管服务的开源实现。
* [Phabricator](https://www.phacility.com/) - 一整套强大的 Git 工具来帮助公司构建更高质量的软件。
* [RhodeCode CE/EE](https://rhodecode.com/) - 一个提供企业级源代码管理的平台。

## 工作流
*使用廉价的分支策略可以让人们采用除经典集中式工作流程以外的工作流程。*

* [Pro Git - Distributed Workflows](https://git-scm.com/book/it/v2/Distributed-Git-Distributed-Workflows)
* [Atlassian Git Tutorial - Comparing Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows)
* [Gitflow](http://nvie.com/posts/a-successful-git-branching-model/) - 最知名的 Git 工作流。
* [GitHub flow](http://scottchacon.com/2011/08/31/github-flow.html) - 一个只需要 master 分支的简易 Git 工作流。
* [GitLab flow](https://about.gitlab.com/2014/09/29/gitlab-flow/)
* [Git DMZ Flow](https://gist.github.com/djspiewak/9f2f91085607a4859a66)

## 钩子管理策略
*Git 在提交/推送短语中提供挂钩，允许其与代码质量检查工具和持续集成（CI）集成。*

* [pre-commit](http://pre-commit.com/) - 一个用于管理和维护的多语言预提交钩子的框架，由 Yelp 团队打造，广泛支持多种编程语言。
* [Overcommit](https://github.com/brigade/overcommit/) - 一个用 Ruby 编写的可扩展 Git 钩子管理器。
* [git-hooks](https://github.com/icefox/git-hooks/) - 一个管理项目、用户和全局 Git 钩子的工具。
* [quickhook](https://github.com/dirk/quickhook/) - 一个自称比 Git Hooks 更快的钩子库。
* [husky](https://github.com/typicode/husky) - 为 Node.js 打造的 Git 钩子，可在 package.json 中进行配置。
* 更多资源可参考 https://githooks.com/

## 工具
*这里有各种日常 Git 操作工具。*

* [awesome-git-addons](https://github.com/stevemao/awesome-git-addons) - 这里列出了超过 20 个 Git 插件，包括所有可用命令。
* [myrepos](https://myrepos.branchable.com/) - 一个管理多个版本控制库的工具。
* [mu-repo](http://fabioz.github.io/mu-repo/) - 一个管理多个 Git 仓库的工具。
* [gr](http://mixu.net/gr/) - 一个管理多个 Git 仓库的工具。
* [BFG Repo-Cleaner](https://rtyley.github.io/bfg-repo-cleaner/) - 一个更简单、更快捷的替代 git-filter-branch 的方法库，用于清理 Git 存储库历史记录中的错误数据。
* [GitIgnore Collection](https://github.com/github/gitignore) - 该项目为各种编程语言收集其专属的 .gitignore 文件。
* [etckeeper](http://etckeeper.branchable.com/) - 一个让 /etc 存储在 Git 仓库中的工具集合。
* [git-extras](https://github.com/tj/git-extras) – 集成各种常见 Git 命令的命令行工具集。
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 另一个有用的 Git 命令工具集。
* [git-follow](https://github.com/nickolasburr/git-follow) - 一个用于跟踪整个 Git 仓库历史记录中文件生命周期变化的工具。
* [Gitrob](https://github.com/michenriksen/gitrob) - 一个用于查找 GitHub 上公开可用文件中存在的敏感信息的命令行工具。
* [gitFS](https://www.presslabs.com/gitfs/) - 与 Git 完全集成的 FUSE 文件系统。
* [Gitless](http://gitless.com/) - Git 的实验版本，其改变了 Git 的一些基本概念。
* [ghq](https://github.com/motemen/ghq) — 便捷的管理远程仓库。
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - 为 Git 用户提供丰富而又有趣的 bash 提示。

## 拓展
*Git 专为源代码管理而诞生，但是人们扩展了这个想法，并将版本控制推向了更多的领域。*

* [Git Large File Storage](https://git-lfs.github.com/) - 由 GitHub 支持的大文件版本化实用解决方案。
* [Git Virtual File System or GVFS](https://github.com/Microsoft/GVFS) - 以管理非常大的 Git 存储库，同时保持大多数操作的速度和效率的解决方案，由微软推进。
* [git-annex](https://git-annex.branchable.com/) - 可以通过 [git-annex assistant](https://git-annex.branchable.com/assistant/) 创建一个同步文件夹，来像操作一个正常的 Git 仓库一样来管理机器上的大型二进制文件。
