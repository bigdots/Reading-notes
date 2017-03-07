# DOM 总述

由于 Netscape 和微软分别支持的不同形式的 DHTML 来操作和修改页面，浏览器开始出现互不兼容的局面，于是负责制定 Web 通信标准的 W3C(World Wide Web Consortium,万维网联盟)开始着手规划 DOM。

DOM： 文档对象模型，Document Object Model

DOM是用于 HTML 的应用程序编程接口（API）。它针对 XML 经过扩展而来。

DOM 把整个页面映射为一个多层节点结构。HTML 或 XML 页面中的每个组成部分都是某种类型的节点,这些节点又包含着不同类型的数据。


## DOM级别

1. DOM1级
	主要由俩部分组成：
	+ DOM 核心(DOM Core): 规定如何映射基于 XML 的文档结构
	+ DOM HTML: 添加了针 对 HTML 的对象和方法。
	
2. DOM2级

	在DOM1级的基础上扩充而来，增加了鼠标和用户界面事件、范围、遍历等模块
	
3. DOM3级

	在DOM2级的基础上扩充而来，引入了验证文档和以统一方式加载和保存文档的方法

