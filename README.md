# 一些技术总结

使用[Whalesnote](https://github.com/ryankolter/whalesnote)创作并批量导出

```
.
├── JavaScript
│   ├── 1.基础知识
│   │   ├── 00.js变量声明.md
│   │   ├── 01.js变量类型.md
│   │   ├── 02.js函数形态.md
│   │   ├── 03.js判断类型（数组为例）.md
│   │   ├── 04.js对原型的理解.md
│   │   ├── 05.js对原型链的理解.md
│   │   ├── 06.js对作用域链的理解.md
│   │   ├── 07.js属性描述对象.md
│   │   ├── 08.js实例_静态_原型方法.md
│   │   ├── 09.js创建对象的5种方式.md
│   │   ├── 10.js检查属性的2种方法.md
│   │   ├── 11.js继承的6种方式.md
│   │   ├── 12.js理解this_call_apply_bind.md
│   │   ├── 13.js异步(Promise、then).md
│   │   ├── 14.js异步(async、await）.md
│   │   ├── 15.js闭包(Closure).md
│   │   ├── 16.js柯里化(Currying).md
│   │   ├── 17.js操作节点的方法.md
│   │   ├── 18.js类的装饰器Decorator.md
│   │   ├── 19.js常见标准错误.md
│   │   └── 20.js的新规范便利.md
│   ├── 2.概念阐述
│   │   ├── 0.同步异步、阻塞非阻塞.md
│   │   ├── 1.事件循环、宏任务、微任务.md
│   │   ├── 2.事件模型、事件委托.md
│   │   └── 3.4种模块规范.md
│   ├── 3.对象方法
│   │   ├── 00.Object的静态方法.md
│   │   ├── 01.Object的原型方法.md
│   │   ├── 02.Array的静态方法.md
│   │   ├── 03.Array的原型方法.md
│   │   ├── 04.Number的静态方法.md
│   │   ├── 05.Number的原型方法.md
│   │   ├── 06.Number的常量属性.md
│   │   ├── 07.String的原型方法.md
│   │   ├── 08.Math的静态方法.md
│   │   ├── 09.Date的方法.md
│   │   ├── 10.RegExp的方法.md
│   │   ├── 11.localStorage的方法.md
│   │   ├── 12.Map操作.md
│   │   ├── 13.BigInt.md
│   │   └── 14.globalThis.md
│   ├── 4.浏览器知识
│   │   ├── 00.浏览器多线程模型.md
│   │   ├── 01.浏览器请求过程.md
│   │   ├── 02.重绘(repaint)和重排(reflow).md
│   │   ├── 03.异步(JSONP、setTimeout).md
│   │   ├── 04.异步(XMLHttpRequest、fetch).md
│   │   ├── 05.压缩（gzip，br）.md
│   │   ├── 06.缓存（四种位置）.md
│   │   ├── 07.缓存（强缓存，协商缓存）.md
│   │   ├── 08.存储（cookie、localStorage）.md
│   │   ├── 09.资源延迟加载.md
│   │   ├── 10.通过CDN引入js库.md
│   │   ├── 11.跨站点脚本攻击（XSS）.md
│   │   ├── 12.跨站请求伪造（CSRF）.md
│   │   ├── 13.V8分代内存回收.md
│   │   ├── 14.内存泄漏.md
│   │   ├── 15.ajax.md
│   │   ├── 16.axios.md
│   │   └── 17.socket.io.md
│   ├── 5.名词区别
│   │   ├── 00.isNaN 和 Number.isNaN.md
│   │   ├── 01.undefined 和 null 和 undeclared.md
│   │   ├── 02.== 和 === .md
│   │   ├── 03.valueOf 和 toString.md
│   │   ├── 04.DOM 和 BOM.md
│   │   ├── 05.defer 和 async.md
│   │   ├── 06.setTimeout 和 setImmediate.md
│   │   ├── 07.encodeURI 和 encodeURIComponent.md
│   │   ├── 08.client 和 offset 和 scroll.md
│   │   ├── 09.函数声明 和 函数表达式.md
│   │   ├── 10.基础类型 和 包装类型.md
│   │   ├── 11.F5 和 Ctrl+F5.md
│   │   └── 12.SSL 和 TLS.md
│   ├── 6.设计模式
│   │   ├── 0.单例模式.md
│   │   ├── 1.工厂模式.md
│   │   ├── 2.适配器模式.md
│   │   ├── 3.装饰器模式.md
│   │   ├── 4.观察者模式 vs 订阅发布模式.md
│   │   ├── 5.策略模式.md
│   │   ├── 6.代理模式.md
│   │   └── 7.享元模式.md
│   └── 7.TypeScript
│       ├── 00.ts简介.md
│       ├── 01.直接使用基本类型.md
│       ├── 02.用接口自定义类型.md
│       ├── 03.class中操作符的使用.md
│       ├── 04.class中接口的使用.md
│       ├── 05.ts泛型.md
│       ├── 06.ts类型检查机制.md
│       ├── 07.ts交叉类型（&）与联合类型（_）.md
│       ├── 08.ts索引类型（keyof）.md
│       ├── 09.ts映射类型.md
│       └── 10.ts类库声明.md
├── README.md
├── babel
│   ├── 0.简介.md
│   ├── 1.基础用法——语法转换.md
│   ├── 2.基础用法——补齐API.md
│   ├── 3.@babel_env不配参.md
│   ├── 4.@babel_env配参.md
│   ├── 5.plugin-transform-runtime.md
│   └── 6.使用webpack.md
└── webpack
    ├── 00.简介.md
    ├── 01.配置.md
    ├── 02.entry入口.md
    ├── 03.output输出.md
    ├── 04.rules引入.md
    ├── 05.填充1——json.md
    ├── 06.填充2——chain【推荐】.md
    ├── 07.使用chain的好处.md
    ├── 08.splitChunks.md
    ├── 09.source-map.md
    ├── 10.babel-loader.md
    ├── 11.css-loader.md
    ├── 12.postcss-loader.md
    ├── 13.less-loader.md
    ├── 14.sass-loader.md
    ├── 15.file-loader.md
    ├── 16.url-loader.md
    ├── 17.html-loader.md
    ├── 18.模板-loader.md
    ├── 19.自定义loader.md
    ├── 20.js-conditional-compile-loader.md
    ├── 21.html-webpack-plugin.md
    ├── 22.mini-css-extract-plugin.md
    ├── 23.optimize-css-assets-webpack-plugin.md
    ├── 24.terser-webpack-plugin.md
    ├── 25.compression-webpack-plugin.md
    ├── 26.brotli-webpack-plugin.md
    ├── 27.webpack-bundle-analyzer.md
    ├── 28.webpack-obfuscator.md
    ├── 29.HashedModuleIdsPlugin.md
    └── 30.模板-plugin.md
```