# 快捷键说明

## 编辑器与窗口管理
* 打开一个新窗口： Ctrl+Shift+N
* 关闭窗口： Ctrl+Shift+W
* 同时打开多个编辑器（查看多个文件）
* 新建文件 Ctrl+N
* 文件之间切换 Ctrl+Tab
* 切出一个新的编辑器（最多 3 个） Ctrl+\
* 左中右 3 个编辑器的快捷键 Ctrl+1 Ctrl+2 Ctrl+3
* 3 个编辑器之间循环切换 Ctrl+
* 编辑器换位置， Ctrl+k然后按 Left或 Right

## 代码编辑

### 格式调整
* 代码行缩进 Ctrl+[ 、 Ctrl+]
* Ctrl+C 、 Ctrl+V 复制或剪切当前行/当前选中内容
* 代码格式化： Shift+Alt+F，或 Ctrl+Shift+P 后输入 format code
* 上下移动一行： Alt+Up 或 Alt+Down
* 向上向下复制一行： Shift+Alt+Up 或 Shift+Alt+Down
* 在当前行下边插入一行 Ctrl+Enter
* 在当前行上方插入一行 Ctrl+Shift+Enter

### 光标相关
* 移动到行首： Home
* 移动到行尾： End
* 移动到文件结尾： Ctrl+End
* 移动到文件开头： Ctrl+Home
* 移动到定义处： F12
* 定义处缩略图：只看一眼而不跳转过去 Alt+F12
* 移动到后半个括号： Ctrl+Shift+]
* 选择从光标到行尾： Shift+End
* 选择从行首到光标处： Shift+Home
* 删除光标右侧的所有字： Ctrl+Delete
* 扩展/缩小选取范围： Shift+Alt+Left 和 Shift+Alt+Right
* 多行编辑(列编辑)：Alt+Shift+鼠标左键，Ctrl+Alt+Down/Up
* 同时选中所有匹配： Ctrl+Shift+L
* Ctrl+D 下一个匹配的也被选中
* 回退上一个光标操作： Ctrl+U

### 重构代码
* 找到所有的引用： Shift+F12
* 同时修改本文件中所有匹配的： Ctrl+F12
* 重命名：比如要修改一个方法名，可以选中后按 F2，输入新的名字，回车，会发现所有的文件都修改了
* 跳转到下一个 Error 或 Warning：当有多个错误时可以按 F8 逐个跳转
* 查看 diff： 在 explorer 里选择文件右键 Set file to compare，然后需要对比的文件上右键选择 Compare with file_name_you_chose

### 查找替换
* 查找 Ctrl+F
* 查找替换 Ctrl+H
* 整个文件夹中查找 Ctrl+Shift+F

## 显示相关
* 全屏：F11
* zoomIn/zoomOut：Ctrl +/-
* 侧边栏显/隐：Ctrl+B
* 显示资源管理器 Ctrl+Shift+E
* 显示搜索 Ctrl+Shift+F
* 显示 Git Ctrl+Shift+G
* 显示 Debug Ctrl+Shift+D
* 显示 Output Ctrl+Shift+U
  
# 插件安装卸载
* 安装：点击左边栏上方的最后一项进入插件管理页面，最上方的搜索框可以搜索VSCode的插件，或者直接查看插件管理页面下面一栏的RECOMMENDED中列出的可安装插件，点击绿色的Install按钮就可以完成安装。
* 卸载：插件管理页面的上面一栏ENABLED列出了所有已安装的插件，点击这个插件左下角的齿轮按钮，在下拉列表中选择Uninstall即可卸载。
  
# 在 VSCode 中使用 Git
在创建好本地和远程仓库后，在VS Code中打开仓库所在的文件夹
1. 命令行操作：选择菜单中的Terminal-New Terminal打开命令行，输入git指令，效果等于在git bash上输入指令。
2. 图形化界面：选择左边栏的Source Control按钮就可以用git的方式打开该仓库文件夹，修改过的文件会在CHANGES这一栏列出，点击文件会列出修改前后的对比页面。点击+号按钮暂存修改；点击对勾按钮commit（之后会弹出文字编辑框，用来输入commit的message）；点击···按钮弹出下拉列表，里面有更多功能，包括Push、Pull等等，点击就可以使用。