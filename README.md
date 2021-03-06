# OpenGL学习脚印

1.[nanosuit model demo](http://img.blog.csdn.net/20161004121046497)

-------

# 致谢

首先，感谢广东工业大学吴伟明老师，是他让我第一次听说OpenGL这个API，以后逐渐产生兴趣。
再次，要非常感谢[Joey de Vries](http://joeydevries.com/#home)面向初学者的在线教程[www.learnopengl.com](http://www.learnopengl.com)，他的教程通俗易懂，给初学者减轻了很多负担。

本笔记的内容，整理自以下几个主要参考资料，并通过自己实践提炼而成：

- [www.learnopengl.com](http://www.learnopengl.com)
- [www.opengl-tutorial.org](http://www.opengl-tutorial.org/)
- [open.gl](https://open.gl/)
- [OpenGL Wiki](https://www.opengl.org/wiki)
- [Lighthouse3d.com](http://www.lighthouse3d.com/)
- [ww.informit.com Graphic Programming](http://www.informit.com/articles/index.aspx?st=60188)
- [http://www.geeks3d.com/](http://www.geeks3d.com/)

在笔记中对于图片或者例子出处，均作了引用说明，对原作者表示深深谢意。

-------
# 书写笔记的初衷

这份笔记是学习和使用OpenGL过程中的一份总结笔记。
学习的过程，主要是选定一个主题，然后搜索有价值的参考资料，然后动手实践，最后整理成文。
书写本笔记的目的在于：

- 保持自己对图形编程的兴趣，同时保持一定节奏学习，避免过快或者过慢两个极端。
- 以初学者的身份记录下学习过程中的点滴经验，供初学者交流和学习。

具体的讲解请见博客：http://blog.csdn.net/ziyuanxiazai123/article/category/2107037

**对代码的建议、纠错，请在博客下方留言**。

-------
# 目前代码适用情况

作为初学者，本代码主要以 windows + visual studio + C++ 作为开发环境，
同时选用[GLFW + GLEW + SOIL + AssImp](https://github.com/wangdingqiao/noteForOpenGL/tree/master/libraries) 等作为OpenGL的第三方库文件。

选用这些平台和语言的原因在于，作为初学者要尽量屏蔽语言相关、机器相关的细节，
重点放在动手实践上，而不是把时间浪费在Linux下驱动程序安装, c++11新特性，python或者java的OpenGL语言绑定等无关细节上面。

同时在书写代码时，本文例子有些地方没有涉及到细致的函数封装、错误处理、性能优化等内容，这些因素在具体实现应用时需要考虑，但是作为初学的入门例子，没有把这些复杂的细节加入。

另外，作为一个入门实践笔记，主要目的是能快速直观的理解某个概念和原理，因此部分API细节和底层实现可能没有一一详细探讨，这一点可以在后面具体实现应用时参考API手册或者红宝书和蓝宝书。


