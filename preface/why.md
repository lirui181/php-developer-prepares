# 源起

作为一名草根码农，接触 PHP 的时间其实不晚（ASP + Access 虚拟空间满天飞的年代，同等价位标配 MySQL 的 PHP 4.0 空间是众多草根站长的最爱）。

种种原因，重新拿起 PHP 已是多年之后，再次踏入 LA/NMP 阵营真心不是因为 PHP 是世界上最好的语言（无意挑起战争 :P）

DiaoSi 互联网创业起步，

 - Java 平台架构的繁杂（出门野营还是瑞士军刀短小精悍，随身一大箱专业扳手谁用谁知道 :-( ），
 - Python & Ruby 是优雅，但国内社区的小众（小公司招人真心难），
 - C#？（Windows & SQL Server 服务器正版授权咱就直接跪了，还真心不是安全问题，当然前提是您有牛x系统管理员），
 - Perl（上古时代的程序员哪里找，后续接盘侠估计更是欲哭无泪）？ C/C++（程序还没开发出来估计公司就挂了）？
 - Go？ Erlang？Scala。。。（一个是资料少、一个是可能相关支持开发包都还没有或坑太多、再一个您招到人再说。。。）

对比起来，LA/NMP 阵营良好的社区群众基础(程序员多啊)、大量的成功开源项目以及简单直接的高开发效率，作为小型互联网创业公司的我们最后选择了 PHP~

 > 几年以后的今天，尽管在国内 Python、Node.js、Ruby 等社区有了很大发展、也有越来越多的公司即将或正在使用这些技术，但目前从各大公司招聘情况看来 PHP 仍然是大量中小互联网公司的首选后端语言之一。

在这几年的团队组建与培养过程中，注意到一些有意思的现象，

 - 一方面：PHP 社区愈加强调协作&强化性能优势，如 PSR 标准化、 Composer 包管理、 HHVM 的风生水起(PHP 7 也同样值得期待)、 phalcon的不断成熟(向鸟哥的 Yaf 致敬)、性能彪悍的 swoole，
 - 另一方面：关于 PHP 的吐槽不断，比如大家都知道的一些梗。。。

也许是因为 PHP 的简单直接、易上手造成草根程序员太多（因为未接受科班教育的原因，许多草根程序员都会有知识结构不系统的问题），而火爆的互联网行情进一步造成了开发群体高低水平层次的两极分化。 关于如何具体学习、使用 PHP 技术进行 Web 开发，市面上现在已经有了太多代码与资料，然而关于 PHP 研发人员（其实很多内容同样适用于 PHP 之外的其他语言）在项目中的具体实践却缺少相关系统性资料，这也是我尝试总结、整理此文的原因之一。


## 资源

 * [PHP: The Right Way](https://github.com/codeguy/php-the-right-way), [中文版](http://laravel-china.github.io/php-the-right-way/)
 * [PHP Best Practices](https://phpbestpractices.org/), [中文版](http://phpbestpractices.justjavac.com/)

> 强烈建议您直接过一遍上面内容，这样这里的大部分您都可以快速略过，不过我们按照软件开发流程顺序对内容进行组织，同时会有穿插一些中国特色的问题及处理方法 :-) 
