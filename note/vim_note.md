

#### 修改文字

```cpp
n==
vawp
yaw yiw
"+y 复制到系统剪贴板
"+p 从系统剪贴板粘贴
J 删除换行符（合并成一行）
u 撤销上一次操作
CTRL-R 撤销上次的撤销操作
ZZ 保存当前文件并推出此文件
w ge e b 下一个字母开头，结尾，当前字母结尾，上一个字母开头
:set ruler 在Vim窗口的右下角显示当前光标位置
:set (no)number 在每行的前面显示一个行号
:set ignorecase 查找内容忽略大小写
* # 向前向后查找当前单词
:set hlsearch 高亮显示搜索结果
:set nohlsearch（不）高亮显示搜索结果
:marks 用来查看标记的列表
cw 删除一个word并让你置身于Insert模式
. 重复上一次做出的改动（命令）
:args 显示当前正在编辑的文件
`ctrl + ^` 要在两个文件间快速切换
`CTRL + shift + w` 命令可以切换当前活动窗口
:only 关闭除当前窗口外的所有其它窗口
:split xxx.x 可以打开第二个窗口同时在新打开的窗口中开始编辑作为
参数的文件
```

```cpp
:set all  可设置的环境变量列表
:set   环境变量的当前值
:set nu   设定资料的行号。
:set nonu  取消行号设定。
:set ai   自动内缩。
:set noai   取消自动内缩。
:set ruler  会在屏幕右下角显示当前光标所处位置，并随光移动而改变，占用屏幕空间较小，使用也比较方便，推荐使用。
:set hlsearch 在使用查找功能时，会高亮显示所有匹配的内容。
:set nohlsearch  关闭此功能。
:set incsearch  使Vim在输入字符串的过程中，光标就可定位显示匹配点。
:set nowrapscan 关闭查找自动回环功能，即查找到文件结尾处，结束查找；默认状态是自动回环
```
```cpp
:10,20w test  将第10行至第20行的资料写入test文件。
:10,20w>>test 将第10行至第20行的资料加在test文件之后。
:r test   将test文件的资料读入编辑缓冲区的最后。
:e [filename] 编辑新的文件。
:e! [filename] 放弃当前修改的文件，编辑新的文件。
:sh   进入shell环境，使用exit退出，回到编辑器中。
:!cmd  运行命令cmd后，返回到编辑器中。
```
```cpp
:10,20d   删除第10行至第20行的资料。
:10d   删除第10行的资料。
:%d   删除整个编辑缓冲区。
:10,20co30  将第10行至第20行的资料复制至第30行之后。
:10,20mo30  将第10行至第20行的资料搬移至第30行之后。
```