# 最近给团队新同学分享的git markdown

## 背景
最近给团队新同学分享了关于`git`、`markdown`的入门及学习。下面是分享`ppt`的内容，其中就关于我自己在学习使用的感受谈几点想法。

## 你真的会用git了吗？
我大概是在15年开始接触`git`,估计和绝大部分人一样，作为小白一开始看的是第三方的博客和文章。实际上，只要跟着敲和练几遍，你发现，`git`竟然这么快就入门了！为此，心中便有了意淫的想法，心想：哎呀，`git`也不是很难吗！其实，这中间有个很大的问题忽略了，直到后面我接触`linux`后才**后悔不已**，当初的想法是**多么幼稚，多么愚钝**。

刚开始学习的时候，就有一种急于求成的想法，想快速了解，快速搞定。**囫囵吞枣乱学一通**，打开了第三方的博客和文章后，里面有说关于学习`git`更简单，更直接的方式是图形化。估计新手看到这个，估计是相当兴奋：有GUI,还要啥自行车（记什么命令行，那么多，怎么记得住）。就这样，我带着好奇心理开始使用了`SourceTree`工具，因为当时在做app相关工作，基本都是基于本地化操作，我就因为好奇心理，使用了GUI工具将近一年。

之后，开始接触服务端相关工作，因为环境发生了极大的变化，服务端开发都基于开发机（Linux环境）操作，我在上手项目对`git`进行版本控制后，发现根本没有图形化工具这个东西，完蛋了，我基本上束手无策。等于我离开了GUI工具，我几乎是不会敲git命令，我之前本以为学会了git的想法一直是自己在意淫。当天，我又重拾起`git`，通宵达旦又将官方文档翻起了阅读。从那以后：我发誓，至此再也不碰GUI工具。

工作有几年了，在经历的团队中，依然能发现有些同学，重度依赖GUI工具不使用git命令行工具的，上了Linux环境操后，几乎对于gi的操作无从下手，甚至不知道`Stage Area`（暂存区）这个定义，导致在操作`git`命令行时，乱敲一通。最终不知怎么解决，又回到原始办法：重新`google`或`baidu`,完全浪费时间。

可能自己比较幸运，很早意识到这个问题，这期间也吃了很大的亏，让我对于后期学习新知识有了一个比较直接的认识，官方文档才是通向大门的唯一直径。

#### 就想上面这个问题谈几点感受：
* 依赖GUI的工具的同学，不是因为学不会，而是因为懒得记命令，认为GUI用鼠标点一点更快、更舒服。
* 学习方法不对。可能第一次学习git接触的是第三方博客，而不是官网。可能博客上推荐说使用GUI更方便，你也将信将疑，尝试心态试了GUI，“发现真是真么回事！”。其实官网更权威。
* 可能因为环境的变化，非常打击到你的时候，才会意识到，之前做的是在**浅尝辄止**。
* 以上三点，基于前提还是，学习新东西，还是想**寻找捷径**，不想**按部就班**

## 关于issues的使用感受
现在团队之间的信息写作来源多个平台wiki,jira,git。导致`jira`和`wiki`对于需要信息和反馈及信息追踪方面是有所缺失的。有时候，大家很想记住刚才说的信息任务，但是因为有更紧急,更重要的事情，让刚才的信息被其他重要信息冲淡，随后抛之脑后了。因为信息不能被**持续跟踪**和**及时反馈**，导致当初建立信息的任务的结果是缺失的。

**"我们缺乏的不是制定信息的任务，而是缺少好的信息协作流程"**

上面这段话，是我在自己使用`issues`工作感受中得出来的。下面给大家介绍下为什么要利用好`issues`工具
1. issues可以让信息有：开始->过程->完成（closed）
2. issues可以Assignee制定的人来协作
3. issues可以利用labels来给任务贴标签
4. issues可以利用milestones可以来给团队制定计划和任务
5. issues还可以评论和交流，对话式交换观点
6. issues是公开的，因为创建了，不能删除
7. issues默认使用markdown 编写，简单

