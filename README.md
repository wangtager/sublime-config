### Hello Sublime 3或2 Users

我使用的操作系统是 Mac (目前是 Yosemite)，不同的操作系统，在 sublime
配置上会有微小的差别。

我使用 [Package
Control](https://packagecontrol.io/installation)，所有我安装的包在 [Package
Control.sublime-settings 文件](https://github.com/happypeter/sublime-config/blob/master/Package%20Control.sublime-settings)
 中都列出了。



### 安装步骤

－ 在新系统上 sublime 3/2 安装好之后

```console
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/
git clone git@github.com:happypeter/sublime-config.git
mv sublime-config/* .
rm -rf sublime-config
```

- 到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的包会自动安装上。（ ctrl 跟 导引号 来呼叫出 command console ）

### 插件说明
1. ChineseLocalization
  语言包功能，切换各国语言
2. Ctags
  函数跳转，我的电脑上是Alt+点击 函数名称，会跳转到相应的函数
3. git
  git 版本控制
4. Vue Syntax Highlight
  Vue语法高亮
5. Vuejs Snippets
6. AdvancedNewFile
  快速创建文件
7. Emmet(同时自动安装PyV8库）
  一种快速编写html/css的方法
8. pug
9. Sass
10. SyncedSideBar
11. AutoFileName
功能：快捷输入文件名(按Tab键或鼠标点击选中)
12. Nodejs
功能：node代码提示







