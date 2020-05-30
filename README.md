# JavaScript 资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-javascript](https://github.com/sorrycc/awesome-javascript) 是 sorrycc 发起维护的 JS 资源列表，内容包括：包管理器、加载器、测试框架、运行器、QA、MVC框架和库、模板引擎、数据可视化、时间轴、编辑器等等

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-javascript 列表，我们将对其中的各个资源项进行编译整理。此外还将从其他来源补充好资源。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hwww.importnew.com/)。可参考已整理的内容：
  - 《[jQWidgets：jQuery HTML5 UI组件框架](http://www.importnew.com/jqwidgets-jquery-html5-ui/)》
  - 《[Bootstrap：Web前端开发框架](http://www.importnew.com/bootstrap/)》
  - 《[YUI Compressor：JS/CSS压缩工具](http://www.importnew.com/yui-compressor/)》

* * *

### 如何参与本项目？

<!-- 从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 在用 JavaScript；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「JS大全」 -->

* * *

### 如何为列表贡献新资源？

欢迎大家为列表贡献高质量的新资源，提交PR时请参照以下要求：

* 请确保推荐的资源自己使用过
* 提交PR时请注明推荐理由

资源列表管理收到PR请求后，会定期（每周）在微博转发本周提交的PR列表，并在微博上面听取使用过这些资源的意见。确认通过后，会加入资源大全。

感谢您的贡献！

* * *

### 本项目的参与者

- 维护者：
- 贡献者：[刘健超](https://github.com/JChehe)、MissNull、一兮、Mr. Somebody、Jason Lee、[Tab_Gre](http://www.jobbole.com/members/ivanberry/)、[GavinZhang](http://www.jobbole.com/members/KeepMoving/)、[shadowkimi520](https://github.com/shadowkimi520/)、[zhoutk](http://www.jobbole.com/members/zhoutk/)、[tzstone](http://www.jobbole.com/members/tzstone)、[Erichain](http://www.jobbole.com/members/Erichain)、[chen](http://www.jobbole.com/members/atmfans)、[ElizabethMa](https://github.com/ElizabethMa)、[LeuisKen](http://www.jobbole.com/members/LeuisKen)、[linacre](http://www.jobbole.com/members/linacre)、[王涛](http://www.jobbole.com/members/wt726553124/)、[neal1991](https://github.com/neal1991)、[luoyjx](https://github.com/luoyjx)、[appleshowc](https://github.com/appleshowc)、[TAMMENY](https://github.com/TAMMENY)、[cike8899](https://github.com/cike8899)、[cnzin](https://github.com/cnzin)、[cike8899](https://github.com/cike8899)、[hustcc](https://github.com/hustcc)、[冰斌](http://www.jobbole.com/members/libing1209/)、[邢敏](https://github.com/dfghj44444)、[张小然](https://github.com/hellozhangran)

注：名单不分排名，不定期补充更新

* * *

<!-- ### 奖励计划

虽然奖励可能并不是你加入的主要原因，但还是有必要提一下：

* 整理超过 20 个资源后，可在伯乐在线上开通打赏；
* 每整理 20 个资源，有机会获得技术书籍或各种有意思的创意、极客产品；
* [奖励详情](http://hao.jobbole.com/rewards/)

* * * -->
### 目录

* [JavaScript资源大全中文版](#awesome-javascript-cn)
  * [包管理器](#package-managers)
  * [加载器](#loaders)
  * [打包工具](#bundlers)
  * [测试框架](#testing-frameworks)
  * [QA 工具](#qa-tools)
  * [MVC 框架和库](#mvc-frameworks-and-libraries)
  * [基于 Node 的 CMS 框架](#node-powered-cms-frameworks)
  * [模板引擎](#templating-engines)
  * [Flux](#data-flow)
  * [数据可视化](#data-visualization)
    * [时间轴](#timeline)
  * [编辑器](#editors)
  * 工具
    * [文件](#files)
    * [函数式编程](#functional-programming)
    * [响应式编程](#reactive-programming)
    * [数据结构](#data-structure)
    * [日期](#date)
    * [字符串](#string)
    * [数字](#number)
    * [存储](#storage)
    * [颜色](#color)
    * [国际化和本地化](#i18n-and-l10n)
    * [类](#class)
    * [控制流](#control-flow)
    * [路由](#routing)
    * [安全性](#security)
    * [日志](#log)
    * [正则表达式](#regexp)
    * [媒体](#media)
    * [语言命令](#voice-command)
    * [API](#api)
    * [视觉检测](#vision-detection)
    * [浏览器检测](#browser-detection)
    * [性能分析](#performance-analysis)
  * UI
    * [代码高亮](#code-highlighting)
    * [加载状态](#loading-status)
    * [验证](#validation)
    * [键盘封装器](#keyboard-wrappers)
    * [浏览和引导](#tours-and-guides)
    * [通知](#notifications)
    * [幻灯片](#sliders)
    * [滑块控件](#range-sliders)
    * [表单组件](#form-widgets)
    * [提示](#tips)
    * [模态框和弹出框](#modals-and-popups)
    * [滚动条](#scroll)
    * [菜单](#menu)
    * [表格/栅格](#table-grid)
    * [框架](#frameworks-1)
  * 移动
    * [手势](#gesture)
    * [触摸](#touch)
  * [地图](#maps)
  * [视频/音频](#video-audio)
  * [动画](#animations)
  * [图片处理](#image-processing)
  * [ES6](#es6)
  * [SDK](#sdk)
  * [大杂烩](#misc)
* [精品阅读](#worth-reading)
- [资源](#resources)
    - [社区](#communities)
    - [有影响力的书](#influential-books)
    - [微博、微信公众号](#weibo-weixin)
    - [知名网站](#websites)
    - [博客](blogs)

* * *

<h2 id="package-managers">包管理器</h2>

管理着 JavaScript 库，并提供读取和打包它们的工具。

* Yarn: Yarn 是由 Facebook、Google、Exponent 和 Tilde 联合推出了一个新的 JS 包管理工具[官网](https://yarnpkg.com/lang/en/)
* npm：npm 是 JavaScript 的包管理器。[官网](https://www.npmjs.com/)
* Bower：一个 web 应用的包管理器。[官网](https://github.com/bower/bower)
* component：能构建更好 web 应用的客户端包管理器。[官网](https://github.com/componentjs/component)
* spm：全新的静态包管理器。[官网](https://github.com/spmjs/spm)
* jam：一个专注于浏览器端和兼容 RequireJS 的包管理器。[官网](https://github.com/caolan/jam)
* jspm：流畅的浏览器包管理器。[官网](https://github.com/jspm/jspm-cli)
* Ender：没有库文件的程序库。[官网](https://github.com/ender-js/Ender)
* volo：以项目模板、添加依赖项与自动化生成的方式创建前端项目。[官网](https://github.com/volojs/volo) 
* Duo：一个整合 Component、Browserify 和 Go [官网](https://github.com/duojs/duo)的最佳思想，使开发者能快速方便地组织和编写前端代码的下一代包管理器。

<h2 id="loaders">加载器</h2>

JavaScript 的模块或加载系统。

* RequireJS：JavaScript 文件和模块的加载器。[官网](https://github.com/jrburke/requirejs)
* browserify：在浏览器端以 node.js 的方式 require()。[官网](https://github.com/substack/node-browserify)
* SeaJS：用于 Web 的模块加载器。[官网](https://github.com/seajs/seajs)
* HeadJS：HEAD 的唯一脚本。[官网](https://github.com/headjs/headjs)
* curl：小巧、快速且易扩展的模块加载器，它能处理 AMD、CommonJS Modules/1.1、CSS、HTML/text 和历史脚本。[官网](https://github.com/cujojs/curl)
* lazyload：小巧且无依赖的异步 JavaScript 和 CSS 加载器。[官网](https://github.com/rgrove/lazyload/)
* script.js：异步 JavaScript 加载器和依赖管理器。[官网](https://github.com/ded/script.js)
* systemjs：AMD、CJS（commonJS） 和符合 ES6 规范的模块加载器。[官网](https://github.com/systemjs/systemjs)
* LodJS：基于 AMD 的模块加载器。[官网](https://github.com/yanhaijing/lodjs)
* ESL：浏览器端的模块加载器，支持延迟定义和 AMD。[官网](https://github.com/ecomfe/esl)
* modulejs：轻量的 JavaScript 模块系统。[官网](https://github.com/lrsjng/modulejs)

<h2 id="bundlers">打包工具</h2>

* browserify ：Browserify 让你能在浏览器端使用 require('modules') ，打包所有依赖。[官网](https://github.com/substack/node-browserify)
* webpack：为浏览器打包 CommonJs/AMD 模块。[官网](https://github.com/webpack/webpack)
* gulp：用自动化构建工具增强你的工作流程！[官网](http://gulpjs.com/)
* rollup: JavaScript 模块打包器! [官网](https://rollupjs.org/) [中文](http://www.rollupjs.com/)

<h2 id="testing-frameworks">测试框架</h2>

### 框架

* mocha：适用于 node.js 和浏览器、简易、灵活、有趣的 JavaScript 测试框架。[官网](https://github.com/mochajs/mocha)
* jasmine：简单无 DOM 的 JavaScript 测试框架。[官网](https://github.com/jasmine/jasmine)
* qunit：一个易于使用的 JavaScript 单元测试框架。[官网](https://github.com/jquery/qunit)
* jest：简单的 JavaScript 单元测试框架。[官网](https://github.com/facebook/jest)
* prova：基于 Tape 和 Browserify 的测试运行器，它适用于 Node &amp; 浏览器。[官网](https://github.com/azer/prova)
* DalekJS：自动化且跨浏览器的 JavaScript 功能测试框架。[官网](https://github.com/dalekjs/dalek)

### 断言

* chai：适用于 node.js 和浏览器的 BDD / TDD 断言框架，并能搭配其它测试框架使用。[官网](https://github.com/chaijs/chai)
* Sinon.JS：对 JavaScript 进行 spies、stubs 和 mock 测试。[官网](https://github.com/sinonjs/sinon)
* expect.js：简约的、适用于 Node.js 和浏览器端的 BDD 式断言工具。[官网](https://github.com/Automattic/expect.js)
* should.js：适用于 Node.js 的 BDD 式断言工具。[官网](https://github.com/tj/should.js)

### 覆盖率

* istanbul：另一个 JS 代码覆盖率检测工具。[官网](https://github.com/gotwarlost/istanbul)
* blanket：一个简单的代码覆盖率检测库。它的设计理念是易于安装和使用，且可用于浏览器端和 node.js。[官网](https://github.com/alex-seville/blanket)
* JSCover：JSCover 是一个检测 JavaScript 程序代码覆盖率的工具。[官网](https://github.com/tntim96/JSCover)

### 运行器

* phantomjs：脚本化的 Headless WebKit。[官网](https://github.com/ariya/phantomjs)
* slimerjs：一个内核为 Gecko 的类似 PhantomJS 工具。[官网](https://github.com/laurentj/slimerjs)
* casperjs：基于 PhantomJS 和 Slimer JS 的导航脚本和测试工具。[官网](https://github.com/n1k0/casperjs) 
* zombie：基于 node.js 、快速、全栈且无图形界面的浏览器的测试工具。[官网](https://github.com/assaf/zombie)
* totoro：一个简单可靠且能跨浏览器运行的测试工具。[官网](https://github.com/totorojs/totoro)
* karma：一个优秀的的 JavaScript 测试运行器。[官网](https://github.com/karma-runner/karma)
* nightwatch：基于 node.js 和 selenium webdriver 的图形界面自动化测试框架。[官网](https://github.com/nightwatchjs/nightwatch)
* intern：下一代 JavaScript 代码测试栈。[官网](https://github.com/theintern/intern)
* yolpo：在浏览器逐句执行的 JavaScript 解释器。[官网](http://www.yolpo.com/)

<h2 id="qa-tools">QA 工具</h2>

* JSHint：JSHint 是一个有助于发现 JavaScript 代码错误和潜在问题的工具。[官网](https://github.com/jshint/jshint/)
* jscs：JavaScript 代码风格检测工具。[官网](https://github.com/jscs-dev/node-jscs)
* jsfmt：格式化、搜索和改写 JavaScript。[官网](https://github.com/rdio/jsfmt)
* jsinspect：检测复制粘贴和结构类似的代码。[官网](https://github.com/danielstjules/jsinspect)
* buddy.js：发现 JavaScript 代码里的 [魔术数字](https://zh.wikipedia.org/wiki/%E9%AD%94%E8%A1%93%E6%95%B8%E5%AD%97)。[官网](https://github.com/danielstjules/buddy.js)
* ESLint：完全插件化的工具，能在 JavaScript 中识别和记录模式。[官网](https://github.com/eslint/eslint)
* JSLint ：高标准、严格和固执的代码质量工具，旨在只保持语言的优良部分。[官网](https://github.com/douglascrockford/JSLint)

<h2 id="mvc-frameworks-and-libraries">MVC 框架和库</h2>

* [angular.js](http://hao.jobbole.com/angularjs/)：为网络应用增强 HTML。[官网](https://github.com/angular/angular.js)
* aurelia：一个适用于移动设备、桌面电脑和 web 的客户端 JavaScript 框架。[官网](http://aurelia.io/)
* backbone：给你的 JS 应用加入带有 Models、Views、Collections 和 Events 的 Backbone。[官网](https://github.com/jashkenas/backbone)
* batman.js：最适合 Rails 开发者的 JavaScript 框架。[官网](http://batmanjs.org/)
* ember.js：一个旨在创建非凡 web 应用的 JavaScript 框架。[官网](https://github.com/emberjs/ember.js)
* meteor：一个超简单的、数据库无处不在的、只传输数据的纯 JavaScript web 框架。[官网](https://github.com/meteor/meteor)
* ractive：新一代 DOM 操作。[官网](https://github.com/ractivejs/ractive)
* vue：一个用于构建可交互界面的、直观快速和可组合的 MVVM 框架。[官网](https://github.com/vuejs/vue) 
* knockout：Knockout 用 JavaScript 让创建响应式的富 UI 更加容易。[官网](https://github.com/knockout/knockout) 
* spine：构建 JavaScript 应用的轻量 MVC 库。[官网](https://github.com/spine/spine)
* espresso.js：一个极小的、用于制作用户界面的 JavaScript 库。[官网](https://github.com/techlayer/espresso.js)
* canjs：让 JS 更好、更快、更简单。[官网](https://github.com/canjs/canjs)
* react：用于建构用户界面的库。它是声明式的、高效的和极度灵活的，并使用虚拟 DOM 作为其不同的实现。[官网](https://facebook.github.io/react/)
* react-native：一个用 React 构建原生应用的框架。[官网](https://github.com/facebook/react-native)
* riot：类 React 库，但很轻量。[官网](https://github.com/riot/riot)
* thorax：加强你的 Backbone。[官网](https://github.com/walmartlabs/thorax)
* chaplin：使用 Backbone.js 库的 JavaScript 应用架构。[官网](https://github.com/chaplinjs/chaplin)
* marionette：一个 Backbone.js 的复合应用程序库，旨在简化大型 JavaScript 应用结构。[官网](https://github.com/marionettejs/backbone.marionette)
* ripple：一个小巧的、用于构建响应界面的基础框架。[官网](https://github.com/ripplejs/ripple)
* rivets：轻量却拥有强大的数据绑定和模板解决方案[官网](https://github.com/mikeric/rivets)
* derby：让编写实时和协同应用更简单的 MVC 框架，能够在 Node.js 和浏览器同时运行。[官网](https://github.com/derbyjs/derby)
    * derby-awesome：很棒的 derby 组件集合。[官网](https://github.com/russll/awesome-derby)
* [way.js](http://hao.jobbole.com/way-js/)：简单、轻量、持久化的双向数据绑定。[官网](https://github.com/gwendall/way.js)
* mithril.js：Mithril 是一个客户端 MVC 框架（轻量、强大和快速）[官网](https://github.com/lhorie/mithril.js)
* jsblocks：jsblocks 是一个更好的 MV-ish 框架。[官网](https://github.com/astoilkov/jsblocks)
* LiquidLava：易懂的、用于构建用户界面的 MVC 框架。[官网](http://www.lava-framework.com/)
* [Electron](http://hao.jobbole.com/electron/)：用Html、CSS和JavaScript构建跨平台的客户端应用程序。[官网](http://electron.atom.io/)、[GitHub](https://github.com/electron/electron)

<h2 id="node-powered-cms-frameworks">基于 Node 的 CMS 框架</h2>

* KeystoneJS：强大的 CMS 和 web 应用框架。[官网](https://github.com/keystonejs/keystone)
* Reaction Commerce：拥有实时的架构和设计的响应式（reactive） CMS。[官网](https://github.com/reactioncommerce/reaction)
* Ghost：简单、强大的发布平台。[官网](https://github.com/tryghost/Ghost)
* Apostrophe：提供内容编辑和基本服务的 CMS。[官网](https://github.com/punkave/apostrophe)
* We.js：适用于实时应用、网站或博客的框架。[官网](https://github.com/wejs/we/)
* Hatch.js：拥有社交特性的 CMS 平台。[官网](https://github.com/inventures/hatchjs)
* TaracotJS：拥有快速、极简风格特点且基于Node.js 的 CMS。[官网](https://github.com/xtremespb/taracotjs-generator/)
* Nodizecms：为 CoffeeScript 爱好者准备的 CMS。[官网](https://github.com/nodize/nodizecms)
* Cody：拥有所见即所得的编辑器的 CMS。[官网](https://github.com/jcoppieters/cody)
* PencilBlue：CMS 和博客平台。[官网](https://github.com/pencilblue/pencilblue/)

<h2 id="templating-engines">模板引擎</h2>

模板引擎允许您执行字符串插值。

* mustache.js：是 JavaScript 中带有 {{mustaches}} 的最简模板。[官网](https://github.com/janl/mustache.js)
* handlebars.js：是 Mustache 模板语言的扩展。[官网](https://github.com/wycats/handlebars.js/)
* hogan.js：是 Mustache 模板语言的编译器。[官网](https://github.com/twitter/hogan.js)
* doT：最快速简洁的 JavaScript 模板引擎，适用于 nodejs 和浏览器。[官网](https://github.com/olado/doT)
* dustjs：适用于浏览器和 node.js 的异步模板。[官网](https://github.com/linkedin/dustjs/)
* eco：嵌入式的 CoffeeScript 模板。[官网](https://github.com/sstephenson/eco/)
* JavaScript-Templates：轻量（小于 1KB）、快速且无依赖的强大 JavaScript 模版引擎。[官网](https://github.com/blueimp/JavaScript-Templates)
* t.js：小巧的 JavaScript 模板框架，压缩后约为 400 字节。[官网](https://github.com/jasonmoo/t.js)
* pug：健壮的、优雅且功能丰富的 nodejs 模板引擎。[官网](https://github.com/pugjs/pug)
* EJS：高效的 JavaScript 模板。[官网](https://github.com/mde/ejs)
* xtemplate：可扩展的模板引擎，适用于 node 和浏览器。[官网](https://github.com/xtemplate/xtemplate)
* marko：快速轻量且基于 HTML 的模板引擎，支持异步、流、自定义标签和 CommonJS 模编译后输出。适用于 Node.js [官网](https://github.com/marko-js/marko)和浏览器。

<h2 id="data-flow">Flux</h2>

Flux是Facebook用来构建客户端Web应用的应用架构

* Reflux是根据React的flux创建的单向数据流类库。[官网](https://github.com/reflux/refluxjs)
* Redux是可预测javascript应用程序状态的容器。[官网](http://redux.js.org/)
* Mobx是通过透明的函数响应式编程实现简单，可扩展的状态管理库。[官网](https://mobx.js.org/)
* Dva是基于Redux, Redux-saga 和 react-router@2.x的轻量级的框架。[官网](https://github.com/dvajs/dva)

<h2 id="data visualization">数据可视化</h2>

Web 数据可视化工具

* d3：一个对 HTML 和 SVG 进行可视化的 JavaScript 库。[官网](https://github.com/mbostock/d3)
* metrics-graphics：更简洁和拥有更规范的数据图表布局优化算法的库。[官网](https://github.com/mozilla/metrics-graphics)
* pykcharts.js：经过精心设计后，去除 d3.js 复杂性的 d3.js 图表库。[官网](https://github.com/pykih/PykCharts.js)
* [three.js](http://hao.jobbole.com/three-js/)：JavaScript 3D 库。[官网](https://github.com/mrdoob/three.js)
* Chart.js：简单的、基于 canvas 标签的 HTML5 图表库。[官网](https://github.com/nnnick/Chart.js)
* paper.js：是矢量图形脚本中的瑞士军刀 —— 使用 HTML5 Canvas 将 Scriptographer  移植到 JavaScript [官网](https://github.com/paperjs/paper.js)和浏览器。
* fabric.js：JavaScript Canvas 库，SVG 与 Canvas 可以相互解析。[官网](https://github.com/kangax/fabric.js)
* peity：进度条、线状和饼状图。[官网](https://github.com/benpickles/peity)
* raphael：JavaScript 矢量库。[官网](https://github.com/DmitryBaranovskiy/raphael)
* echarts：商业产品图表。[官网](https://github.com/ecomfe/echarts)
* vis：动态的、基于浏览器的可视化库。[官网](https://github.com/almende/vis)
* two.js：一个渲染器无关的适用于 web 的二维绘图 api 。[官网](https://github.com/jonobr1/two.js)
* g.raphael：基于 Raphaël 图表库。[官网](https://github.com/DmitryBaranovskiy/g.raphael)
* sigma.js：一个致力于图形绘画的 JavaScript 库。[官网](https://github.com/jacomyal/sigma.js)
* arbor：一个使用 web workers 和 jQuery 的图形可视化库。[官网](https://github.com/samizdatco/arbor)
* cubism：可视化时间序列的 D3 插件。[官网](https://github.com/square/cubism)
* dc.js：与 crossfilter 无缝合作的多维图表绘制库，使用 d3.js 渲染。[官网](https://github.com/dc-js/dc.js)
* vega：一套可视化语法。[官网](https://github.com/trifacta/vega)
* processing.js：Processing.js 基于 Web 标准使数据可视化，而无需任何插件。[官网](http://processingjs.org/)
* envisionjs：动态的 HTML5 可视化。[官网](https://github.com/HumbleSoftware/envisionjs)
* rickshaw：用于构建交互式实时图表的 JavaScript 工具包。[官网](https://github.com/shutterstock/rickshaw)
* flot：吸引人的、基于 jQuery 的 JavaScript 图表库。[官网](https://github.com/flot/flot)
* morris.js：漂亮的时间序列线框图。[官网](https://github.com/morrisjs/morris.js)
* nvd3：一个为 D3.js 构建可复用图表和图表组件的库。[官网](https://github.com/novus/nvd3)
* svg.js：一个轻量的、用于操作和添加 SVG 动画的库。[官网](https://github.com/wout/svg.js)
* heatmap.js：基于 HTML5 canvas 的热力图 JavaScript 库。[官网](https://github.com/pa7/heatmap.js)
* jquery.sparkline：一个直接在浏览器端生成小型走势图的 jQuery 插件。[官网](https://github.com/gwatts/jquery.sparkline)
* xCharts：一个基于 D3、用于构建自定义图表和图形的库。[官网](https://github.com/tenxer/xCharts)
* trianglify：基于 d3.js 的低多边形（low poly）风格背景图片生成器。[官网](https://github.com/qrohlf/trianglify)
* d3-cloud：创建词云（word cloud）效果的 JavaScript 库。[官网](https://github.com/jasondavies/d3-cloud)
* d4：一个基于 D3 、友好、可复用的 DSL 图表库 。[官网](https://github.com/heavysixer/d4)
* dimple.js：基于 d3 的简易商业分析图表库。[官网](http://dimplejs.org/)
* chartist-js：简单的响应式图表。[官网](https://github.com/gionkunz/chartist-js)
* epoch：一个通用的实时图表库。[官网](https://github.com/epochjs/epoch)
* c3：基于 D3 的可复用图表库。[官网](https://github.com/masayuki0812/c3)
* BabylonJS：一个运用 HTML5 和 WebGL 构建 3D 游戏的框架。[官网](https://github.com/BabylonJS/Babylon.js)
* jquery.raty.js：一个星级评分插件。[官网](https://github.com/wbotelhos/raty)

也有一些很棒的收费库，如 [amchart](https://www.amcharts.com/)、[plotly](https://plot.ly/) 和 [highchart](http://www.highcharts.com/)。

<h3 id="timeline">时间轴</h3>

* TimelineJS： 一个用 JavaScript 编写的可叙事时间轴库。[官网](https://github.com/NUKnightLab/TimelineJS)
* timesheet.js：用于构建简单的 HTML5 &amp; CSS3 时间表的 JavaScript 库。[官网](https://github.com/semu/timesheet.js)

<h2 id="editors">编辑器</h2>

* ace：Ace（Ajax.org Cloud9 Editor）。[官网](https://github.com/ajaxorg/ace)
* CodeMirror：浏览器端的代码编辑器。[官网](https://github.com/codemirror/CodeMirror)
* esprima：用于综合分析的 ECMAScript 解析器。[官网](https://github.com/ariya/esprima)
* [quill](http://hao.jobbole.com/quill/)：一个带有 API 的跨浏览器富文本编辑器。([官网](http://quilljs.com/))
* medium-editor：Medium.com 所见即所得编辑器的克隆版。[官网](https://github.com/yabwe/medium-editor)
* pen：享受在线编辑（支持 markdown）。[官网](https://github.com/sofish/pen)
* jquery-notebook：一个易用的、简洁优雅的文本编辑器。灵感来源于 Medium 的魅力。[官网](https://github.com/raphaelcruzeiro/jquery-notebook)
* bootstrap-wysiwyg：小巧的、兼容 bootstrap 的所见即所得的富文本编辑器。[官网](https://github.com/mindmup/bootstrap-wysiwyg)
* ckeditor-releases：适用于每个人的 web 文本编辑器。[官网](https://github.com/ckeditor/ckeditor-releases)
* editor：一个 markdown 编辑器，但仍在开发中。[官网](https://github.com/lepture/editor)
* EpicEditor：一个可嵌入的 JavaScript Markdown [官网](https://github.com/OscarGodson/EpicEditor)的编辑器，拥有全屏编辑、即时预览、自动保存草稿和离线支持等功能。
* jsoneditor：查看、编辑和格式化 JSON 的 web 工具。[官网](https://github.com/josdejong/jsoneditor)
* vim.js： 拥有持久化 ~/.vimrc 的 Vim 编辑器的 JavaScript 移植版本。[官网](https://github.com/coolwanglu/vim.js)
* Squire：HTML5 富文本编辑器。[官网](https://github.com/neilj/Squire)
* TinyMCE：JavaScript 富文本编辑器。[官网](https://github.com/tinymce/tinymce)
* trix：由 Basecamp 制作，适用于每天写作的富文本编辑器。[官网](https://github.com/basecamp/trix)

<h3 id="files">文件</h3>

处理文件的库。

* Papa Parse：一款强大的 CSV 库，支持解析 CSV 文件/字符串，也能导出 CSV。[官网](https://github.com/mholt/PapaParse)
* jBinary：对用声明式语法描述文件类型和数据结构的二进制文件，进行高级 I/O（加载、解析、操作、序列化、存储）操作。[官网](https://github.com/jDataView/jBinary)

<h3 id="functional-programming">函数式编程</h3>

函数式编程库扩展了 JavaScript 的能力。

* [underscore](http://hao.jobbole.com/underscore/)：JavaScript 的实用工具。[官网](https://github.com/jashkenas/underscore)
* [lodash](http://hao.jobbole.com/lodash/)：提供一致性、可定制、高性能和额外功能的实用库。[官网](https://github.com/lodash/lodash)
* Sugar：一个扩展了原生对象功能的 JavaScript 库。[官网](https://github.com/andrewplummer/Sugar)
* lazy.js：类似 Underscore，但性能更优越[官网](https://github.com/dtao/lazy.js)
* ramda：一个针对 JavaScript 程序员的实用函数库。[官网](https://github.com/CrossEye/ramda)
* mout：模块化的 JavaScript 工具库。[官网](https://github.com/mout/mout)
* mesh：流数据同步工具。[官网](https://github.com/crcn/mesh.js)
* [rubico](https://github.com/a-synchronous/rubico) - 🏞 [a]synchronous functional syntax

<h3 id="reactive-programming">响应式编程</h3>

响应式程序库扩展了 JavaScript 的能力。

* RxJs：对 JavaScript 进行响应式扩展。[官网](https://github.com/Reactive-Extensions/RxJS)
* Bacon：JavaScript 的 FPR（函数式响应式编程）库。[官网](https://github.com/baconjs/bacon.js)
* Kefir：受 Bacon.js 和 RxJS 启发的 FRP 库，专注于高性能和低内存消耗。[官网](https://github.com/pozadi/kefir)
* Highland：对 JavaScript 实用工具的重新思考，Highland 能轻易地管理同步和异步信息，而且仅使用标准 JavaScript 和类 Node 流。[官网](http://highlandjs.org/)
* Most.js：高性能 FRP 库。[官网](https://github.com/cujojs/most)

<h3 id="data-structure">数据结构</h3>

数据结构库用于构建一个更复杂的应用。

* immutable-js：不可变的数据集合，包括 Sequence、Range、Repeat、Map、OrderedMap、Set 和 sparse Vector。[官网](https://github.com/facebook/immutable-js)
* mori：使用 ClojureScript 持久化数据结构和支持原生 JavaScript API 的库。[官网](https://github.com/swannodette/mori)
* buckets：完整的、经过充分测试和记录数据结构的 JavaScript 库。[官网](https://github.com/mauriciosantos/Buckets-JS)
* hashmap：简单的 hashmap 实现，支持任何类型的键值。[官网](https://github.com/flesler/hashmap)

<h3 id="date">日期</h3>

日期库。

* moment：解析、验证、操作和显示日期。[官网](https://github.com/moment/moment)
* moment-timezone：基于 moment.js 的时区库。[官网](https://github.com/moment/moment-timezone)
* jquery-timeago：一款支持自动更新模糊时间戳的 jQuery 插件（如："4 分钟之前"）。[官网](https://github.com/rmm5t/jquery-timeago)
* timezone-js：让 JavaScript Date 对象拥有时区功能。使用 Olson zoneinfo 文件记录着时区数据。[官网](https://github.com/mde/timezone-js)
* date：拥有人性化的 Date() 方法。[官网](https://github.com/MatthewMueller/date)
* ms.js：小巧的毫秒转换工具。[官网](https://github.com/rauchg/ms.js)
* timeago.js：一个非常轻量级(~1.7 Kb)的用于将时间转化成`xxx时间前`格式，例如：8分钟前。[官网](http://timeago.org)

<h3 id="string">字符串</h3>

字符串库。

* selecting：一个允许你获取用户选定文本的库。[官网](https://github.com/EvandroLG/selecting)
* underscore.string：扩展了 Underscore.js 的字符串操作。[官网](https://github.com/epeli/underscore.string)
* string.js：额外的 JavaScript 字符串方法。[官网](https://github.com/jprichardson/string.js)
* he：健壮的 HTML 实体编码/解码器。[官网](https://github.com/mathiasbynens/he)
* multiline：多行字符串。[官网](https://github.com/sindresorhus/multiline)
* query-string：解析和字符串化 URL 查询字符串。[官网](https://github.com/sindresorhus/query-string)
* URI.js：URL 操作库。[官网](https://github.com/medialize/URI.js/) 
* jsurl：轻量的 URL 操作库。[官网](https://github.com/Mikhus/jsurl)
* sprintf.js：实现字符串格式化。[官网](https://github.com/alexei/sprintf.js)
* url-pattern：让 url 和其它字符串进行比正则表达式匹配更简单。字符串和数据可相互转化。[官网](https://github.com/snd/url-pattern)

<h3 id="number">数字</h3>

* Numeral-js：对数字进行格式化和操作的库。[官网](https://github.com/adamwdraper/Numeral-js)
* odometer：流畅的数字过渡效果。[官网](https://github.com/HubSpot/odometer)
* accounting.js：对数字、金钱、货币进行格式化的轻量库——完全本地化和无依赖。[官网](https://github.com/josscrowcroft/accounting.js)
* money.js：一个小巧（1kb）的货币转换库，适用于 web 和 nodeJS。[官网](https://github.com/josscrowcroft/money.js)
* Fraction.js：一个有理数库。[官网](https://github.com/infusion/Fraction.js)
* Complex.js： 一个复数库。[官网](https://github.com/infusion/Complex.js)
* Polynomial.js：一个多项式库。[官网](https://github.com/infusion/Polynomial.js)

<h3 id="storage">存储</h3>

* store.js：为所有浏览器封装了 LocalStorage，而没有使用 cookies 和 flash。隐秘地使用 localStorage、globalStorage 和用户数据。[官网](https://github.com/marcuswestin/store.js)
* localForage：改善后的离线存储。其封装了 IndexedDB、WebSQL 和 localStorage，拥有操作简单和强大的 API。[官网](https://github.com/mozilla/localForage)
* jStorage：jStorage 是一个简单的键值对数据库，用于在浏览器端存储数据。[官网](https://github.com/andris9/jStorage)
* cross-storage：获得权限后，能跨域名本地存储。[官网](https://github.com/zendesk/cross-storage)
* basket.js：用 localStorage 加载和缓存脚本的资源加载器。[官网](https://github.com/addyosmani/basket.js)
* bag.js：可以缓存脚本和加载资源，与 basket.js 相似，但增加了键值对接口和对 localStorage / websql / [官网](https://github.com/nodeca/bag.js)undexedDB 的支持。
* basil.js：智能的 JavaScript 数据持久层库。[官网](https://github.com/Wisembly/basil.js)
* jquery-cookie：轻量简单的、用于读取、编辑和删除 cookie 的 jQuery 插件。[官网](https://github.com/carhartl/jquery-cookie)
* Cookies：客户端 Cookie 操作库。[官网](https://github.com/ScottHamper/Cookies)
* DB.js：基于 Promise 的、封装了 IndexedDB 的库。[官网](https://github.com/aaronpowell/db.js/)
* lawnchair.js：简单的客户端 JSON 存储。[官网](https://github.com/brianleroux/lawnchair/)

<h3 id="color">颜色</h3>

* randomColor：JavaScript 颜色生成器。[官网](https://github.com/davidmerfield/randomColor)
* chroma.js：拥有各种各样颜色操作的 JavaScript 库。[官网](https://github.com/gka/chroma.js)
* color：JavaScript 颜色转换和操作库。[官网](https://github.com/MoOx/color)
* colors：更智能的默认 web 颜色。[官网](https://github.com/mrmrs/colors)
* PleaseJS：随机创建出赏心悦目的颜色和配色方案。[官网](https://github.com/Fooidge/PleaseJS)
* TinyColor：快速、轻巧的颜色操作和转换库。[官网](https://github.com/bgrins/TinyColor)
* Vibrant.js：从图像提取主要颜色。[官网](https://github.com/jariz/vibrant.js/)

<h3 id="i18n-and-l10n">国际化和本地化（I18n And L10n）</h3>

本地化和国际化 JavaScript 库

* i18next：JavaScript 最简单的国际化（i18n）方法。[官网](https://github.com/i18next/i18next)
* polyglot：小巧的国际化助手库。[官网](https://github.com/airbnb/polyglot.js)
* babelfish：i18n 提供友好易懂的 API ，并且内置多种支持。[官网](https://github.com/nodeca/babelfish/)

<h3 id="class">类</h3>

* ClassManager：世界上最快、最方便的类系统之一。[官网](https://github.com/kogarashisan/ClassManager)
* klass：用于创建极富表现力的类工具库。[官网](https://github.com/ded/klass)
* augment：世界上最小且最快的一流 JavaScript 继承模式。[官网](https://github.com/javascript/augment)

<h3 id="control-flow">控制流</h3>

* async：适用于 node 和浏览器的异步工具库。[官网](https://github.com/caolan/async)
* q：实现异步的 promise JavaScript 库。[官网](https://github.com/kriskowal/q)
* step：让逻辑顺序合理化的异步控制流库。[官网](https://github.com/creationix/step/)
* contra：利用函数风格实现的异步流控制。[官网](https://github.com/bevacqua/contra/)
* Bluebird：专注于革新功能和性能的，功能齐全的 promoise 库。[官网](https://github.com/petkaantonov/bluebird/)
* when：快速可靠的、Promises/A+ 规范的 when() 实现，而且拥有异步其它的优秀特性。[官网](https://github.com/cujojs/when)
* ObjectEventTarget：提供增加了事件监听的原型（与 DOMElement 的 EventTarget 在浏览器行为一致）。[官网](https://github.com/gartz/ObjectEventTarget)

<h3 id="routing">路由</h3>

* director：一个小巧的、与 URL 同构的路由器。[官网](https://github.com/flatiron/director)
* page.js：受 Express router 启发的小型客户端路由器（约为1200字节）。[官网](https://github.com/visionmedia/page.js)
* pathjs：简单、轻量的 web 路由器。[官网](https://github.com/mtrpcic/pathjs)
* crossroads：JavaScript 路由。[官网](https://github.com/millermedeiros/crossroads.js)
* davis.js：使用 pushState、RESTful 风格和可降级的 JavaScript 路由器。[官网](https://github.com/olivernn/davis.js)
* [angular-ui-router](http://hao.jobbole.com/angular-ui-router/)：基于AngularJS的可嵌套路由。[官网](http://angular-ui.github.io/ui-router/)
* react-router: Declarative routing for React [官方](https://github.com/ReactTraining/react-router)
* vue-router: Declarative routing for Vue [官方](https://router.vuejs.org/)

<h3 id="security">安全性</h3>

* DOMPurify：针对 HTML、MathML 和 SVG 的仅支持DOM、快速、高容错的 XSS 过滤器。[官网](https://github.com/cure53/DOMPurify)
* js-xss：通过白名单配置，即可过滤不信任的 HTML（防止 XSS 攻击）。[官网](https://github.com/leizongmin/js-xss)

<h3 id="log">日志</h3>

* log：带有样式的 Console.log。[官网](https://github.com/adamschwartz/log)
* Conzole：对 JavaScript 原生 console 对象方法和功能进行封装的 debug 面板，使其显示在页面内。[官网](https://github.com/Oaxoa/Conzole)
* console.log-wrapper：将日志清晰地记录到 console，且兼容所有浏览器。[官网](https://github.com/patik/console.log-wrapper)
* loglevel：最轻量的 JavaScript 日志记录工具库，向封装后可用的 console.log 方法增加可靠的日志等级。[官网](https://github.com/pimterry/loglevel)
* minilog：轻量的、用流式 API 显示的、可用于客户端和服务器端的日志记录库。[官网](http://mixu.net/minilog/)

<h3 id="regexp">正则表达式</h3>

* RegEx101：在线的 JavaScript 正则表达式测试器和调试器。同时支持 Python、PHP 和 PCRE。[官网](https://regex101.com/#javascript)
* RegExr：用于创建、测试和学习正则表达式的 HTML/JS  工具。[官网](http://regexr.com/)
* RegExpBuilder：使用链式方法创建正则表达式。[官网](https://github.com/thebinarysearchtree/regexpbuilderjs)

<h3 id="media">媒体</h3>

* Ion.Sound：可用于任何网页上简单音频。[官网](https://github.com/IonDen/ion.sound)

<h3 id="voice-command">语音命令</h3>

* annyang：向网站添加语音命令的语音识别库。[官网](https://github.com/TalAter/annyang)
* voix.js：向网站、app 或游戏添加语音命令的 JavaScript 库。[官网](https://github.com/pazguille/voix)

<h3 id="api">API</h3>

* bottleneck：强大的频率限制器，使调节流量变得更容易。[官网](https://github.com/SGrondin/bottleneck)
* oauth-signature-js：适用于 node 和 浏览器的 OAuth 1.0a 签名生成器。[官网](https://github.com/bettiolo/oauth-signature-js)
* amygdala：为 Web 应用提供 RESTful HTTP 客户端解决方案。[官网](https://github.com/lincolnloop/amygdala)
* jquery.rest：一个让 RESTful API 更易使用的 jQuery 插件。[官网](https://github.com/jpillora/jquery.rest)

<h3 id="vision-detection">视觉检测</h3>

* tracking.js：在 web 上实现计算视觉的一种现代方法。[官网](https://github.com/eduardolundgren/tracking.js)
* ocrad.js：通过 Emscripten 用 JavaScript 实现 OCR（光学字符识别）。[官网](https://github.com/antimatter15/ocrad.js)

<h3 id="browser-detection">浏览器检测</h3>

* bowser：一个浏览器检测器。[官网](https://github.com/ded/bowser)

<h3 id="performance-analysis">性能分析</h3>

* easy-monitor：一个轻量级实时 Node.js 项目的内核性能分析工具。[官网](http://www.easy-monitor.cn/document)

## UI

<h3 id="code-highlighting">代码高亮</h3>

* Highlight.js：JavaScript 语法高亮器。[官网](https://github.com/isagalaev/highlight.js)
* PrismJS：轻量、健壮和优雅的语法高亮器。[官网](https://github.com/PrismJS/prism)

<h3 id="loading-status">加载状态</h3>

指示加载状态的库。

* Mprogress.js：创建谷歌 Material 设计风格的线性进度条。[官网](https://github.com/lightningtgc/MProgress.js)
* NProgress：在 Ajax'y 应用显示细长型进度条[官网](http://ricostacruz.com/nprogress/)
* Spin.js：一个旋转的进度指示器。[官网](https://github.com/fgnass/spin.js)
* progress.js：为页面任何对象创建和管理进度条。[官网](https://github.com/usablica/progress.js)
* progressbar.js：用 SVG path 动画制作的、漂亮和响应式的进度条。[官网](https://github.com/kimmobrunfeldt/progressbar.js)
* pace：自动向你的网站添加一个进度条。[官网](https://github.com/HubSpot/pace)
* topbar：小巧漂亮的、与网站同宽的进度指示器。[官网](https://github.com/buunguyen/topbar)
* nanobar：非常轻量的进度条。不依赖 jQuery。[官网](https://github.com/jacoborus/nanobar)
* PageLoadingEffects：使用 SVG 动画展现新内容的现代方式。[官网](https://github.com/codrops/PageLoadingEffects)
* SpinKit：运用 CSS 动画的加载指示器集合。[官网](https://github.com/tobiasahlin/SpinKit)
* Ladda：内置在按钮的加载指示器。[官网](https://github.com/hakimel/Ladda)
* css-loaders：运用 CSS 动画的旋转加载指示器的集合。[官网](https://github.com/lukehaas/css-loaders)

除了上述这些库，还有收藏在 [Codepen](http://codepen.io/collection/HtAne/) 的，另外还有 [Ajaxload](http://www.ajaxload.info/)，[Preloaders](http://preloaders.net/) 和 [CSSLoad](http://cssload.net/) 这些生成器。

<h3 id="validation">验证</h3>

* Parsley.js：不用写一行 JavaScript 代码即可在前端验证表单。[官网](https://github.com/guillaumepotier/Parsley.js)
* jquery-validation：jQuery 验证插件。[官网](https://github.com/jzaefferer/jquery-validation)
* validator.js：字符串验证和过滤（在使用用户输入之前清理用户输入中的有害或危险字符的操作）。[官网](https://github.com/chriso/validator.js)
* validate.js：受 CodeIgniter 启发的轻量表单验证 JavaScript 库。[官网](https://github.com/rickharrison/validate.js)
* validatr：跨浏览器的 HTML5 表单验证库。[官网](https://github.com/jaymorrow/validatr/)
* BootstrapValidator：是验证表单域中最好的 jQuery 插件。要与 Bootstrap 3 一起使用。[官网](https://github.com/nghuuphuoc/bootstrapvalidator)
* [is.js](http://hao.jobbole.com/is-js/)：检查类型、正则表达式、是否存在、时间等。[官网](https://github.com/arasatasaygin/is.js)
* FieldVal：多用途验证库。同时支持同步和异步验证。[官网](https://github.com/FieldVal/fieldval-js)

<h3 id="keyboard-wrappers">键盘封装器</h3>

* mousetrap：处理键盘快捷键的 JavaScript 库。[官网](https://github.com/ccampbell/mousetrap)
* keymaster：定义和调度键盘快捷键的小型库。[官网](https://github.com/madrobby/keymaster)
* [hotkeys.js](https://github.com/jaywcjlove/hotkeys)：一个强健的 Javascript 库用于捕获键盘输入和输入的组合键，它易于使用，没有依赖。[官网](https://jaywcjlove.github.io/hotkeys/)
* Keypress：键入捕捉工具库，任何键都可以成为一个修饰健。[官网](https://github.com/dmauro/Keypress)
* KeyboardJS：一个用于绑定键盘组合的 JavaScript 库，让你脱离快捷键和快捷键组合冲突的痛苦。[官网](https://github.com/RobertWHurst/KeyboardJS)
* jquery.hotkeys：jQuery Hotkeys 能让你在代码任何的地方监听键盘事件，并几乎支持所有按键组合。[官网](https://github.com/jeresig/jquery.hotkeys)
* jwerty：令人惊叹的键盘事件处理库。[官网](https://github.com/keithamus/jwerty)

<h3 id="tours-and-guides">浏览和引导</h3>

* intro.js：这是一个介绍新功能的很好方式，能一步步地引导用户浏览你的网站和项目。[官网](https://github.com/usablica/intro.js)
* shepherd：通过引导让用户浏览你的应用程序。[官网](https://github.com/HubSpot/shepherd)
* bootstrap-tour：应用 Twitter Bootstrap 弹出框对产品进行快速简单的引导。[官网](https://github.com/sorich87/bootstrap-tour)
* tourist：简单、灵活的应用引导介绍库。[官网](https://github.com/easelinc/tourist)
* chardin.js：简单的应用遮罩层介绍。[官网](https://github.com/heelhook/chardin.js)
* pageguide：使用 jQuery 和 CSS3 的 web 页面元素交互引导库。[官网](https://github.com/tracelytics/pageguide)
* hopscotch：让开发者更容易向其页面产品添加引导的框架。[官网](https://github.com/linkedin/hopscotch)
* joyride：基于 jQuery 的功能引导插件。[官网](https://github.com/zurb/joyride)
* focusable：通过向页面其余部分添加遮罩层，使焦点聚集在特定 DOM 元素。[官网](https://github.com/zzarcon/focusable)

<h3 id="notifications">通知</h3>

* messenger：为你的应用添加 Growl-style 弹框和信息（Crowl 是 Mac OS X 下的一个通知系统）。[官网](https://github.com/HubSpot/messenger)
* noty：jQuery 通知插件。[官网](https://github.com/needim/noty)
* pnotify：适用于 Bootstrap、jQuery UI 和 Web Notifications Draft 的 JavaScript 通知库。[官网](https://github.com/sciactive/pnotify)
* toastr：用来显示简单的，会自动到期的信息窗口）简单的弹出框通知（[toast notifications](http://ux.stackexchange.com/questions/11998/what-is-a-toast-notification)[官网](https://github.com/CodeSeven/toastr)
* humane-js：一个简单、时髦的浏览器通知系统。[官网](https://github.com/wavded/humane-js)
* smoke.js：与框架无关的、能够自定义样式的 JavaScript 弹框系统。[官网](https://github.com/hxgf/smoke.js)

<h3 id="sliders">幻灯片</h3>

* Swiper：使用硬件加速过渡的移动设备触控滑块框架。[官网](https://github.com/nolimits4web/Swiper)
* slick：你所需要的最后一个轮播插件。[官网](https://github.com/kenwheeler/slick)
* slidesJs：响应式的 jQuery（1.7.1+）幻灯片插件，具有触摸、 CSS3 过渡等特性。[官网](http://www.slidesjs.com/)
* FlexSlider：一款令人惊叹的、全响应式的幻灯片 jQuery 插件。[官网](https://github.com/woothemes/FlexSlider)
* unslider：最简单的幻灯片 jQuery 插件。[官网](https://github.com/idiot/unslider)
* colorbox：轻量、可自定义的灯箱 jQuery 插件。[官网](https://github.com/jackmoore/colorbox)
* fancyBox：提供了良好优雅的方式，为页面上的图片、html 内容和多媒体添加缩放功能的工具。[官网](https://github.com/fancyapps/fancyBox)
* sly：基于项导航的、支持单向滚动的 JavaScript 库。[官网](https://github.com/darsain/sly)
* vegas：向页面添加漂亮的全屏背景的 jQuery 插件，甚至允许幻灯片。[官网](https://github.com/jaysalvat/vegas)
* Sequence：用于创建响应式的幻灯片、演示、旗帜广告和以步骤为基础的应用的 CSS 动画框架。[官网](https://github.com/IanLunn/Sequence)
* baguetteBox.js：易于使用的、用纯 JavaScript 实现的遮罩层脚本。[官网](https://github.com/feimosi/baguetteBox.js)
* reveal.js：用 HTML 创建漂亮演示控件的框架。[官网](https://github.com/hakimel/reveal.js)
* PhotoSwipe：适用于移动设备和桌面电脑的、模块化和不无依赖框架的 JavaScript 画廊控件。[官网](https://github.com/dimsemenov/PhotoSwipe)
* jcSlider：用 CSS 动画实现的响应式幻灯片 jQuery 插件。[官网](https://github.com/JoanClaret/jcSlider)
* basic-jquery-slider：易于使用、指定主题和定制化。[官网](https://github.com/jcobb/basic-jquery-slider)
* unslider： 这是最简单的幻灯片 jQuery 插件。[官网](https://github.com/idiot/unslider)
* viewerjs：原生js实现的图片查看器。[官网](https://fengyuanchen.github.io/viewerjs/)
* jQuery.adaptive-slider：带有自适应颜色标题和导航的幻灯片 jQuery 插件。[官网](https://github.com/creative-punch/jQuery.adaptive-slider/)
* slidr：可添加一些幻灯片效果。[官网](https://github.com/bchanx/slidr)
* Flickity：可触摸的、响应式的和可轻弹的画廊。[官网](https://github.com/metafizzy/flickity)

<h3 id="range-sliders">滑块控件</h3>

* Ion.RangeSlider：强大的、易于自定义的范围滑块选择库，支持很多配置和皮肤。[官网](https://github.com/IonDen/ion.rangeSlider)
* jQRangeSlider：支持日期的滑块选择库。[官网](https://github.com/ghusse/jQRangeSlider)
* noUiSlider：轻量无冗余的、高度定制化的滑块选择库。[官网](https://github.com/leongersen/noUiSlider)
* rangeslider.js：HTML5  input 区域滑块元素。[官网](https://github.com/andreruffert/rangeslider.js)

<h3 id="form-widgets">表单组件</h3>

### 输入

* typeahead.js：快速的、功能齐全的自动补全库。[官网](https://github.com/twitter/typeahead.js)
* tag-it：处理多标签字段以及标签建议/自动完成的 jQuery UI 插件。[官网](https://github.com/aehlke/tag-it)
* At.js：向你的应用添加类似 Github 的自动完成提示功能。[官网](https://github.com/ichord/At.js)
* Placeholders.js：JavaScript 补全 HTML5 占位符的属性。[官网](https://github.com/jamesallardice/Placeholders.js)
* fancyInput：利用 CSS3 效果让输入更有趣。[官网](https://github.com/yairEO/fancyInput)
* jQuery-Tags-Input：利用这个 jQuery 插件，可奇妙地将一个简单的文本输入转换成一个酷酷的标签列表。[官网](https://github.com/xoxco/jQuery-Tags-Input)
* vanilla-masker：一个纯 JavaScript 实现的输入控制库。[官网](https://github.com/BankFacil/vanilla-masker)
* Ion.CheckRadio：一个为复选框和单选按钮添加样式的 jQuery 库，支持多种皮肤。[官网](https://github.com/IonDen/ion.checkRadio)

### 日历

* pickadate.js：对移动设备友好的、响应式的和轻量的 jQuery 日期 &amp; 时间输入选择器。[官网](https://github.com/amsul/pickadate.js)
* bootstrap-datepicker：基于 bootstrap 的日历选择器。[官网](https://github.com/eternicode/bootstrap-datepicker)
* Pikaday：一个崭新的 JavaScript 日期选择器 —— 轻量、无依赖和模块化的 CSS。[官网](https://github.com/dbushell/Pikaday)
* fullcalendar：全尺寸、支持拖放事件的日历（jQuery 插件）。[官网](https://github.com/fullcalendar/fullcalendar)
* rome：可定制的日期（和时间）选择器。无依赖，可选 UI。[官网](https://github.com/bevacqua/rome)
* datedropper： datedropper 是一个 jQuery 插件，它提供了快速简易的方式去管理日期输入框。[官网](https://github.com/felicegattuso/datedropper)
* flatpickr： flatpickr 是一个轻量、强大、无依赖的日历和时间选择器插件，支持移动端，并支持React、Ember、Angular和Vue。[官网](https://chmln.github.io/flatpickr/)

### 选择

* selectize.js：Selectize 是文本框和选择框的混合体。它基于jQuery，拥有自动完成和键盘感应下拉列表功能，可用于标签、联系人列表等。[官网](https://github.com/brianreavis/selectize.js)
* select2：它基于 jQuery，是选择框（select box）的替代品。支持搜索、远程数据集和无限滚动。[官网](https://github.com/select2/select2)
* chosen：可以让冗长不便的选择框更友好的库。[官网](https://github.com/harvesthq/chosen)

### 文件上传

* jQuery-File-Upload：File Upload 是一个支持多文件选择、文件拖放、进度条、验证和图片、音频、视频预览的 [官网](https://github.com/blueimp/jQuery-File-Upload)jQuery 插件。
* dropzone：Dropzone 是一个易于使用且支持多文件拖放的库。其支持图片预览并且拥有很好的进度条效果。[官网](https://github.com/enyo/dropzone)
* flow.js：一个通过 HTML5 的 File API ，提供多个同时链接的、稳定的、容错的、可恢复的/可重新开始的文件上传库。[官网](https://github.com/flowjs/flow.js)
* fine-uploader：一个带有进度条、拖放功能和支持直接上传到 S3 （Amazon Simple Storage Service，亚马逊简易存储服务）的多文件上传插件。[官网](https://github.com/FineUploader/fine-uploader)
* FileAPI：JavaScript 文件工具集合。支持多文件上传、拖放和文件分块上传。对于图像，支持裁剪、调整大小和根据 [EXIF](http://baike.baidu.com/view/22006.htm) 自动调整方向。[官网](https://github.com/mailru/FileAPI)
* plupload：处理文件上传的 JavaScript [官网](https://github.com/moxiecode/plupload)API，其支持多文件选择、文件类型过滤、分块请求、客户端图片缩放和根据不同的运行环境选择 HTML5、Silverlight 和 Flash。

### 其它

* form：jQuery 表单插件。[官网](https://github.com/malsup/form)
* Garlic.js：自动在本地保存表单文本和选择框的值，直到表单被提交。[官网](https://github.com/guillaumepotier/Garlic.js)
* Countable：对某个 HTML 元素包含文本的段落数、单词数和字符数进行统计的 JavaScript 函数。[官网](https://github.com/RadLikeWhoa/Countable)
* card：只需一行代码，让信用卡表单变得更友好。[官网](https://github.com/jessepollak/card)
* stretchy：自适应大小的 form 元素，表单本应该是这样的。[官网](https://github.com/LeaVerou/stretchy)
* list.js：向表格、列表等 HTML 元素添加搜索、排序、过滤和自适应功能的库。在已有 HTML 上增加可视化。[
 ](http://www.listjs.com/)[官网](https://github.com/javve/list.js)

<h3 id="tips">提示</h3>

* tipsy：基于 jQuery 的 Fackbook 风格的提示工具（tooltip）。[官网](https://github.com/jaz303/tipsy)
* opentip：开源且基于 prototype 框架的 JavaScript 工具提示库。[官网](https://github.com/enyo/opentip)
* qTip2：非常强大的工具提示库。[官网](https://github.com/qTip2/qTip2)
* tooltipster：一个工具提示 jQuery 插件。[官网](https://github.com/iamceege/tooltipster)
* simptip：用 Sass 制作的、简单的工具提示。[官网](https://github.com/arashmanteghi/simptip)
* jquery-popup-overlay：是一个响应式的和可访问性强的模态框（modal）和工具提示框 jQuery 插件。[官网](https://github.com/vast-engineering/jquery-popup-overlay)

<h3 id="modals-and-popups">模态框和弹出框</h3>

* Magnific-Popup：专注于性能、轻量、响应式的灯箱（lightbox）脚本。[官网](https://github.com/dimsemenov/Magnific-Popup)
* jquery-popbox：jQuery 提示框插件。[官网](https://github.com/gristmill/jquery-popbox)
* jquery.avgrund.js：一种新的定于弹出的模态框 jQuery 插件。[官网](https://github.com/voronianski/jquery.avgrund.js)
* vex：新的、拥有高度可配置和易于改变样式功能的对话框库。[官网](https://github.com/HubSpot/vex)
* bootstrap-modal：对 Bootstrap 默认的模态框类进行扩展。其支持响应式、可堆叠和 ajax 等。[官网](https://github.com/jschr/bootstrap-modal)
* css-modal：纯 CSS 打造的模态框。[官网](https://github.com/drublic/css-modal)
* jquery-popup-overlay：是一个响应式的和可访问性强的模态框和工具提示框（tooltips）jQuery 插件。[官网](https://github.com/vast-engineering/jquery-popup-overlay)
* layer：国内最多人使用的web弹层组件。[官网](https://github.com/sentsin/layer/)

<h3 id="scroll">滚动</h3>

* scrollMonitor：滚动发生时，可以监听元素的、简单、快速的 API。[官网](https://github.com/sakabako/scrollMonitor)
* headroom：除非你需要显示页面头部（header），否则将隐藏它，以腾出页面头部空间。[官网](https://github.com/WickyNilliams/headroom.js)
* onepage-scroll：创建一个类似 Apple 的单页面滚动网站（iPhone 5S  网站）。[官网](https://github.com/peachananr/onepage-scroll)
* iscroll：高性能、轻量、无依赖、兼容多平台的 JavaScript 滚动组件。[官网](https://github.com/cubiq/iscroll)
* skrollr：独立（不依赖 jQuery） 的视差滚动库，适用于移动设备（Android + iOS）和桌面电脑。[官网](https://github.com/Prinzhorn/skrollr)
* parallax：面向智能设备的视差引擎。[官网](https://github.com/wagerfield/parallax)
* stellar.js：让视差滚动变简单。[官网](https://github.com/markdalgleish/stellar.js)
* plax：基于 jQuery 的视差库。[官网](https://github.com/cameronmcefee/plax)
* jparallax：创建可交互视差效果的 jQuery 插件。[官网](https://github.com/stephband/jparallax)
* fullPage：简单和易于使用的、用于创建全屏滚动网站的插件（也被称为单页面网站）。[官网](https://github.com/alvarotrigo/fullPage.js)
* ScrollMenu：让老旧无聊的滚动条焕然一新。[官网](https://github.com/s-yadav/ScrollMenu)

<h3 id="menu">菜单</h3>

* jQuery-menu-aim：当用户光标放在特定下拉菜单项时触发事件。可制作响应式的、大数据量的下拉菜单，如 Amazon 的。[官网](https://github.com/kamens/jQuery-menu-aim)
* jQuery contextMenu：右键菜单（contextMenu） 管理工具。[官网](https://github.com/swisnl/jQuery-contextMenu)
* Slideout：为移动设备的 web 应用制作出响应式的、可触摸滑出的导航菜单。[官网](https://github.com/mango/slideout)
* Slide and swipe：一个基于 touchSwipe 库的滑出菜单插件。[官网](https://github.com/JoanClaret/slide-and-swipe-menu)

<h3 id="table-grid">表格/栅格</h3>

* jTable：基于 CRUD 表创建 AJAX 的 jQuery 插件。[官网](https://github.com/hikalkan/jtable)
* DataTables：这是一个非常灵活的工具，在渐进增强的基础上，将高级的交互效果加到 HTML 表格。（jQuery 插件）[官网](http://www.datatables.net/) 
* floatThead：（jQuery 插件）锁定表格头部，只允许表格内容滚动。适用于任何表格，而且不需要额外的 html 或 css。[官网](https://github.com/mkoryak/floatThead)
* Masonry：瀑布流式的网格布局库。[官网](http://masonry.desandro.com/)
* Packery：使用装箱算法（bin-packing）的网格布局库。支持拖拽布局。[官网](http://packery.metafizzy.co/)
* Isotope：可过滤和可排序的网格布局的库，它能实现 Masonry、Packery 等布局。[官网](http://isotope.metafizzy.co/)

<h3 id="frameworks-1">框架</h3>

* Semantic UI：拥有大量主题和元素的 UI 套件。[官网](http://semantic-ui.com/)

<h3 id="gesture">手势</h3>

* hammer.js：拥有多种触摸手势的 JavaScript 库。[官网](https://github.com/hammerjs/hammer.js)
* touchemulator：在桌面电脑模仿触摸输入。[官网](https://github.com/hammerjs/touchemulator)
* Dragula：超级易于使用的拖拽库。[官网](https://github.com/bevacqua/dragula/)

<h3 id="touch">触摸</h3>

* fastclick.js：去除触屏用户300ms点击延误。[官网](https://github.com/ftlabs/fastclick)
* dropload.js：移动端下拉刷新，上拉加载更多。[官网](https://github.com/ximan/dropload)
* touchslide.js：触屏滑动特效。[官网](http://www.superslide2.com/touchSlide/)

<h3 id="maps">地图</h3>

* Leaflet：对移动设备友好的、可交互的地图 JavaScript 库。[官网](https://github.com/Leaflet/Leaflet)
* Cesium：开源的、基于 WebGL 实现的虚拟地球仪和地图引擎。[官网](https://github.com/AnalyticalGraphicsInc/cesium)
* gmaps：以最简单的方式使用 Google 地图。[官网](https://github.com/HPNeo/gmaps)
* polymaps：一个免费的、兼容现代 web 浏览器的、用于制作动态可交互的地图 JavaScript 库。[官网](https://github.com/simplegeo/polymaps)
* kartograph.js：开源的 Kartograph SVG 地图渲染器。[官网](https://github.com/kartograph/kartograph.js)
* mapbox.js：Mapbox 的 API，Leaflet 的插件。[官网](https://github.com/mapbox/mapbox.js)
* jqvmap：矢量地图 jQuery 插件。[官网](https://github.com/manifestinteractive/jqvmap)
* OpenLayers3：高性能的、功能丰富的库，能满足你对地图所有需求。[官网](http://openlayers.org/)

<h3 id="video-audio">视频/音频</h3>

* prettyembed.js：更完美地嵌入 YouTube —— 拥有很好的选项，如高分辨率的预览图、嵌入选项的高级定制和可选的 [官网](https://github.com/mike-zarandona/prettyembed.js)FitVids 支持。
* [html5media](http://hao.jobbole.com/html5media/)：能在所有主流浏览器播放多媒体标签中定义的多媒体文件。[官网](https://github.com/etianen/html5media)
* Play-em JS：Play'em 是一个 JavaScript 组件，它能管理音乐/视频播放顺序，通过在一个 DIV 元素里嵌入几个播放器（Youtube、Soundcloud 和 Vimeo）来控制一系列歌曲的播放。[官网](https://github.com/adrienjoly/playemjs)
* polyplayer：将 YouTube、Soundcloud 和 Vimeo 播放器的 API 统一成一套。[官网](https://github.com/Acconut/polyplayer)
* flowplayer： HTML5 视频播放器 [官网](https://flowplayer.org/)、[Github](https://github.com/flowplayer/flowplayer)
* mediaelement：让 HTML5、 Flash 播放器和模仿 HTML5 媒介元素 API 的 Silverlight shim，在所有浏览器拥有一致的 UI。[官网](http://mediaelementjs.com/)、[Github](https://github.com/johndyer/mediaelement)
* SoundJS：让音频在 web 上运行更简单的库。它为不同浏览器提供了一致的 API。[官网](https://github.com/CreateJS/SoundJS)

<h3 id="animations">动画</h3>

* [velocity](http://hao.jobbole.com/velocity-js/)：加速 JavaScript 动画。[官网](https://github.com/julianshapiro/velocity)
* [jquery.transit](http://hao.jobbole.com/jquery-transit/)：拥有超级流畅的 CSS3 变换和过渡的 jQuery 插件。[官网](https://github.com/rstacruz/jquery.transit)
* impess.js：在 HTML 文档里，运用 CSS3 变换和过渡制作类似 Prezi 的展现效果。[官网](https://github.com/impress/impress.js)
* [bounce.js](http://hao.jobbole.com/bounce-js/)：可以立刻创建有趣的 CSS3 动画。[官网](https://github.com/tictail/bounce.js)
* GreenSock-JS：适用于所有主流浏览器的高性能 HTML5 动画。[官网](https://github.com/greensock/GreenSock-JS)
* TransitionEnd：TransitionEnd 是一个运用 transitonend 事件的、跨浏览器的库。[官网](https://github.com/EvandroLG/transitionEnd)
* [Dynamics.js](http://hao.jobbole.com/dynamics-js/)：用于创建基于物理知识的 CSS 动画库。[官网](https://github.com/michaelvillar/dynamics.js)

<h3 id="image-processing">图片处理</h3>

* [lena.js](http://hao.jobbole.com/lena-js/)：拥有滤镜和实用功能的图像处理库。[官网](https://github.com/davidsonfellipe/lena.js)
* [pica](http://hao.jobbole.com/pica/)：高质量地调整图片大小（拥有快速的、纯 JS 实现的 Lanczos 滤镜算法）。[官网](https://github.com/nodeca/pica)
* cropper：一个简单的图像裁剪 jQuery 插件。[官网](https://github.com/fengyuanchen/cropper)
* AlloyImage：腾讯前端开源的基于HTML5的专业级图像处理开源引擎。[官网](https://github.com/AlloyTeam/AlloyImage)

<h3 id="es6">ECMAScript 6</h3>

* [es6features](http://hao.jobbole.com/ecmascript-6/)：ECMAScript 6 特性概述。[官网](https://github.com/lukehoban/es6features)
* es6-features：ECMAScript 6:  特性概述和比较。[官网](https://github.com/rse/es6-features)
* ECMAScript 6 compatibility table ：Compatibility tables 展示了各种平台上所有 ECMAScript 6 特性的支持程度。[官网](http://kangax.github.io/compat-table/es6/)
* Babel (Formerly 6to5)：将 ES6+ 代码转换成纯 ES5。[官网](https://github.com/babel/babel)
* Traceur compiler：ES6 特性转 ES5。包括 classes、generators、promises、destructuring [官网](https://github.com/google/traceur-compiler)patterns、default parameters 等。

<h3 id="sdk">软件开发工具包(SDK)</h3>

* javascript-sdk-design：从工作和个人经验中提炼出来的 JavaScript SDK 设计指导。[官网](https://github.com/huei90/javascript-sdk-design)

<h3 id="misc">大杂烩</h3>

* echo：利用 data-* 属性延迟加载图片。[官网](https://github.com/toddmotto/echo)
* picturefill：响应式图片显示插件，使浏览器支持 srcset、size 属性。[官网](https://github.com/scottjehl/picturefill)
* platform.js：一个平台检测库，几乎适用于所有 JavaScript 平台。[官网](https://github.com/bestiejs/platform.js)
* [json3](http://hao.jobbole.com/json3/)：一个现代 JSON 实现库，几乎兼容所有 JavaScript 平台。[官网](https://github.com/bestiejs/json3)
* Logical Or Not：一个关于 JavaScript 特性的游戏。[官网](http://gabinaureche.com/logicalornot/)
* BitSet.js：实现位向量的 JavaScript 库。[官网](https://github.com/infusion/BitSet.js)
* [Edge.js](http://hao.jobbole.com/edge-js/)：运行在一个进程中运行.NET和Node.js代码。[官网](http://tjanczuk.github.io/edge/)、[GitHub](https://github.com/tjanczuk/edge)

<h2 id="worth-reading">精品阅读</h2>

* braziljs/js-the-right-way：[官网](https://github.com/braziljs/js-the-right-way/)
* JSbooks：[官网](https://github.com/revolunet/JSbooks)
* Superhero.js：关于创建、测试和维护一个大型 JavaScript 代码库的资源集。[官网](http://superherojs.com/)
* 《[前端开发者都应知道的 jQuery 小技巧](http://web.jobbole.com/84028/)》
* 《[常用的 Javascript 设计模式](http://web.jobbole.com/29454/)》
* 《[10 个 jQuery 图表插件推荐](http://web.jobbole.com/21136/)》
* 《[理解 JavaScript 原型](http://web.jobbole.com/9648/)》
* 《[只有20行Javascript代码！手把手教你写一个页面模板引擎](http://web.jobbole.com/56689/)》
* 《[编写快速、高效的JavaScript代码](http://web.jobbole.com/31951/)》
* 《[45个实用的JavaScript技巧、窍门和最佳实践](http://web.jobbole.com/54495/)》
* 《[为现代JavaScript开发做好准备](http://web.jobbole.com/66135/)》
* 《[给JavaScript初学者的24条最佳实践](http://web.jobbole.com/53199/)》

<h1 id="resources">资源</h1>

<h3 id="influential-books">有影响力的书</h3>

*具有广泛影响且值得阅读的前端经典书籍。*

* 《[Limu：JavaScript 的那些书](http://web.jobbole.com/8087/)》
* 《你不知道的Javascript》：英文版 "You Don't Know JS"

<h3 id="websites">知名网站</h3>

*值得关注的前端技术站点。*

<h4>中文站点</h4>

* 伯乐在线前端频道：伯乐前端分享 Web 前端开发，包括 JavaScript、CSS 和 HTML5 开发技术，前端相关的行业动态。[官网](http://web.jobbole.com/)

<h4>英文站点</h4>

待补充

<h3 id="weibo-weixin">微博、微信公众号</h3>

* 前端大全 微博：[@前端大全](http://weibo.com/u/5261893910)
* 前端大全：专注分享Web前端相关的内容，包括 JavaScript, CSS 和 HTML5 技术文章、工具资源、精选课程和Web技术领域热点资讯。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c688tqj2046046mx8.jpg" width=150 height=150>
* UI设计达人：分享 UI 设计精选文章、案例、行业趋势、课程和书籍。<br><img src="http://ww4.sinaimg.cn/mw690/bfdcef89gw1evuvyehtx4j2076076q3e.jpg" width=150 height=150>
* 网页设计精选：分享网页设计精选文章、案例、行业趋势、课程和书籍。<br><img src="http://ww2.sinaimg.cn/mw690/bfdcef89gw1evuvyhsikmj2076076dgb.jpg" width=150 height=150>
