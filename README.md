<p align="center">
	<a href="https://gitmoji.carloscuesta.me">
		<img src="https://cloud.githubusercontent.com/assets/7629661/20073135/4e3db2c2-a52b-11e6-85e1-661a8212045a.gif" width="456" alt="gitmoji">
	</a>
</p>
<p align="center">
	<a href="https://travis-ci.org/carloscuesta/gitmoji">
		<img src="https://img.shields.io/travis/carloscuesta/gitmoji.svg?style=flat-square"
			 alt="Build Status">
	</a>
	<a href="https://gitmoji.carloscuesta.me">
		<img src="https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square"
			 alt="Gitmoji">
	</a>
</p>
git commit emoji 中文使用指南([EN](https://gitmoji.carloscuesta.me/))
============================
> 	Fork By [git-commit-emoji-cn](https://github.com/liuchengxu/git-commit-emoji-cn)，由于原项目更新频率及来源问题，故自立分支。 

执行 `git commit` 时使用 emoji 为本次提交打上一个 "标签", 使得此次 commit 的主要工作得以凸现，也能够使得其在整个提交历史中易于区分与查找。

截取的 [gitmoji](https://github.com/carloscuesta/gitmoji) 快照:

![gitmoji-snapshot](snapshot.png)

### commit 格式

`git commit` 时，提交信息遵循以下格式：

```sh
:emoji1: :emoji2: 主题

提交信息主体

Ref <###>
```

初次提交示例：

```sh
git commit -m ":tada: Initialize Repo"
```

### emoji 指南

emoji                                   | emoji 代码                   | commit 说明
:--------                               | :--------                    | :--------
:construction: (施工)                   | `:construction:`             | 工作进行中
:tada: (庆祝)                           | `:tada:`                     | 初次提交
:white_check_mark: (白色复选框)         | `:white_check_mark:`         | 增加测试
:ok_hand: (OK手势)						| `:ok_hand:`				   | 由于代码Reciew造成的修改
:truck: (卡车)							| `:truck:`					   | 移除或者重命名文件
:sparkles: (火花)                       | `:sparkles:`                 | 引入新功能
:bug: (bug)                             | `:bug:`                      | 修复 bug
:ambulance: (急救车)                    | `:ambulance:`                | 重要补丁
:wrench: (扳手)							| `:wrench:`				   | 修改配置文件
:fire: (火焰)                           | `:fire:`                     | 移除代码或文件
:mute: (保持安静)						| `:mute:`					   | 移除日志
:loud_sound: (大声叫喊)					| `:loud_sound:`			   | 添加日志
:heavy_plus_sign: (加号)                | `:heavy_plus_sign:`          | 增加一个依赖
:heavy_minus_sign: (减号)               | `:heavy_minus_sign:`         | 减少一个依赖
:beers: (啤酒)							| `:beers:`					   | 醉意熏熏地写代码
:alien: (外星人)						| `:alien:`					   | 由于外部API更改造成的代码变更
:boom: (爆炸)							| `:boom:`					   | 项目介绍产生改变
:art: (调色板)                          | `:art:`                      | 改进代码结构/代码格式
:zap: (闪电)<br>:racehorse: (赛马)      | `:zap:`<br>`:racehorse:`     | 提升性能
:rewind: (回溯)							| `:rewind:`				   | 回溯代码版本
:children_crossing: (带着你的孩子)		| `:children_crossing:`		   | 提升用户体验/可用性
:lipstick: (口红)                       | `:lipstick:`                 | 更新 UI 和样式文件
:memo: (备忘录)                         | `:memo:`                     | 撰写文档
:rocket: (火箭)                         | `:rocket:`                   | 部署功能
:lock: (锁)                             | `:lock:`                     | 修复安全问题
:apple: (苹果)                          | `:apple:`                    | 修复 macOS 下的问题
:penguin: (企鹅)                        | `:penguin:`                  | 修复 Linux 下的问题
:checkered_flag: (旗帜)                 | `:checked_flag:`             | 修复 Windows 下的问题
:bookmark: (书签)                       | `:bookmark:`                 | 发行/版本标签
:rotating_light: (警车灯)               | `:rotating_light:`           | 移除 linter 警告
:green_heart: (绿心)                    | `:green_heart:`              | 修复 CI 构建问题
:arrow_down: (下降箭头)                 | `:arrow_down:`               | 降级依赖
:arrow_up: (上升箭头)                   | `:arrow_up:`                 | 升级依赖
:construction_worker: (工人)            | `:construction_worker:`      | 添加 CI 构建系统
:chart_with_upwards_trend: (上升趋势图) | `:chart_with_upwards_trend:` | 添加分析或跟踪代码
:hammer: (锤子)                         | `:hammer:`                   | 重大重构
:whale: (鲸鱼)                          | `:whale:`                    | Docker 相关工作
:globe_with_meridians: (地球)           | `:globe_with_meridians:`     | 国际化与本地化
:pencil2: (铅笔)                        | `:pencil2:`                  | 修复 typo


### 如何在命令行中显示 emoji

默认情况下，在命令行中并不会显示出 emoji, 仅显示 emoji 代码。不过可以使用 [emojify](https://github.com/mrowa44/emojify) 使得在命令行也可显示 emoji, 它是一个 shell 脚本，安装与使用都很简单，在 [这里](https://github.com/mrowa44/emojify) 查看如何安装与使用。

![emojify](terminal_emojify.png)

### 参考

- [gitmoji](https://github.com/carloscuesta/gitmoji/)
- [An emoji guide for your commit messages](https://gitmoji.carloscuesta.me/)
- [styleguide-git-commit-message](https://github.com/slashsBin/styleguide-git-commit-message)
- [atom git commit messages guide](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages)
- [emoji-cheat-sheet](http://www.webpagefx.com/tools/emoji-cheat-sheet/)
- [程序员提交代码的 emoji 指南——原来表情文字不能乱用](https://www.h5jun.com/post/gitmoji.html)