## markdown
自己因为平时的文档编写都是基于markdown编写，包括在`github`,`gitlab`上协作，几乎都离不开`markdown`。不管是在写作文档还是在写邮件，我注意到，觉大部分同学对于文字排版几乎是**将就**的。
没有意识到一篇好的文章或文字表达，不仅仅是在于文字的力量，外在的排版更能直接吸引到读者的眼球。`markdown`恰好解决了这些麻烦，你不需要关于排版，文字大小，因为书写简单，你可以花几分钟就可以掌握语法，写出一篇优雅的排版。哈哈，非常高兴地是，因为和周边同学的“安利”，他们也意识到这个问题，最近邮件文字表达，对于邮件的书写有了明显改善。我觉得学习`markdown`更直接的原因，是和生态对接。正如我们学习英语一样，使用`markdown`更直接参与生态、开源平台的交流。

## 以上，是我的个人感受，你呢？

---

**下面是我在团队中分享的ppt，分享给大家。** 😝

![git_markdown.001.jpeg](git_markdown/git_markdown.001.jpeg)

![git_markdown.002.jpeg](git_markdown/git_markdown.002.jpeg)

![git_markdown.003.jpeg](git_markdown/git_markdown.003.jpeg)

![git_markdown.004.jpeg](git_markdown/git_markdown.004.jpeg)

![git_markdown.005.jpeg](git_markdown/git_markdown.005.jpeg)

![git_markdown.006.jpeg](git_markdown/git_markdown.006.jpeg)

![git_markdown.007.jpeg](git_markdown/git_markdown.007.jpeg)

![git_markdown.008.jpeg](git_markdown/git_markdown.008.jpeg)

![git_markdown.009.jpeg](git_markdown/git_markdown.009.jpeg)

![git_markdown.010.jpeg](git_markdown/git_markdown.010.jpeg)

![git_markdown.011.jpeg](git_markdown/git_markdown.011.jpeg)

![git_markdown.012.jpeg](git_markdown/git_markdown.012.jpeg)

![git_markdown.013.jpeg](git_markdown/git_markdown.013.jpeg)

![git_markdown.014.jpeg](git_markdown/git_markdown.014.jpeg)

![git_markdown.015.jpeg](git_markdown/git_markdown.015.jpeg)

![git_markdown.016.jpeg](git_markdown/git_markdown.016.jpeg)

![git_markdown.017.jpeg](git_markdown/git_markdown.017.jpeg)

![git_markdown.018.jpeg](git_markdown/git_markdown.018.jpeg)

![git_markdown.019.jpeg](git_markdown/git_markdown.019.jpeg)

![git_markdown.020.jpeg](git_markdown/git_markdown.020.jpeg)

![git_markdown.021.jpeg](git_markdown/git_markdown.021.jpeg)

![git_markdown.022.jpeg](git_markdown/git_markdown.022.jpeg)

![git_markdown.023.jpeg](git_markdown/git_markdown.023.jpeg)

![git_markdown.024.jpeg](git_markdown/git_markdown.024.jpeg)

![git_markdown.025.jpeg](git_markdown/git_markdown.025.jpeg)

![git_markdown.026.jpeg](git_markdown/git_markdown.026.jpeg)

![git_markdown.027.jpeg](git_markdown/git_markdown.027.jpeg)

![git_markdown.028.jpeg](git_markdown/git_markdown.028.jpeg)

![git_markdown.029.jpeg](git_markdown/git_markdown.029.jpeg)

![git_markdown.030.jpeg](git_markdown/git_markdown.030.jpeg)

![git_markdown.031.jpeg](git_markdown/git_markdown.031.jpeg)

![git_markdown.032.jpeg](git_markdown/git_markdown.032.jpeg)

![git_markdown.033.jpeg](git_markdown/git_markdown.033.jpeg)

![git_markdown.034.jpeg](git_markdown/git_markdown.034.jpeg)

