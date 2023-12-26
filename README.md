# 一些技术总结

1. 读过的好书 —— Books

2. 前端技术 —— JavaScript、HTML、CSS、webpack、babel

3. 后端技术 —— Linux、Nodejs、PostgreSQL、Redis、Nginx、Docker、ES

4. 系统设计 —— SystemDesign

5. 工具 —— Git、Vim

```
.
├── 00_Books
│   ├── 0.计算机基础.md
│   ├── 1.前端书籍.md
│   └── 2.后端书籍.md
├── 01_JavaScript
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
├── 02_HTML
│   ├── 1.HTML标签
│   │   ├── 00.模板-head_body.md
│   │   ├── 01.容器-div_span.md
│   │   ├── 02.图片-img.md
│   │   ├── 03.图片点击-map.md
│   │   ├── 04.超链接-a.md
│   │   ├── 05.列表-ol_ul.md
│   │   ├── 06.表格-table.md
│   │   ├── 07.输入-input.md
│   │   ├── 08.表单-form.md
│   │   ├── 09.下拉选择-select.md
│   │   └── 10.小标签-br_hr_p.md
│   ├── 2.HTML5
│   │   ├── 0.简介.md
│   │   ├── 1.新增-结构元素.md
│   │   ├── 2.新增-其他.md
│   │   ├── 3.改良-表单元素.md
│   │   ├── 4.改良-其他.md
│   │   └── 5.公共属性.md
│   └── 3.HTML技术
│       ├── 0.文件上传.md
│       ├── 1.Blob对象.md
│       ├── 2.本地存储.md
│       ├── 3.音频视频.md
│       └── 4.canvas标签.md
├── 03_CSS
│   ├── 1.css基础
│   │   ├── 00.三种像素.md
│   │   ├── 01.标准单位.md
│   │   ├── 02.css特性.md
│   │   ├── 03.css引用.md
│   │   ├── 04.css选择器.md
│   │   ├── 05.命名规范.md
│   │   ├── 06.书写规范.md
│   │   ├── 07.注释规范.md
│   │   ├── 08.表单.md
│   │   ├── 09.视口计算.md
│   │   └── 10.容易遗忘点.md
│   ├── 10.技巧代码
│   │   ├── 00.绘制-三角形.md
│   │   ├── 01.绘制-扇形(待完成).md
│   │   ├── 02.动画-盒子移动(待完成).md
│   │   ├── 03.动画-滚动的轮子.md
│   │   ├── 04.动画-地球绕太阳.md
│   │   ├── 05.动画-逐帧动画实现.md
│   │   ├── 06.动画-图片圆形框放大.md
│   │   ├── 07.动画-加载中.md
│   │   ├── 08.自定义-普通按钮.md
│   │   └── 09.自定义-圆形对勾按钮.md
│   ├── 11.项目需求
│   │   ├── 0.【需求】全局设置.md
│   │   ├── 1.【需求】插入顶部宣传图，并自适应手机屏幕.md
│   │   ├── 2.【需求】方框内要配置背景色图，并能做出向下凸起效果.md
│   │   ├── 3.【需求】方框底部插入蒙层和按钮.md
│   │   ├── 4.【需求】上面视频固定，下面剩余部分可滚动.md
│   │   ├── 5.【需求】做一套关于成功和失败的提示弹窗.md
│   │   ├── 6.【需求】cover方框内放img图片，并绝对定位一个tag标签.md
│   │   ├── 7.使用 伪类和伪元素 实现的需求.md
│   │   └── 8.使用 选择器 实现的需求.md
│   ├── 2.css属性
│   │   ├── 0.display.md
│   │   ├── 1.position.md
│   │   ├── 2.float.md
│   │   ├── 3.文本效果.md
│   │   ├── 4.文本布局.md
│   │   ├── 5.文本换行.md
│   │   └── 6.@media.md
│   ├── 3.css问题
│   │   ├── 0.flex_1 无效问题.md
│   │   ├── 1.双层flex嵌套问题.md
│   │   ├── 2.外边距重叠问题.md
│   │   ├── 3.body存在8px外边距问题.md
│   │   ├── 4.父元素坍塌问题.md
│   │   └── 5.span不继承强制颜色问题.md
│   ├── 4.css代码
│   │   ├── 0.文字省略.md
│   │   ├── 1.单行文字垂直居中.md
│   │   ├── 2.勾选框垂直居中.md
│   │   ├── 3.文字或图片水平居中.md
│   │   ├── 4.按钮水平居中.md
│   │   ├── 5.对元素进行放大缩小.md
│   │   ├── 6.两段文字强制换行.md
│   │   ├── 7.多行文字两行定宽显示.md
│   │   └── 8.父方框内插入图片到最右侧居中.md
│   ├── 5.css3
│   │   ├── 00.简介.md
│   │   ├── 01.新增选择器.md
│   │   ├── 02.CSS3变量.md
│   │   ├── 03.变换 transform.md
│   │   ├── 04.过渡 transition.md
│   │   ├── 05.动画 animation.md
│   │   ├── 06.颜色 color.md
│   │   ├── 07.渐变 xxx-gradient.md
│   │   ├── 08.阴影 box-shadow.md
│   │   ├── 09.文本样式.md
│   │   ├── 10.字体图标.md
│   │   ├── 11.边框样式.md
│   │   ├── 12.背景样式.md
│   │   ├── 13.滤镜效果.md
│   │   └── 14.其他样式.md
│   ├── 6.sass
│   │   ├── 0.全局中配置.md
│   │   ├── 1.react中配置.md
│   │   ├── 2.基础规则.md
│   │   ├── 3.导入文件.md
│   │   ├── 4.混合器.md
│   │   └── 5.继承.md
│   ├── 7.专业名词
│   │   ├── 0.包含块.md
│   │   ├── 1.格式化上下文.md
│   │   └── 2.浏览器兼容性.md
│   ├── 8.概念对比
│   │   ├── 0._before VS _before.md
│   │   ├── 1._nth-child VS _nth-of-type.md
│   │   ├── 2._active VS _focus.md
│   │   ├── 3.标准盒 VS 怪异盒(IE).md
│   │   ├── 4.sass VS less VS stylus.md
│   │   ├── 5.rgba() VS opacity.md
│   │   └── 6.transition VS animation.md
│   └── 9.布局专题
│       ├── 0.flex基础-弹性盒子.md
│       ├── 1.flex属性-针对外层容器.md
│       ├── 2.flex属性-针对内部子元素.md
│       ├── 3.实例-flex各种布局.md
│       ├── 4.实例-flex单行排列.md
│       ├── 5.实例-table布局(四列等高).md
│       └── 6.实例-子元素不定宽高的居中.md
├── 04_webpack
│   ├── 00.简介.md
│   ├── 01.配置.md
│   ├── 02.entry入口.md
│   ├── 03.output输出.md
│   ├── 04.rules引入.md
│   ├── 05.填充1——json.md
│   ├── 06.填充2——chain【推荐】.md
│   ├── 07.使用chain的好处.md
│   ├── 08.splitChunks.md
│   ├── 09.source-map.md
│   ├── 10.babel-loader.md
│   ├── 11.css-loader.md
│   ├── 12.postcss-loader.md
│   ├── 13.less-loader.md
│   ├── 14.sass-loader.md
│   ├── 15.file-loader.md
│   ├── 16.url-loader.md
│   ├── 17.html-loader.md
│   ├── 18.模板-loader.md
│   ├── 19.自定义loader.md
│   ├── 20.js-conditional-compile-loader.md
│   ├── 21.html-webpack-plugin.md
│   ├── 22.mini-css-extract-plugin.md
│   ├── 23.optimize-css-assets-webpack-plugin.md
│   ├── 24.terser-webpack-plugin.md
│   ├── 25.compression-webpack-plugin.md
│   ├── 26.brotli-webpack-plugin.md
│   ├── 27.webpack-bundle-analyzer.md
│   ├── 28.webpack-obfuscator.md
│   ├── 29.HashedModuleIdsPlugin.md
│   └── 30.模板-plugin.md
├── 05_babel
│   ├── 0.简介.md
│   ├── 1.基础用法——语法转换.md
│   ├── 2.基础用法——补齐API.md
│   ├── 3.@babel_env不配参.md
│   ├── 4.@babel_env配参.md
│   ├── 5.plugin-transform-runtime.md
│   └── 6.使用webpack.md
├── 06_Git
│   ├── 00.git 配置命令.md
│   ├── 01.git 更新命令.md
│   ├── 02.git 分支命令.md
│   ├── 03.git 提交命令.md
│   ├── 04.git 日志命令.md
│   ├── 05.git reset命令.md
│   ├── 06.git merge命令.md
│   ├── 07.git stash 命令.md
│   ├── 08.git cherry-pick命令.md
│   ├── 09.git rebase命令.md
│   ├── 10.git revert命令.md
│   ├── 11.git 解决冲突.md
│   ├── 12.git忽略文件名大小写的问题.md
│   ├── 13.git的22端口ssh被墙.md
│   └── 14.github.com遇到DNS劫持的办法.md
├── 07_Linux
│   ├── 1.系统机器
│   │   ├── 00.两类系统.md
│   │   ├── 01.【Red Hat系列】包管理yum.md
│   │   ├── 02.【Red Hat系列】源管理.repo.md
│   │   ├── 03.【Red Hat系列】手动装包.rpm_rpm.md
│   │   ├── 04.【Ubuntu系列】包管理 apt.md
│   │   ├── 05.【Ubuntu系列】源管理 source.list.md
│   │   ├── 06.【Ubuntu系列】手动装包 .deb_dpkg.md
│   │   ├── 07.【连通登录】ping_ssh.md
│   │   ├── 08.【快捷键】shell.md
│   │   ├── 09.【信息】系统版本 lsb_release -a.md
│   │   ├── 10.【信息】软硬件 uname -a.md
│   │   ├── 11.【信息】内核 cat _proc_version.md
│   │   ├── 12.【信息】CPU cat _proc_cpuinfo.md
│   │   ├── 13.【信息】各目录用途.md
│   │   ├── 14.用户权限 whoami_su_sudo.md
│   │   ├── 15.浏览结构 ls_tree.md
│   │   ├── 16.路径探索 cd_pwd_which.md
│   │   ├── 17.信息查询 date_cal.md
│   │   ├── 18.设置别名 type_alias.md
│   │   ├── 19.历史追溯 history_script.md
│   │   ├── 20.帮助 help_man.md
│   │   └── 21.离开指令 clear_exit_shutdown.md
│   ├── 2.文件操作
│   │   ├── 00.文件名通配符.md
│   │   ├── 01.增删文件 touch_mkdir_rm.md
│   │   ├── 02.预览文件 cat_less_tail_head_file.md
│   │   ├── 03.移动文件 mv_cp.md
│   │   ├── 04.硬连接 ln _软链接 ln -s.md
│   │   ├── 05.文件权限 chmod_chown_chgrp.md
│   │   ├── 06.查找文件 find_grep.md
│   │   ├── 07.下载文件 wget_curl.md
│   │   ├── 08.解压文件 tar_zcat_zip_unzip.md
│   │   ├── 09.传输文件 scp.md
│   │   ├── 10.重定向到文件 _&_&_.md
│   │   └── 11.管道处理 sort_uniq_wc.md
│   └── 3.监控管理
│       ├── 0.挂载 mount_umount.md
│       ├── 1.端口命令 lsof_iptables.md
│       ├── 2.进程命令 ps_kill.md
│       ├── 3.磁盘和IO df_du_iostat.md
│       └── 4.内存 free_top_pmap.md
├── 08_Nodejs
│   ├── 1.npm
│   │   ├── 0.nodejs发展演变.md
│   │   ├── 1.nvm管理多版本.md
│   │   ├── 2.npm命令 .md
│   │   └── 3.批量升级npm依赖.md
│   ├── 2.Koa实践
│   │   ├── 00.【基础】Koa安装+路由+日志.md
│   │   ├── 01.【模范代码】路由书写.md
│   │   ├── 02.【模范代码】入口index.js.md
│   │   ├── 03.【配置】dotenv+config.md
│   │   ├── 04.项目启动所需依赖及脚本.md
│   │   ├── 05.setCommon处理所有中间件.md
│   │   ├── 06.【中间件】POST请求解析.md
│   │   ├── 07.【中间件】模板渲染.md
│   │   ├── 08.【中间件】静态文件服务.md
│   │   ├── 09.【中间件】协商缓存.md
│   │   ├── 10.【中间件】文件压缩.md
│   │   ├── 11.【中间件】允许跨域.md
│   │   ├── 12.【中间件】安全加固.md
│   │   ├── 13.【路由中间件】文件上传.md
│   │   ├── 14.【路由中间件】（弃用）防止csrf攻击.md
│   │   ├── 15.setRouter处理所有路由.md
│   │   ├── 16.【服务端渲染】ejs.md
│   │   ├── 17.【鉴权】jsonwebtoken.md
│   │   ├── 18.【加密】crypto_argon2.md
│   │   ├── 19.【数据库】pg-pool+事务中间件.md
│   │   ├── 20.【数据库迁移】node-pg-migrate_pg.md
│   │   ├── 21.migration 备份.md
│   │   ├── 22.【缓存】redis.md
│   │   ├── 23.【搜索】elasticsearch.md
│   │   ├── 24.【日志】koa-log4.md
│   │   ├── 25.【日志高级】搭配logstash.md
│   │   ├── 26.【pm2】集群开启.md
│   │   ├── 27.【小工具封装】 uuid_.md
│   │   └── 28.不建议使用的包.md
│   └── 3.Eggjs实践
│       ├── 00.【基础】eggjs安装+路由+控制器.md
│       ├── 01.eggjs视图+静态资源.md
│       ├── 02.eggjs服务+请求API+日志.md
│       ├── 03.eggjs扩展内置对象.md
│       ├── 04.eggjs中间件+定时任务.md
│       ├── 05.eggjs数据库安装(windows).md
│       ├── 06.【弃用】egg-mysql配置(无model方案)+CRUD操作+事务.md
│       ├── 07.egg-sequelize配置(有model方案)+CRUD操作+事务.md
│       ├── 08.findAll_One_Pk(sequelize).md
│       ├── 09.sequelize-cli配置(用于管理migration).md
│       ├── 10.eggjs跨域解决.md
│       ├── 11.eggjs密码加密.md
│       ├── 12.eggjs鉴权.md
│       ├── 13.eggjs的一些技巧和坑.md
│       ├── 14.【后端部署】安装nodejs.md
│       ├── 15.【后端部署】安装mysql.md
│       ├── 16.【后端部署】mysql简单操作更改.md
│       ├── 17.【后端部署】部署eggjs.md
│       ├── 18.【后端部署】README.md
│       ├── 19.【前端部署】部署uniapp.md
│       └── 20.【前端部署】README.md
├── 09_PostgreSQL
│   ├── 1.基础
│   │   ├── 00.实用教程网址.md
│   │   ├── 01.实用命令.md
│   │   ├── 02.实用函数.md
│   │   ├── 03.创建_删除 表.md
│   │   ├── 04.修改 表.md
│   │   ├── 05.查询源创建语句.md
│   │   ├── 06.简单查询 行.md
│   │   ├── 07.聚合函数 行.md
│   │   ├── 08.插入_删除 行.md
│   │   ├── 09.更新 行.md
│   │   ├── 10.索引——btree_brin.md
│   │   ├── 11.索引——GIN_GIST.md
│   │   ├── 12.索引——hash.md
│   │   ├── 13.索引——对于json与jsonb.md
│   │   ├── 14.取值操作符——`-_`、`#_`.md
│   │   ├── 15.判断操作符——`@_`、`_`.md
│   │   ├── 16.正则操作符——`~`、原子、量词.md
│   │   ├── 17.聚簇索引 和 非聚簇索引.md
│   │   ├── 18.锁.md
│   │   └── 19.隐藏字段xmin_xmax_cmin_cmax .md
│   └── 2.运维
│       ├── 00.psql——进入数据库.md
│       ├── 01.psql——全局指令.md
│       ├── 02.psql——查询指令.md
│       ├── 03.命令行指令.md
│       ├── 04.参数——设置方式.md
│       ├── 05.参数——全局所有.md
│       ├── 06.参数——内存缓冲大小.md
│       ├── 07.参数——WAL和检查点.md
│       ├── 08.参数——数量.md
│       ├── 09.参数——超时控制.md
│       ├── 10.参数——日志、慢查询排查.md
│       ├── 11.参数——pg-pool连接池.md
│       ├── 12.历史视图——pg_stat_database.md
│       ├── 13.实时视图——pg_stat_activity.md
│       ├── 14.表视图——pg_stat_ratio_user_tables.md
│       ├── 15.索引视图——pg_stat_user_indexes.md
│       ├── 16.语句统计视图——pg_stat_statements.md
│       ├── 17.检查点视图——pg_stat_bgwriter.md
│       ├── 18.缓存视图——pg_buffercache.md
│       ├── 19.OS缓存视图——pgfincore.md
│       ├── 20.基于视图的 占用空间 查询.md
│       └── 21.推荐优化工具(在线).md
├── 10_Redis
│   ├── 1.安装配置
│   │   ├── 0.redis源码安装.md
│   │   ├── 1.修改为守护进程.md
│   │   ├── 2.设置日志目录.md
│   │   ├── 3.安全性.md
│   │   ├── 4.设置RDB持久化.md
│   │   ├── 5.设置AOF持久化 .md
│   │   └── 6.添加到系统服务.md
│   ├── 2.Redis理论
│   │   ├── 00.键值对.md
│   │   ├── 01.基础结构-String.md
│   │   ├── 02.基础结构-List.md
│   │   ├── 03.基础结构-Set.md
│   │   ├── 04.基础结构-Zset.md
│   │   ├── 05.基础结构-Hash.md
│   │   ├── 06.redisObject.md
│   │   ├── 07.底层数据结构-sds.md
│   │   ├── 08.底层数据结构-quickList.md
│   │   ├── 09.底层数据结构-intset.md
│   │   ├── 10.底层数据结构-zskiplist.md
│   │   ├── 11.底层数据结构-ziplist.md
│   │   └── 12.底层数据结构-dict.md
│   ├── 3.Redis实践
│   │   ├── 0.批量操作相同前缀的键.md
│   │   ├── 1.问题排查与优化.md
│   │   ├── 2.用 bitMap 对时间秒数去重.md
│   │   └── 3.streams流的使用.md
│   └── 4.node-redis
│       ├── 0.安装 + 范例.md
│       ├── 1.封装 + 简单使用.md
│       ├── 2.自由命令 + 内置命令 .md
│       ├── 3.使用事务批量执行.md
│       └── 4.XX，NX，EX，PX.md
├── 11_Nginx
│   ├── 00.【检查】nginx安装情况.md
│   ├── 01.nginx安装 - centos.md
│   ├── 02.nginx安装 - ubuntu.md
│   ├── 03.yum或apt安装对应的运维指令.md
│   ├── 04.源码安装(不推荐).md
│   ├── 05.前置注意.md
│   ├── 06.配置gzip.md
│   ├── 07.配置br.md
│   ├── 08.简单配置后签发https证书.md
│   ├── 09.映射和重定向规则.md
│   ├── 10.多级反向代理抓出真实ip.md
│   ├── 11.重新定义请求头.md
│   ├── 12.负载均衡.md
│   ├── 13.限流.md
│   ├── 14.一级代理下的配置文件.md
│   ├── 15.二级代理下的配置文件.md
│   ├── 16.增大nginx的并发限制.md
│   └── 17.密钥安全性.md
├── 12_Docker
│   ├── 00.docker安装 - centos.md
│   ├── 01.docker安装 - ubuntu.md
│   ├── 02.docker安装-macOS.md
│   ├── 03.docker配置问题.md
│   ├── 04.docker命令 - 全局列出.md
│   ├── 05.docker命令 - 镜像拉取和运行.md
│   ├── 06.docker命令 - 容器操作.md
│   ├── 07.docker命令 - 镜像命名和分发.md
│   ├── 08.基于 Dockerfile 的镜像生成.md
│   ├── 09.基于 Dockerfile 的构建指令.md
│   ├── 10.基于docker-compose.yml的多镜像部署.md
│   ├── 11.docker实战 - 安装pgadmin.md
│   ├── 12.docker实战 - 安装omnidb.md
│   ├── 13.docker实战 - 安装greenplum.md
│   ├── 14.docker实战 - 安装superset.md
│   ├── 15.docker 测试机部署问题.md
│   └── 16.排查容器node进程内存泄漏.md
├── 13_ElasticSearch
│   ├── 00.安装JDK_es_logstash_Kibana.md
│   ├── 01.es-十个概念.md
│   ├── 02.es-配置.md
│   ├── 03.es-节点发现.md
│   ├── 04.es-分片_副本_路由.md
│   ├── 05.es-分段.md
│   ├── 06.es-基础指令.md
│   ├── 07.es-创建索引+查看索引.md
│   ├── 08.es-添加文档.md
│   ├── 09.es-更新文档.md
│   ├── 10.es-删除文档+删除索引.md
│   ├── 11.logstash-五个概念.md
│   ├── 12.logstash-配置.md
│   ├── 13.logstash-jdbc插件.md
│   ├── 14.logstash-针对book表.md
│   ├── 15.logstash-针对sheet表.md
│   ├── 16.logstash-针对composer表.md
│   └── 17.logstash-针对conf的配置.md
├── 14_SystemDesign
│   ├── 00.可扩展性Scalability.md
│   ├── 01.权衡取舍Trade Off.md
│   ├── 02.数据库——SQL.md
│   ├── 03.数据库——NoSQL.md
│   ├── 04.异步处理——Queue.md
│   ├── 05.域名——DNS.md
│   ├── 06.分发——CDN.md
│   ├── 07.负载均衡.md
│   ├── 08.反向代理.md
│   ├── 09.微服务架构.md
│   ├── 10.服务可靠性.md
│   ├── 11.一致性哈希.md
│   ├── 12.设计流程总结.md
│   ├── 13.常用策略.md
│   └── 14.常用部件.md
├── 15_WeixinPlatform
│   ├── 00.wxHelper初始化.md
│   ├── 03.【例1】用代码生成公众号订阅二维码.md
│   ├── 04.【例1】用户怎么扫到二维码呢？.md
│   ├── 05.【例1】监听二维码的反馈.md
│   ├── 06.【例1】处理反馈-reply.md
│   ├── 07.【例1】处理反馈-subscribe.md
│   ├── 08.【例1】处理反馈-unsubscribe.md
│   ├── 09.【例2】主动发送消息.md
│   ├── 10.总结一下目前为止用到的微信api.md
│   ├── 11.【笔记】总览.md
│   ├── 12.【笔记】被动回复粉丝消息.md
│   ├── 13.【笔记】我们的服务器搭建.md
│   ├── 14.【笔记】搭建access_token中控.md
│   ├── 15.【笔记】自定义菜单.md
│   ├── 16.【笔记】接受事件推送.md
│   ├── 17.【笔记】回应事件推送.md
│   ├── 18.【笔记】关注后主动发模版消息.md
│   └── 19.【笔记】未关注时发送一次性消息.md
├── 16_Vim
│   ├── 0.vim - 简介.md
│   ├── 1.vim - 光标移动.md
│   ├── 2.vim - 搜索替换.md
│   ├── 3.vim - 选中操作.md
│   ├── 4.vim - 编辑操作.md
│   ├── 5.vim - 剪贴板.md
│   ├── 6.vim - 全局操作.md
│   └── 7.vim - 切换编辑.md
└── README.md
```