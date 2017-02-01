---
layout: post
title: 深入 Vim
cover: cover_hacking_vim.png
date:   2017-01-29 12:00:00
categories: posts
---
Kim Schulz

主页：[深入Vim](https://github.com/M-Mono/Hacking_Vim) / PDF: [A4 版](https://github.com/M-Mono/Hacking_Vim/raw/master/Hacking%20Vim%20(A4).pdf) / Fork: [wuzhouhui](https://github.com/wuzhouhui/hacking_vim)


不知道是谁说过一句话：说世界上的程序员分为三种，一种是使用 Vim 的，还有一种使用 Emacs 的，剩下的都是第三种。由此可见 Vim 的强大程度，可以说，这是一款非常适合程序员使用的编辑器。Vim 的设计哲学是如果你的工作只需要做一次，那没问题，怎么搞都行，如果你的工作是要重复的完成某些工作，则 Vim 总可以帮你找到更少的按键方式来实现相同的目标，为此，Vim 设计了多种模式，常见的模式包括命令模式，编辑模式，命令模式等，这个也是和其他编辑器一个很不相同的地方，可能有些已经有其他编辑器习惯的人有点不太习惯的地方，但是如果将模式熟悉了就可以发现在不同的模式之间切换是很平常的事情，而且带来的好处是更少的按键和更快的输入。

Vim 是 vi 的优秀后裔，虽然vi的后裔中不仅仅包括 Vim，但是 Vim 是实现对 vi 的兼容性最好的编辑器，其他的后裔还包括 STEViE, ELvis, NVi, Vile 等。除了实现对 vi 的兼容性外，Vim 还扩展了很多的功能，包括语法高亮，代码折叠，脚本扩展等等，Packt Publishing 出版社出版的这本书《Hacking Vim》就对 Vim 使用的一些 Tip 作了介绍，在下面的文章中，我将会为大家具体介绍这些 Tip，希望可以给你在使用 Vim 的过程中带去一点帮助。介绍的内容包括定制篇，移动篇，效率篇，格式篇和脚本篇。
