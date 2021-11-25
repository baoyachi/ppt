# vscode使用
使用vscode，也属于无奈之举，虽然ide使用的习惯，但出于以下两个方面。还是想让自己走出舒适圈。
* 团队大部分同学是用vscode，和他们环境尽量保持一致。虽然出问题比较少，但是偶尔一个问题，会耗掉几个小时，不划算。
* 自己用ide几年，vscode开发还是主流，打破舒适圈，另一方面，远程开发的熟悉工具，方便我用ipad Pro工作.

## 环境
* oh-my-zsh

#### 安装
* https://ohmyz.sh/#install
#### 切换到zsh shell

* 查看当前shell:
```sh
~ echo $SHELL
```
* 切换zsh shell: 编辑默认shell,顶部添加 `exec zsh`
```sh
~ vi ~/.bashrc
exec zsh
...
```
让系统使用zsh shell,之后我们的环境变量可以直接在`.zshrc`文件中编辑。

#### git 高亮显示
```sh
git config --global color.ui true
```



## 快捷键（mac版本）
* 上一个浏览位置：`ctrl + -`

