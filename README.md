### Sublime 插件和配置文件的版本控制

使用 [Package
Control](https://packagecontrol.io/installation)，所有安装的包在 [Package
Control.sublime-settings 文件](https://github.com/wangtager/sublime-config/blob/master/Package%20Control.sublime-settings)
 中都列出了。



### 使用步骤

首先在新系统上 sublime 3/2 安装好之后

```console

  1. 找到sublime插件目录
  打开sumlime, 选择菜单栏-首选项-浏览插件目录，然后在目录下打开User文件夹
  (mac系统下的插件地址是~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/)
  (windows下的插件地址是C:\Users\pp\AppData\Roaming\Sublime Text 3\Packages\User)

  2. cd 到插件的地址

  3. git clone https://github.com/wangtager/sublime-config.git

  4. 把sublime 插件和配置都存放在自己的git仓库，像操作其它项目一样对配置进行版本控制。

  ** 一次配置，终生有效。再也不用担心换电脑，重新一个一个的安装插件和配置了 **

```

- 到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的包会自动安装上。（ ctrl 跟 导引号 来呼叫出 command console ）
- 如果已经安装了packagecontrol， 打开命令栏`Ctrl+Shift+P`, 在命令栏输入`pi`, 选择`Package Control: Install Package` 安装即可。

### 插件说明
1. ChineseLocalization
  语言包功能，切换各国语言
2. Ctags [使用](https://www.jianshu.com/p/8e6d67bde952)
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
13. ctrl+shift+p 在输入ssyvue可以快速输入vue的代码片段（区分插件cVuejs Snippets和Vuejs Complete Package）

最近打开的数量可以Main.sublime-menu文件里增加对象`{ "command": "open_recent_file", "args": {"index": 0 } },然后依次index的大小`
### 其它
1. channel_v3.json文件位置切换
https://wangtager.github.io/sublime-config/channel_v3.json 远程
C:/Users/pp/AppData/Roaming/Sublime Text 3/Packages/User/channel_v3.json 本地1
C:/Users/dell/AppData/Roaming/Sublime Text 3/Packages/User/channel_v3.json 本地2

快速切换项目(安装最近打开文件的插件即可)、ctags的配置、相对path跳转、markdown的预览






