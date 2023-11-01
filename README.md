# academic-writing-guide
 一些关于写论文的教程,防止犯一些低级错误

## 内容
- [Check List](#check-list)
  - [图表](#图表)
  - [正文](#正文)
  - [摘要](#摘要)
  - [参考文献](#参考文献)
- [资源教程](#资源教程)
- [其他资源链接集合](#其他资源链接集合)


## Check List

### 图表
 - 考虑打印效果。
   - 颜色。考虑黑白印刷的效果。正常的发表印刷都是黑白打印。所以尽量不要用红黄色，用灰色来区分。
   - 清晰度。如果图片是截图，需要确认清晰度问题。可以自己尝试论文打印成pdf，看看能否看清楚图表。
 - 布局
   - 圆圈和文字的布局效果至少让读者清楚看到其中的字，而不是部分被遮盖。
   - 图表之间，图表和标题、正文，不存在互相遮挡。
 - 字体
   - 文中的所有图中字体统一。最好能和论文正文字体统一。
   - 字体大小粗细适中，能让人很清楚不费力的看清楚。
   - 同一张图上的相同位置类型的字体大小粗细统一。比如流程图上的方框内字体粗细大小一致。

 - 标题
   - 中英文对照（如软件学报的的投稿需要同时有英文和中文标题），需要确保两者能对应，并且术语统一
   - 英文标题，实词首字母大写，虚词如（如of，in）首字母不需要大写，例如：![image](https://github.com/FudanSELab/academic-writing-guide/assets/10709391/a0978008-134b-48f4-8e13-404e9945d173)

   
 - 边框、线条
   - 如果是自己画的图，边框和线条尽量保证粗细样式统一，并且保证打印效果。
   - 如果是文字要放在线段上做说明，比如类似表示数据传递，输入输出，文字尽量放在线段上。以下是不好的做法，文字放在了线段下面![1690889303138](https://github.com/FudanSELab/academic-writing-guide/assets/10709391/370d266a-d7f8-44a2-91e1-205f6108297f)

   
 - 内容
   - 图片表格中是否有拼写错误，因为图表是最直接能看到的，存在错误很致命
   
### 正文
 - 引用检查
   - 检查每个引用论文、图片、表格是否准确
   - 检查引用章节的序号是否准确
   - 检查论文中引用的数字和结论是否准确（例如introduction中引用实验的最终指标）
   - 引用标注遗漏检查，如“与Liu等人的工作相似,”这里“Liu等人”后应有文献标注
   - 文章介绍各种背景知识的文字、公式、图表等，特别注意引用标记，没有标注的地方尽量用自己的语言介绍而不是直接拷贝其他文献的文字。
   - 直接引用文本内容要用引号区分
   - 引用标在等人后面，如“Xie等人[3]”和“谢等人[3]”,中文文献用中文姓，英文文献用英文姓
 - 标点
   - 统一全文的标点符号，比如英文写作统一成英文标点，中文写作统一成中文标点，不要混用。比如同时使用中文句号“。”和英文句号“.”
   - 标点符号是否使用准确。
     - 应该使用句号的地方不要使用逗号
 - 术语统一，需要建立一个统一的术语表，全文中应该使用相同术语指代同一个东西。
   - 例如“实验标签”还是“试验标签”，全文中应该只出现一个表达
   - 中英文统一
   - 大小写统一（如一个地方用AI KG， 另外的地方就不能使用 ai KG）
   - 先定义再使用，对于一个术语，特别是英文的，第一次出现应该先定义，说清楚是什么，后面才能使用，比如Stack Overflow。
 - 通读全文
   - 通读全文的每一句，至少保证语言通顺，没有语法错误
   - 英文检查
     - 介词，单复数，冠词使用是否正确
     - 时态是否前后统一 
     - 是否里面有超出宽度
     - 是否存在两个单词连在一起的情况
     - 涉及到的数字需要重新计算一遍，确保正确，不互相矛盾
 - 中英文混杂问题
   - 如果是中文写作，中英文混杂尽量避免，能用中文尽量用中文，比如“Top-K标签列表”改成“前K个标签列表”
   - 英语专业术语注意大写，如JDK,JRE，而不是jdk，jre。
 - 图文一致
   - 所有图片、表格、公式在正文中应该都被引用到，至少有一句、一段话来介绍其中的内容。不能光展示一张图片，而文章中完全没有介绍。
 - 步骤概览图
   - 不同形状表示不同含义：比如矩形表示一个步骤，应该是动作（如Feature Extraction）；圆柱体表示可持久化数据（如Knowledge Graph）；
   - 图中步骤和文章中标题、后续描述要一一对应。
 - 段落结构编号
   - 段落结构编号风格应该统一。而且不统一。 A）B）C）和1）2）3）多种风格混用不行
 - 标题
   文章的章节标题是否有错误
 - 格式统一
   对于同一类东西的格式是否前后统一， 比如我们的pattern都是用斜体的，是否存在着没有使用斜体的pattern
 
### 摘要
 - 中英对照
   摘要如果是中文英文对应的，需要逐句检查，不能是直接翻译软件翻译的
   - 否每一句中文英文能对照
   - 是否存在语法问题（缺少主语）
   - 表达是否自然
   - 涉及的术语是否用词准确
   - 标点符号使用是否正常（比如该使用逗号的地方使用句号）

### 相关工作与背景技术 
 - 介绍完相关工作、背景要加一句话说明与自己工作的联系、异同。不能罗列现有的技术、相关工作。

### 方法章节
 - 介绍方法应该是一个通用的技术框架，不要是一个具体的技术实现。比如下面：。50,100 不能写死在方法里面，要描述成一个通用的方法，可以写成n,m,k,这种可变参数，然后后面再说实际实现的时候取了50，100. 并且要加上原因。
![image](https://github.com/FudanSELab/academic-writing-guide/assets/10709391/4a1307a6-1b36-42fe-ab51-e6b5533514dc)



### 参考文献
 - 检查参考文献的格式是否统一
 - 参考文献尽量从统一来源获取，英文的dblp（dblp没有就去谷歌学术），中文的知网。
 - 参考文献的格式要求是否和模板要求一致
 - 检查引用是否存在重复的参考文献的情况

# 资源教程
## Latex教程
 - [latex-advice](https://github.com/dspinellis/latex-advice), Advice for writing LaTeX documents.
 
## 视频教程
- 清华大学王翔宇论文写作公开课-工科论文写作
  讲得非常详细和基础，推荐新手阅读
  - [论文文献检索、阅读、引用](https://www.bilibili.com/s/video/BV137411j78R)

- [软件工程领域论文写作套路](https://github.com/stan6/se-paper/blob/main/README.md),一个老师录的两个视频，跟学生分享一些写SE文章的套路，希望学生写作能有所改进(由于有国际生，视频是英语的)
 - [Leadership Lab-- 芝加哥大学科研方法课 全集](https://www.bilibili.com/video/BV1zg4y1q7GT)
 - [LEADERSHIP LAB: The Craft of Writing Effectively](https://www.bilibili.com/video/BV1wz4y1o7UW), [youtube有字幕版本](https://www.youtube.com/watch?v=vtIzMaLkCaM&list=RDLVvtIzMaLkCaM&start_radio=1)， 很风趣幽默
 - [知乎论文写作视频合集](https://zhuanlan.zhihu.com/p/92297191)
   -  [斯坦福SCI论文写作课程(Writing in the Sciences)-中英字幕
](https://www.bilibili.com/video/BV1zv41177JQ?from=search&seid=3407649266167868195&spm_id_from=333.337.0.0)

## 文字教程
 - [知乎专栏-SCI是怎么炼成的](https://zhuanlan.zhihu.com/p/36794864)
   - https://zhuanlan.zhihu.com/p/36794864 
 - 周志华教授：如何做研究与写论文？,[公众号](https://mp.weixin.qq.com/s/01ciF3uNKAMXWML2EeYwvQ), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/research_and_paper_zhou_zhihua_2007_ppt.pdf)
 - 厦门大学林子雨博士的报告《论文是怎样炼成的》，共125页ppt，[公众号](https://mp.weixin.qq.com/s/hZ1bNssbSOCqU_ixTKgtrg), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/linziyu-how-to-do-research-2011.pdf)
 - 北大读博手记——怎样完成自己的博士生涯 [公众号](https://mp.weixin.qq.com/s/VEIbVimS-fTyPtDqxl7tag), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/How-to-complete-your-PhD-career.pdf)
 - 科研论文撰写策略 [公众号](https://mp.weixin.qq.com/s/u8pCkdHKzSQZglB2eLNZVA), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/Research-paper-writing-strategy.pdf)
 - 搞科研必须了解的五十个学术网站 [公众号](https://mp.weixin.qq.com/s/qnRRzoV-F1Uh0uSyocjsjg), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/research-websites.pdf)
 - 学术论文投稿与返修（Rebuttal）分享 [公众号](https://mp.weixin.qq.com/s/DWRIImmUmqbNprMzcFJD2g), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/how-to-Rebuttal.pdf)
 - 写作课堂（一） [公众号](https://mp.weixin.qq.com/s/lpyH-BAOUX9trfi4MYR8rg), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/writing-course.pdf)
 - How to Write and Publish a Scientific Paper [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/How_to_Write_and_Publish_a_Scientific_Paper.pdf)
 - How to Write Good a Scientific Paper [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/how-to-write-a-good-scirentific-paper.pdf)
 - Editing Your Thesis [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/Editing-Your-Thesis.pdf)
 - How to write a good review? - CVPR 2020 Tutorial [公众号](https://mp.weixin.qq.com/s/CpICiPiBmX2l4kDdFcJz4Q), [网页](https://zhuanlan.zhihu.com/p/156994751), [pdf](https://sites.google.com/view/making-reviews-great-again/)
 - How to write a good rebuttal? - CVPR 2020 Tutorial [pdf](https://drive.google.com/file/d/1V8V__zQYCOskD1y1-9L-UWgNDtBHGJ9t/view)
 - How to write a good paper? - CVPR 2020 Tutorial [pdf](https://drive.google.com/file/d/1sE4ZCHkU65J6ZFjOK4dWGIiuPygkM6ZW/view)
 - How are reviews used in the decision process? - CVPR 2020 Tutorial [pdf](https://drive.google.com/file/d/1OEaiHnGi8eKvPQ6HS8Trb_oMKV600p6o/view) [pdf](https://drive.google.com/file/d/1N6BHIOR51R5mcwQ7Qsgv2tpGaV_rfXrF/view)
 - Writing Tips for PhD Theses, 博士论文写作技巧 [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/phd-writing-talk.pdf)
 - 综述论文的六个写作模版 [公众号](https://mp.weixin.qq.com/s/Zw-L_RRKPO17mFJqklKNTw), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/survey-templates.pdf)
 - 国内唯一ACL最佳论文得主冯洋：冲击最佳论文需要知道的事情 [公众号](https://mp.weixin.qq.com/s/xQTsJJrRx7RGSIPOge-gFA), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/how-to-get-best-paper.pdf)
 - 保持高效论文写作的10个原则！ [公众号](https://mp.weixin.qq.com/s/Xs9OrDPu9B8V0SMkwmJZwQ), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/10-tips-for-writing-paper.pdf)
 - 【人大赵鑫老师】如何以初学者角度写好一篇国际学术论文？,很清楚详细,推荐 [公众号](https://mp.weixin.qq.com/s/Kb9Vnl3gpYWsOC-AY1TjTw), [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/write-an-international-academic-paper-from-a-beginner-perspective.pdf)
 - 吐血整理：论文写作中注意这些细节，能显著提升成稿质量,[公众号](https://mp.weixin.qq.com/s/QoZbJxeRcrqZC6rV06zmRg) 
 - 机器翻译学术论文写作方法和技巧：清华大学刘洋老师在CWMT-2014上做的经典报告，以机器翻译的视角，从选题开始，给大家讲解了论文写作的方法和技巧。[PPT](
http://nlp.csai.tsinghua.edu.cn/~ly/talks/cwmt14_tut.pdf)
 - 如何端到端地写科研论文?：复旦大学的邱锡鹏老师在CCL-2018的student workshop上做的报告。[PPT](https://xpqiu.github.io/slides/20181019-PaperWriting.pdf)
 - 论文写作的易读性原则：刘一佳同学， 阿里巴巴达摩院的阿里星大神，在NLPCC-2018上做的报告。[PPT](http://yjliu.net/cv/res/2018-08-19-nlpcc-sws.compressed.pdf)
 - 哥伦比亚大学的Henning Schulzrinne老师的一些学术随笔，其中也有一个论文写作的collection。[网址](http://www.cs.columbia.edu/~hgs/etc/writing.html)
 - 哈佛大学的Whitesides老师从写提纲的角度切入讲解如何撰写学术论文。[链接](https://onlinelibrary.wiley.com/doi/pdf/10.1002/adma.200400767)
 - 如何让摘要吸引人？Nature论文摘要模板值得收藏。[链接](https://zhuanlan.zhihu.com/p/158574876)
 - 支付宝研究员王益的建议：“学好语文，才能写好代码”（很多观点对写论文同样适用）[链接](https://zhuanlan.zhihu.com/p/157243326)
 - Academic PhaseBank [pdf](https://github.com/FudanSELab/academic-writing-guide/blob/main/resources/Academic-Phrasebank-2021.pdf)
## 其他资源链接集合
 - [PaperWriting](https://github.com/wangdongdut/PaperWriting),一个别人的关于学术写作的资源收集
 - [research-method](https://github.com/secdr/research-method), 围绕以下内容有收集各种资料讲义
    - how to think: 如何寻找适合自己的论文观点或者议题；
    - how to search: 有了议题了如何去查找已有的研究成果和相关工作；
    - how to write: 如何去写一篇论文；
    - how to submit: 论文写好了如何去投稿；
    - how to revise: 收到修改意见后如何去回复和修改论文；
    - how to use template: 写作中会遇到各种文档的套词；
    - how to presentation: 会议论文如何做演讲。
## 类似教程
  - [Paper-Writing-Tips](https://github.com/MLNLP-World/Paper-Writing-Tips), 很多初学者同学在投稿的时候经常会出现一些共有的小错误，为了节省大家的时间和帮助大家能够尽快的定位一些小的问题。本项目总结了我们在自己投稿过程中的经验和一些身边老师同学的投稿经验，包含。
    - 写前必看：包含一些常见的错误，每个错误均配有例子，可以在动手写论文之前快速浏览。
    - 终稿必查：包含一些例子，方便快速定位是否自己的论文有错误。
    - 百家之言：整理了一些网络上公开的写作资源（并不完全，欢迎补充），方便大家系统学习。
 - (CS writing Style )[http://www.cs.columbia.edu/~hgs/etc/writing-style.html]
## 工具
 - [phrasebank](https://www.phrasebank.manchester.ac.uk/compare-and-contrast/)，常用的高级的英语论文写作的句式，比如如何对比相关工作、如何阐述实验结果。
 - [grammarly](https://app.grammarly.com/), 一个免费的工具，能够对英语文本进行语法检查和修复，包括冠词误用等情况，建议自己写的英语使用这个工具检查一遍。
 - [writefull](https://www.writefull.com/), 一个免费的工具，能够对英语文本进行语法检查和修复和句式的建议，可以在word中使用。
 - [wordvice.ai](https://wordvice.ai/cn),一个免费在线检查工具，能够对英语文本进行语法检查和修复
