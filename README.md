## Diary

#December 8, 2016

###Cookie 快速理解

Cookie就是服务器暂存放在你计算机上的一份记录（文件），好让服务器用来辨认你的计算机

当你在浏览网站的时候，Web服务器会发送并保存一份记录（文件）放在你的计算机上

Cookie 会帮你在网站上所打的文字或是一些选择，都记录下来。当下次你再访问同一个网站

Web服务器会先看看有没有它上次留下的Cookie资料，有的话，就会依据Cookie里的内容来判断使用者并送出特定的网页内容给你

Cookie的使用很普遍，许多提供个人化服务的网站都是利用Cookie来辨认使用者，以方便送出使用者量身定做的内容

像是Web接口的免费E-mail网站，都要用到 Cookie

Cookie中记载的资料相有限，Cookie是安全的

网站不可能经由Cookie获得你的E-mail地址或是其它私人资料，更没有办法透过Cookie来存取你的计算机

但是如果你实在不喜欢Web服务器乱丢饼干(Cookie)到你的计算机，当然可以让浏览器拒绝网站存放Cookie到你的计算机

只要在IE的“工具”菜单下选择“Intertnet选项”的“安全”，按自定义级别，将Cookie部分设为关闭，按确定，关闭浏览器，再重新启动浏览器即可

当你关闭Cookie之后，很多网站的个人化服务功能很可能也不能再使用了

#December 9, 2016

###Python 爬虫入门

爬虫是一门很优秀的技术，给我的感觉就是可以用很简单的逻辑实现很强大的功能。

这里说一下Python爬虫的明确的逻辑：

从网页上抓取数据大致分三步

1.模拟浏览器访问，获取HTML源代码

2.通过正则匹配获得标签中的一些内容

3.将获取到的内容写到文件中

而后我们可以拥有一些扩展：

4.将我们收集到的信息生成数据报告，进行数据分析，生成图表等东西

5.生成EXE文件，使其可以直接执行

6.生成图形化界面，使其用户体验更友好

感谢让我入门并成功执行的网址
>http://blog.csdn.net/bo_wen_/article/details/50868339

#December 12, 2016

###JavaScript 笔记
因为网景开发了JavaScript，一年后微软又模仿JavaScript开发了JScript，为了让JavaScript成为全球标准，几个公司联合ECMA（European Computer Manufacturers Association）组织定制了JavaScript语言的标准，被称为ECMAScript标准。

所以简单说来就是，ECMAScript是一种语言标准，而JavaScript是网景公司对ECMAScript标准的一种实现。

最新版ECMAScript 6标准（简称ES6）已经在2015年6月正式发布

JavaScript严格区分大小写，如果弄错了大小写，程序将报错或者运行不正常

这个特殊的Number与所有其他值都不相等，包括它自己：  NaN === NaN; // false

唯一能判断NaN的方法是通过isNaN()函数：  isNaN(NaN); // true
