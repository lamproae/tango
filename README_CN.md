Tango [![Build Status](https://drone.io/github.com/lunny/tango/status.png)](https://drone.io/github.com/lunny/tango/latest) [![](http://gocover.io/_badge/github.com/lunny/tango)](http://gocover.io/github.com/lunny/tango) [English](README.md)
=======================

![Tango Logo](logo.png)

Tango 是一个微内核的Go语言Web框架，采用模块化和注入式的设计理念。开发者可根据自身业务逻辑来选择性的装卸框架的功能，甚至利用丰富的中间件来搭建一个全栈式Web开发框架。

## 最近更新
- [2015-10-23] 更新[renders](https://github.com/tango-contrib/renders)插件，解决模板修改后需要刷新两次才能生效的问题

## 特性
- 强大而灵活的路由设计
- 兼容已有的`http.Handler`
- 基于中间件的模块化设计，灵活定制框架功能
- 高性能的依赖注入方式

## 安装Tango：
    go get github.com/lunny/tango

## 帮助文档
- [快速入门](https://github.com/lunny/tango/wiki/QuickStart)
- [开发文档](https://github.com/lunny/tango/wiki/ZH_Home)
- [API文档](https://gowalker.org/github.com/lunny/tango)

## 使用案例
- [Wego](https://github.com/go-tango/wego)  tango结合[xorm](http://www.xorm.io/)开发的论坛
- [Pugo](https://github.com/go-xiaohei/pugo) 博客
- [DBWeb](https://github.com/go-xorm/dbweb) 基于Web的数据库管理工具
- [Godaily](http://godaily.org) - [github](https://github.com/godaily/news) RSS聚合工具
- [Gos](https://github.com/go-tango/gos)  简易的Web静态文件服务端
- [GoFtpd](https://github.com/goftp/ftpd) - 纯Go的跨平台FTP服务器

## 交流讨论
- QQ群：369240307
- [中文论坛](https://groups.google.com/forum/#!forum/go-tango)
- [英文论坛](https://groups.google.com/forum/#!forum/go-tango)

## 中间件列表

[中间件](https://github.com/tango-contrib)可以重用代码并且简化工作：

- [recovery](https://github.com/lunny/tango/wiki/Recovery) - recover after panic
- [compress](https://github.com/lunny/tango/wiki/Compress) - Gzip & Deflate compression
- [static](https://github.com/lunny/tango/wiki/Static) - Serves static files
- [logger](https://github.com/lunny/tango/wiki/Logger) - Log the request & inject Logger to action struct
- [param](https://github.com/lunny/tango/wiki/Params) - get the router parameters
- [return](https://github.com/lunny/tango/wiki/Return) - Handle the returned value smartlly
- [context](https://github.com/lunny/tango/wiki/Context) - Inject context to action struct
- [session](https://github.com/tango-contrib/session) - [![Build Status](https://drone.io/github.com/tango-contrib/session/status.png)](https://drone.io/github.com/tango-contrib/session/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/session)](http://gocover.io/github.com/tango-contrib/session) Session manager, [session-redis](http://github.com/tango-contrib/session-redis), [session-nodb](http://github.com/tango-contrib/session-nodb), [session-ledis](http://github.com/tango-contrib/session-ledis)
- [xsrf](https://github.com/tango-contrib/xsrf) - [![Build Status](https://drone.io/github.com/tango-contrib/xsrf/status.png)](https://drone.io/github.com/tango-contrib/xsrf/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/xsrf)](http://gocover.io/github.com/tango-contrib/xsrf) Generates and validates csrf tokens
- [binding](https://github.com/tango-contrib/binding) - [![Build Status](https://drone.io/github.com/tango-contrib/binding/status.png)](https://drone.io/github.com/tango-contrib/binding/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/binding)](http://gocover.io/github.com/tango-contrib/binding) Bind and validates forms
- [renders](https://github.com/tango-contrib/renders) - [![Build Status](https://drone.io/github.com/tango-contrib/renders/status.png)](https://drone.io/github.com/tango-contrib/renders/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/renders)](http://gocover.io/github.com/tango-contrib/renders) Go template engine
- [dispatch](https://github.com/tango-contrib/dispatch) - [![Build Status](https://drone.io/github.com/tango-contrib/dispatch/status.png)](https://drone.io/github.com/tango-contrib/dispatch/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/dispatch)](http://gocover.io/github.com/tango-contrib/dispatch) Multiple Application support on one server
- [tpongo2](https://github.com/tango-contrib/tpongo2) - [![Build Status](https://drone.io/github.com/tango-contrib/tpongo2/status.png)](https://drone.io/github.com/tango-contrib/tpongo2/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/tpongo2)](http://gocover.io/github.com/tango-contrib/tpongo2) [Pongo2](https://github.com/flosch/pongo2) teamplte engine support
- [captcha](https://github.com/tango-contrib/captcha) - [![Build Status](https://drone.io/github.com/tango-contrib/captcha/status.png)](https://drone.io/github.com/tango-contrib/captcha/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/captcha)](http://gocover.io/github.com/tango-contrib/captcha) Captcha
- [events](https://github.com/tango-contrib/events) - [![Build Status](https://drone.io/github.com/tango-contrib/events/status.png)](https://drone.io/github.com/tango-contrib/events/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/events)](http://gocover.io/github.com/tango-contrib/events) Before and After
- [flash](https://github.com/tango-contrib/flash) - [![Build Status](https://drone.io/github.com/tango-contrib/flash/status.png)](https://drone.io/github.com/tango-contrib/flash/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/flash)](http://gocover.io/github.com/tango-contrib/flash) Share data between requests
- [debug](https://github.com/tango-contrib/debug) - [![Build Status](https://drone.io/github.com/tango-contrib/debug/status.png)](https://drone.io/github.com/tango-contrib/debug/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/debug)](http://gocover.io/github.com/tango-contrib/debug) show detail debug infomaton on log
- [basicauth](https://github.com/tango-contrib/basicauth) - [![Build Status](https://drone.io/github.com/tango-contrib/basicauth/status.png)](https://drone.io/github.com/tango-contrib/basicauth/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/basicauth)](http://gocover.io/github.com/tango-contrib/basicauth) basicauth middleware
- [cache](https://github.com/tango-contrib/cache) - [![Build Status](https://drone.io/github.com/tango-contrib/cache/status.png)](https://drone.io/github.com/tango-contrib/cache/latest) [![](http://gocover.io/_badge/github.com/tango-contrib/cache)](http://gocover.io/github.com/tango-contrib/cache) cache middleware - cache-memory, cache-file, [cache-ledis](https://github.com/tango-contrib/cache-ledis), [cache-nodb](https://github.com/tango-contrib/cache-nodb), [cache-mysql](https://github.com/tango-contrib/cache-mysql), [cache-postgres](https://github.com/tango-contrib/cache-postgres), [cache-memcache](https://github.com/tango-contrib/cache-memcache), [cache-redis](https://github.com/tango-contrib/cache-redis)

## License
This project is under BSD License. See the [LICENSE](LICENSE) file for the full license text.
