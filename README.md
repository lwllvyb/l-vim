l-vim
=====

I will put my vim confige into this repo!

1、vim执行命令

在命令中执行命令方式

:!command

2、常用插件

本人插件参考k-vim配置文件(https://github.com/lwllvyb/k-vim), 并根据个人情况，做了适当的修改。

1) 目录树(https://github.com/scrooloose/nerdtree)
   目录命令：
    ,n  打开/关闭属性目录树结构

    (在nerdtree窗口常用操作)）
    x   收起当前目录树
    X   递归收起当前目录树
    r   刷新跟目录树
    R   刷新跟目录树

    p   跳到当前节点的服节点
    P   跳到root节点
    k/j 上下移动
    K   到同目录的第一个节点
    J   到同目录的最后一个节点

    o   打开文件、目录、标签

    s   split 上下分屏
    v   vsplit 左右分屏

    c   将当前目录设为根节点

    q   关闭
2)tab/buffer 导航增强（https://github.com/szw/vim-ctrlspace)

注意：有些人的ctrl + space被占用，本人的快捷键是《C+Shit + Space》(以下是默认快捷键)
let g:ctrlspace_default_mapping_key="<C-Space>"

ctrl + <sapce> 得到当前tab的buffer列表
    以下命令实在以上命令基础上进行

    j/k     上下移动
    回车    跳转到
    v/V     vsp分屏打开，v会进入对应文件，V会保留在ctrlspace
    s/S     sp分屏打开

    l       展示/关闭tab列表
            j/k     上下移动
            =       给tab命名
            -       将当前tab移动到左侧
            +       将当前tab移动到右侧
            Backspace   返回buffer list

    L      跳转到tab 列表的搜索模式下

    esc/q   关闭buffer列表

