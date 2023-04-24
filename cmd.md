# how to use cmd

## Unix Shell（命令行）

### 命令

`ls` 列目录 list

- -a 显示隐藏档 all
- -l 详细信息

`chmod`变更档案模式 change mode

`chmod [ -fR ] mode filename ...`

- f force 不会处理失败的动作
- R recursive 处理子树/子目录

`cat` 串联显示

`cd`改变当前目录

- from C disk to D disk: `D:`

`cp`拷贝 copy

`cp [-fip]source_file target_file`

`move` 移动 move

`mv [-fi] source_file... target_file`

`rm` 删除 remove

`rmdir` 删除空目录

`pwd` 显示当前路径

`ctrl+q` 恢复被暂停的输出

`ctrl＋shift＋c` 复制

`ctrl＋shift＋v` 粘贴

## what is path

## how to call python script

### if \_\_name\_\_ == '\_\_main\_\_'

通俗的理解\_\_name\_\_ == '\_\_main\_\_'：假如你叫小明.py，在朋友眼中，你是小明(\_\_name\_\_ == '小明')；在你自己眼中，你是你自己(\_\_name\_\_ == '\*\*main\*\*')。

if \_\_name\_\_ == '\_\_main\_\_'的意思是：当.py 文件被直接运行时，if \_\_name\_\_ == '\_\_main\_\_'之下的代码块将被运行；当.py 文件以模块形式被导入时，if \_\_name\_\_ == '\_\_main\_\_'之下的代码块不被运行。

一个 Python 源码文件（.py）除了可以被直接运行外，还可以作为模块（也就是库），被其他.py 文件导入。不管是直接运行还是被导入，.py 文件的最顶层代码都会被运行（Python 用缩进来区分代码层次），而当一个.py 文件作为模块被导入时，我们可能不希望一部分代码被运行。

Ref:

[unix shell](https://baike.baidu.com/item/unix%20shell/2478385?fr=aladdin)

[Linux-ls(ll)-alias](https://www.cnblogs.com/wangziqiang/p/5107510.html)

[linux 命令行突然卡住的一种解决办法](https://blog.csdn.net/weixin_41973774/article/details/119241860)

[如何简单地理解 Python 中的 if \_\_name\_\_ == '\_\_main\_\_'](https://blog.csdn.net/yjk13703623757/article/details/77918633)
