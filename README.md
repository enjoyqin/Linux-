Command(命令模式)                                                        --i(Esc)--                                                 Edit(编辑模式)
在命令模式中打错命令用Esc清除。
保存退出   :wq  
不保存退出 :q!
给文件命名 :wq code.c
打开语法高亮  :syntax on
行号   :set number

上下左右 方向键(Command: H J K L )
向下跳10行：10j 上10行：10k
向下跳一个单词w(word)
往回跳一个单词b(back)
往下翻页，类似于 PageDown ctrl+F (forward)
往上翻页，类似于 PageUp ctrl+B (backward)
跳到88行   88gg
命令模式下 /Node，Node都会高亮，再按n，下一个。Shift+n 上一个


剪切当前行 cc    u(undo) 恢复剪切的行(撤销)
删除2行 c2c
粘贴 p
VISUAL模式  v(类似于win的光标选择，按上下左右)，c(剪切)，p(粘贴) u(撤销)

复制当前行 yy

.vimrc vim的配置文件. 可以搜别人配置好的vimrc
vim ~/.vimrc   当前用户的根目录下
