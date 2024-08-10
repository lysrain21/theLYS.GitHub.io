# vim自查表

`i` into write mode

esc  quit write mode into normal mode

`:` from normal into control mode

`:w` save file

`:q` quit vim

### 基本写入

`i`: insert before

`a`: insert behind

G: to the last

`shift + a`: insert before the whole line

`shift + a`: insert behind the whole line

`o`: insert beneath the whole line

`shift + o`: insert on the whole line

### 移动方向

`hjkl`：左上下右，vim配置文件可以改键位

`x`: 删掉当前光标的空格

`d + motion`:

`y + motion`:复制

`q + motion`:粘贴

`c + motion`

​	c w:改变一个词

​	c i any:改变词中

`f + motion`

### 控制命令

控制命令中的搜索`/`

`:split` 上下分屏

`:vsplit`左右分屏

### 可视模式

`v`: normal visual

`shift + v`: a whole line is visual

选中后在每一行的同一个位置都加入某元素普通模式下输入`:normal`

`control v`可视块模式

### 插件推荐

1.显示当前模式

2.字体主题

# lazyVim

space + e ：打开文件树

space + f + f：搜索文件

s +字母+ 方向键：跳转到相应位置

space + c + r：替换代码名字

space + s + G + 名字：在该文件中搜索字符串

space + x +x：修改错误

space + c + a：启动code action来通过lsp处理代码

space + u + C：切换主题

space + f + b：打开缓冲区，[+b向左切换，]+b向右切换

space + |：左右分屏

space + -：上下分屏

ctrl + hjkl：上下左右插入 

crtl + 方向键：调整分屏大小 

space + sh：搜索帮助

创建todo并用space + f + t来进行搜索

自动补全代码：ctrl + n在里面选择，按Tab一个一个填入 

space + s + k：搜索keymaps

space + s + r : 全局替换 

space + g + g：lazygit 

space + f + t：开启临时终端程序

g + d：跳转定义

K：悬浮查看定义
