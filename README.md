# database-interface-doc-management
数据库接口表，在不通系统间的接口内容文档管理

原来的想法是用java做后端，提供restful风格的接口，然后前端使用emberjs调用进行展示。

试用了几个java web框架，如jfinal，jersey等，要不就是太庞大，依赖的jar包有20个，配置复杂！要不就是定制化低，无法满足自己的特定需求。

现在直接抛弃java，使用python的flask和flask-restless，上手快速，开发方便，可以适用于我这个小项目的场景。

不一定要局限于语言啊，不要因为公司用的，自己用的语言都是java，就必须要用java框架。实际上前后端分离后，前端压根不需要管你后端使用什么框架，什么模板解析引擎；后端也压根不会关系前端的处理，不使用servlet或其他服务端技术，就传送格式化数据（json/xml）就可以了。前后端之间的约束就是这个数据协议，发送的数据格式，接受的数据格式。

这样，以后如果要换前端或者后端，也是极方便的。
