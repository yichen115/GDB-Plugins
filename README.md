# GDB-Plugins
## 使用
在 pwndbg 文件夹中`git init`初始化一下，然后运行`./setup.sh`安装

想用peda：`echo "source ~/GDB-Plugins/peda/peda.py" > ~/.gdbinit`

想用peda-heap：`echo "source ~/GDB-Plugins/peda-heap/peda.py" > ~/.gdbinit`（感觉这个挺好用的，扩展了heap的功能，还保留了peda的）

想用gef：`echo "source ~/GDB-Plugins/gef/gef.py" > ~/.gdbinit`

想用pwndbg：`echo "source ~/GDB-Plugins/pwndbg/gdbinit.py" > ~/.gdbinit`

## 参考
这些工具的github地址：

https://github.com/longld/peda

https://github.com/hugsy/gef

https://github.com/pwndbg/pwndbg

https://github.com/Mipu94/peda-heap
