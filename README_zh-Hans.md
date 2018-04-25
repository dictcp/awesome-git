# Awesome Git
收集一些有关 Git 的工具、资源清单列表。

## 加入我们
如果你有其他有趣的 Git 工具/项目/资源推荐，欢迎提交 Pull Request 请求到本仓库中。

## Table of Contents
- [Awesome Git](#awesome-git)
	- [Tutorial](#tutorial)
  - [Client](#client)
  - [Repository Hosting](#repository-hosting)
  - [Self-Hosted Repository](#self-hosted-repository)
  - [Workflow](#workflow)
  - [Hook management](#hook-management)
  - [Tools](#tools)
  - [Extensions](#extensions)

## 教程
*畅游互联网，我们可以找到很多 Git 学习资料*

* [Flight rules for Git](https://github.com/k88hudson/git-flight-rules) - 该教程在你遇到 Git 错误的时候有效地指导你
* [Try Git](https://try.github.io/) - 利用 15 分钟时间，在该网站提供的伪终端上实践 Git 操作
* [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/) - 这是一系列关于 Git 的综合教程
* [Use gitk to understand git](https://lostechies.com/joshuaflanagan/2010/09/03/use-gitk-to-understand-git/) - 使用可视化工具 gitk 来学习 Git 的重要知识(Commit，SHA，Branch，Merge，Rebase 等)
* [Learn Version Control with Git](https://www.git-tower.com/learn/) - 来自 Tower 制造商 fournova Software 的免费电子书，该系列与付费视频课程相关
* [Pro Git](https://git-scm.com/book/) - 免费、较为权威的 Git 电子书，采用 CC BY-SA 3.0 协议对外授权使用
* [The Git Community Book](https://schacon.github.io/gitbook/) - 由 Git 社区数十人维护编写的 Git 教程(译者注：此链接已被上一条所列教程归并)
* [Git Pocket Guide](http://chimera.labs.oreilly.com/books/1230000000561) - O'Reilly 出版商出版的一本关于 Git 的简明书籍
* [Git Real: Code School](https://www.codeschool.com/courses/git-real/) - 来自 Code School 的付费培训课程
* [Git Branching](http://pcottle.github.io/learnGitBranching/) - 以可视化的方式深入理解 Git 分支
* [Learn Git in a Month of Lunches](https://www.manning.com/books/learn-git-in-a-month-of-lunches) - Manning Publications 出版的 Git 教程
* [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/index.html) - 免费在线看的 Git "魔法"指南
* [Git from the bottom up](https://jwiegley.github.io/git-from-the-bottom-up/) - 有关 Git 的一系列精彩文章
* [Git-it](https://github.com/jlord/git-it-electron) - 在 Mac、Linux 或 Windows 客户端上学习 Git
* [Git How To](http://githowto.com) - 跟着教程一步一步的学习 Git
* [Migrating to Git LFS](http://vooban.com/en/tips-articles-geek-stuff/migrating-to-git-lfs-for-developing-deep-learning-applications-with-large-files/) - 在已存仓库上使用 Git LFS 来更好地管理大型文件
* [Explain Git with D3](http://onlywei.github.io/explain-git-with-d3/) - 使用 D3.js 可视化库来展现几个基本的 Git 概念：commit，branch，checkout，reset，revert，merge，rebase，fetch，pull，push，tag
* [Making Sense of Git – A Visual Perspective](https://appendto.com/2015/06/making-sense-of-git-a-visual-perspective/) - 从时间轴和层级的角度来看 Git 命令

## 客户端
*Git 客户端被各大电脑及手机平台广泛支持着*

* [TortoiseGit](https://tortoisegit.org/) - Windows 平台上的一个易于使用的 Git 客户端，并被完美集成在 Windows 资源管理器上。
* [GitHub Desktop](https://desktop.github.com/) - Github 官方出品的 Git 客户端，可与 GitHub 和 GitHub Enterprise 无缝协作
* [SourceTree](https://www.sourcetreeapp.com/) - 较为知名的免费 Git 客户端，只能运行在 Windows 和 Mac 平台上
* [Tower](http://www.git-tower.com/) - 较为知名的收费 Git 客户端，只能运行在 Windows 和 Mac 平台上
* [SmartGit](http://www.syntevo.com/smartgit/) - 一个商业的 SCM 跨平台客户端，完美支持 Git，SVN 和 Mercurial，可运行在 Windows，Mac 和 Linux 上
* [RabbitVCS](http://rabbitvcs.org/) - TortoiseSVN 版本控制系统的图形工具，集成了 Nautilus 和 Thunar（译者注：这里的翻译意思尚不明确）
* [gitg](https://wiki.gnome.org/Apps/Gitg/) - 一个开源的 GTK+ Git 客户端
* [git-cola](http://git-cola.github.io/) - 一个跨平台的 Git 客户端
* [SGit](https://github.com/sheimi/SGit) - 为 Android 4.x 量身定制的 Git 客户端
* [Ungit](https://github.com/FredrikNoren/ungit) - 使用最便捷的方式学习 Git，你可以在任何地方任何环境使用它（译者注：该项目包括 npm 安装以及 Atom、VS Code 的插件形式）
* [GitKraken](https://www.gitkraken.com/) - 一个基于 Electron 的跨平台 Git 客户端，同时支持免费版和高级付费版
* [GitUp](http://gitup.co) - 一个干净、简介的 Git 客户端，只能运行在 MacOS 系统上
* [GitExtensions](https://gitextensions.github.io/) - 这是一个 Visual Studio 2010-2015 的拓展插件，和一个独立的 Git 存储库工具
* [WorkingCopy](https://workingcopyapp.com) - IOS 平台上的一个强大的 Git 客户端，除需内置付费解锁 push 功能外其它功能均免费使用

## 代码托管平台
*我们拥有很多不同的选择来托管项目的源代码*

* [GitHub](http://github.com/) - 事实上的首选 Git 托管平台，与大多数外部服务完美整合
* [BitBucket](http://bitbucket.org/) - 因在其中可建立免费的私人仓库而闻名（最多支持 5 人协作）
* [CodePlex](https://www.codeplex.com/) - 微软的项目托管平台，上面有很多 SP/C# OSS 项目
* [Kiln](https://www.fogcreek.com/kiln/) - 付费的 Git 仓库托管平台
* [GitLab.com](https://about.gitlab.com/gitlab-com/) - 由 GitLab EE 提供服务的免费 Git 仓库托管服务，每个人都可以建立无限的仓库并和任意数量的合作者协作
* [AWS CodeCommit](https://aws.amazon.com/codecommit/) - Amazon Web Service 在其高可用性基础设施上提供的 SaaS 服务，轻松地托管安全且高度可扩展的私有 Git 仓库
* [Codeplane](https://codeplane.com/) - 一个没有贡献者数量限制的付费代码托管平台
* [Deveo](https://deveo.com/) - 一个同时支持 Git, Subversion, Mercurial 和 WebDAV 的付费代码托管平台

## Self-Hosted Repository
*Or you can host the code yourselves*

* [Gitolite](http://gitolite.com/gitolite/) - a simple with fine-grained access control
* [GitHub Enterprise](https://enterprise.github.com/) - self-hosted solution provided from GitHub
* [Bitbucket Server](https://www.atlassian.com/software/bitbucket/server) - self-hosted refrom Atlassian. Good integration with JIRA and other Atlassian products
* [GitLab CE/EE](https://gitlab.com/) - a popular open-source Git (CE) with paid support option (EE).
* [Upsource](https://www.jetbrains.com/upsource) - recent offer from Jetbrains, a famos developer-oriented software company. Code repository hosting feature pending. Free for 10 users. Good integration with YouTrack and TeamCity
* [GitBucket](https://github.com/takezoe/gitbucket/) - a GitHub clone powered by Scala.
* [Gogs](http://gogs.io/) - a self-hosted Git Service written in Go.
* [GitBlit](http://gitblit.com/) - Pure Java Stack for managing, view, and serving Git repositories.
* [Apache Allura](https://allura.apache.org/) - an open source implementation of project hosting platform
* [Phabricator](https://www.phacility.com/) - an integrated set of powerful tools to help companies build higher quality software
* [RhodeCode CE/EE](https://rhodecode.com/) - a platform delivering enterprise source code management

## Workflow
*Inexpensive branching allows people adopt workflows other than the classic centralilzed workflow*

* [Pro Git - Distributed Workflows](https://git-scm.com/book/it/v2/Distributed-Git-Distributed-Workflows)
* [Atlassian Git Tutorial - Comparing Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows)
* [Gitflow](http://nvie.com/posts/a-successful-git-branching-model/) - the most well-known Git workflow model
* [GitHub flow](http://scottchacon.com/2011/08/31/github-flow.html) - a simple branching model with a single master
* [GitLab flow](https://about.gitlab.com/2014/09/29/gitlab-flow/)
* [Git DMZ Flow](https://gist.github.com/djspiewak/9f2f91085607a4859a66)

## Hook management
*Git provide hooks at commit/push phrase, allowing integration with and code quality checking tool and Continuous Integration (CI)*

* [pre-commit](http://pre-commit.com/) - a framework for managing and maintaining multi-language pre-commit hooks from Yelp. Extensive support for multiple programming language.
* [Overcommit](https://github.com/brigade/overcommit/) - a extendable Git hook manager written with Ruby.
* [git-hooks](https://github.com/icefox/git-hooks/) - tool to manage project, user, and global Git hooks
* [quickhook](https://github.com/dirk/quickhook/) - a fast, Unix'y, opinionated Git hook runner
* [husky](https://github.com/typicode/husky) - Git hooks for Node.js, manage your hooks from your package.json
* more on https://githooks.com/

## Tools
*Various tools for daily operations*

* [awesome-git-addons](https://github.com/stevemao/awesome-git-addons) - lists more than 20 git addons including all available commands
* [myrepos](https://myrepos.branchable.com/) - a tool to manage multiple version control repositories
* [mu-repo](http://fabioz.github.io/mu-repo/) - a tool to help in dealing with multiple git repositories
* [gr](http://mixu.net/gr/) - a tool for managing multiple git repositories
* [BFG Repo-Cleaner](https://rtyley.github.io/bfg-repo-cleaner/) - a simpler, faster alternative to git-filter-branch for cleansing bad data out of your Git repository history
* [GitIgnore Collection](https://github.com/github/gitignore) - collection of gitignore files for various programming language
* [etckeeper](http://etckeeper.branchable.com/) - a collection of tools to let /etc be stored in a git repository
* [git-extras](https://github.com/tj/git-extras) – git utilities adding useful git commands.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Another collection of useful git commands.
* [git-follow](https://github.com/nickolasburr/git-follow) - a tool for following lifetime changes of a file throughout the history of a Git repository.
* [Gitrob](https://github.com/michenriksen/gitrob) - a command line tool to find sensitive information lingering in publicly available files on GitHub
* [gitFS](https://www.presslabs.com/gitfs/) - a FUSE file system that fully integrates with git
* [Gitless](http://gitless.com/) - an experimental version of Git that changes some of Git's underlying concepts
* [ghq](https://github.com/motemen/ghq) — Organization for remote repositories
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy bash prompt for Git users

## Extensions
*Git is designed for source control management. but people extend the idea and push version control to everywhere*

* [Git Large File Storage](https://git-lfs.github.com/) - practical solution for versioning large files. supported by GitHub
* [Git Virtual File System or GVFS](https://github.com/Microsoft/GVFS) - solution for managing very large Git repository while maintaining speed and efficiency of most operations. in developement by Microsoft.
* [git-annex](https://git-annex.branchable.com/) - allow managing large binaries among machines, as if operation a normal git repository. possible to creates a synchronised folder with [git-annex assistant](https://git-annex.branchable.com/assistant/).
