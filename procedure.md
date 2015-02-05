编写步骤如下
---------
有点长，我们已尽量精简，希望大家花点耐心阅读完。  

###一. 准备
- 进群后  
按照群公告修改群昵称，以想分析的库开头。群里发下自己的 Github 帐号并 @Trinea 以添加权限  
- 填写时间计划表  
读完本文档后，根据自己的时间安排，填写 [时间计划表](./schedule.md)，并在编写的每个阶段完成后更新时间计划表 

###二. 编写该开源库的使用示例
到 [android-open-project-demo](https://github.com/aosp-exchange-group/android-open-project-demo) 项目下新建文件夹，用于后续上传该开源库使用示例工程代码  
- 该文件夹以`开源库名-demo`命名，全小写，单词间用`-`连接。如果已有该文件夹，则以`开源库名-demo-${GitHub 用户名}`命名，如`event-bus-demo-trinea`；  
- 示例工程要求覆盖到该开源项目所有功能，不允许拷贝官方 Demo；  
- 若没有自己的 Code Format 文件，使用 [common](./common) 文件夹下 code format，code template 文件；  
- 文件夹下需要有名为 apk 的子文件夹，用于存放可运行 APK 文件；  
- 文件夹下需要有名为 README.md 的介绍文件，其中包含以下内容。  
(1). Demo Download  
(2). Screenshot 截图可使用 [licecap](http://www.cockos.com/licecap/)  
具体可参考：[EventBus Demo ReadMe](https://github.com/android-cn/android-open-project-demo/tree/master/event-bus-demo)  

**完成时间**  
- 示例工程需要在认领后`三天内`完成全部提交，中间每天尽量有一定的提交  
  
###三. 编写原理文档  
到 [android-open-project-analysis](./) 的`master`分支下新建文件夹  
####3.1 文件夹规范  
- 该文件夹以`开源库名`命名，全小写，单词间用-连接。如果已有该文件夹，则以`开源库名-${GitHub 用户名}`命名，如`event-bus-trinea`；  
- 从 [common](./common) 文件夹下拷贝模板文件 README.md，复制到上面的文件夹中，所有内容在 README.md 中用 [Markdown](./common/tool#1-markdown) 编写。如果内容较多可分多个 md 文件，但 README.md 为总体的概括文件；  
- 文件夹下可有名为`image`子文件夹存放相关流程图等图片，`uml`子文件夹存放 uml 文件。  

####3.2 文档需包含的模块及预计时间  
具体编写的模块及各模块预计耗时请参考：[common README](./common/README.md)。  

####3.3 公共技术点及工具  
我们整理了一份公共技术点，如果你分析的库涉及到请直接链过去，以节省精力，地址：[开源分析公共技术点](./tech)  
我们整理了一份你可能需要用到的工具库，地址：[Tool](./tool/README.md)   

项目中遇到的问题可汇总到 [项目过程中问题](./problem.md)，其他问题及建议及时在 Q 群里反馈  

**希望大家都能在分析的过程中收获很多，同时分析文档能为其他开发者带来便利，一起加油！**   
