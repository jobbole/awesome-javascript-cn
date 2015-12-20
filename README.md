# JavaScript 资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。awesome-javascript 是 sorrycc 发起维护的 JS 资源列表，内容包括：包管理器、加载器、测试框架、运行器、QA、MVC框架和库、模板引擎、数据可视化、时间轴、编辑器等等

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-javascript 列表，我们将对其中的各个资源项进行编译整理。此外还将从其他来源补充好资源。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hao.jobbole.com/)。可参考已整理的内容：
  - 《[jQWidgets：jQuery HTML5 UI组件框架](http://hao.jobbole.com/jqwidgets-jquery-html5-ui/)》
  - 《[Bootstrap：Web前端开发框架](http://hao.jobbole.com/bootstrap/)》
  - 《[YUI Compressor：JS/CSS压缩工具](http://hao.jobbole.com/yui-compressor/)》

* * *

### 如何参与本项目？

从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 在用 JavaScript；

如有兴趣，请加 QQ：_______。加 Q 时请注明「JS大全」

* * *

### 本项目的参与者

- 维护者：[tangyouhua](https://github.com/tangyouhua)

- 贡献者：You

注：名单不分排名，不定期补充更新

* * *
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

管理着 javascript 库，并提供读取和打包它们的工具。

* [npm](https://www.npmjs.com/) - npm 是 javascript 的包管理器。
* [Bower](https://github.com/bower/bower) - 一个 web 应用的包管理器。
* [component](https://github.com/component/component) - 能构建更好 web 应用的客户端包管理器。
* [spm](https://github.com/spmjs/spm) - 全新的静态包管理器。
* [jam](https://github.com/caolan/jam) - 一个专注于浏览器端和兼容 RequireJS 的包管理器。
* [jspm](https://github.com/jspm/jspm-cli) - 流畅的浏览器包管理器。
* [Ender](https://github.com/ender-js/Ender) - 没有库文件的程序库。
* [volo](https://github.com/volojs/volo) - 以项目模板、添加依赖项与自动化生成的方式创建前端项目。
* [Duo](https://github.com/duojs/duo) - 一个整合 Component、Browserify 和 Go 的最佳思想，使开发者能快速方便地组织和编写前端代码的下一代包管理器。

<h2 id="loaders">加载器</h2>

JavaScript 的模块或加载系统。

* [RequireJS](https://github.com/jrburke/requirejs) - JavaScript 文件和模块的加载器。
* [browserify](https://github.com/substack/node-browserify) - 在浏览器端以 node.js 的方式 require()。
* [SeaJS](https://github.com/seajs/seajs) - 用于 Web 的模块加载器。
* [HeadJS](https://github.com/headjs/headjs) - HEAD 的唯一脚本。
* [curl](https://github.com/cujojs/curl) - 小巧、快速且易扩展的模块加载器，它能处理 AMD、CommonJS Modules/1.1、CSS、HTML/text 和历史脚本。
* [lazyload](https://github.com/rgrove/lazyload/) - 小巧且无依赖的异步 JavaScript 和 CSS 加载器。
* [script.js](https://github.com/ded/script.js) - 异步 JavaScript 加载器和依赖管理器。
* [systemjs](https://github.com/systemjs/systemjs) - AMD、CJS（commonJS） 和符合 ES6 规范的模块加载器。
* [LodJS](https://github.com/yanhaijing/lodjs) - 基于 AMD 的模块加载器。
* [ESL](https://github.com/ecomfe/esl) - 浏览器端的模块加载器，支持延迟定义和 AMD。
* [modulejs](https://github.com/lrsjng/modulejs) - 轻量的 JavaScript 模块系统。

<h2 id="bundlers">打包工具</h2>

* [browserify](https://github.com/substack/node-browserify) - Browserify 让你能在浏览器端使用 require('modules') ，打包所有依赖。
* [webpack](https://github.com/webpack/webpack) - 为浏览器打包 CommonJs/AMD 模块。

<h2 id="testing-frameworks">测试框架</h2>

### 框架

* [mocha](https://github.com/visionmedia/mocha) - 适用于 node.js 和浏览器、简易、灵活、有趣的 JavaScript 测试框架。
* [jasmine](https://github.com/pivotal/jasmine) - 简单无 DOM 的 JavaScript 测试框架。
* [qunit](https://github.com/jquery/qunit) - 一个易于使用的 JavaScript 单元测试框架。
* [jest](http://github.com/facebook/jest) - 简单的 JavaScript 单元测试框架。
* [prova](http://github.com/azer/prova) - 基于 Tape 和 Browserify 的测试运行器，它适用于 Node &amp; 浏览器。
* [DalekJS](https://github.com/dalekjs/dalek) - 自动化且跨浏览器的 JavaScript 功能测试框架。

### 断言

* [chai](https://github.com/chaijs/chai) - 适用于 node.js 和浏览器的 BDD / TDD 断言框架，并能搭配其它测试框架使用。
* [Sinon.JS](https://github.com/cjohansen/Sinon.JS) - 对 JavaScript 进行 spies、stubs 和 mock 测试。
* [expect.js](https://github.com/LearnBoost/expect.js) - 简约的、适用于 Node.js 和浏览器端的 BDD 式断言工具。

### 覆盖率

* [istanbul](https://github.com/gotwarlost/istanbul) - 另一个 JS 代码覆盖率检测工具。
* [blanket](https://github.com/alex-seville/blanket) - 一个简单的代码覆盖率检测库。它的设计理念是易于安装和使用，且可用于浏览器端和 node.js。
* [JSCover](https://github.com/tntim96/JSCover) - JSCover 是一个检测 JavaScript 程序代码覆盖率的工具。

### 运行器

* [phantomjs](https://github.com/ariya/phantomjs) - 脚本化的 Headless WebKit。
* [slimerjs](https://github.com/laurentj/slimerjs) - 一个内核为 Gecko 的类似 PhantomJS 工具。
* [casperjs](https://github.com/n1k0/casperjs) - 基于 PhantomJS 和 Slimer JS 的导航脚本和测试工具。
* [zombie](https://github.com/assaf/zombie) - 基于 node.js 、快速、全栈且无图形界面的浏览器的测试工具。
* [totoro](https://github.com/totorojs/totoro) - 一个简单可靠且能跨浏览器运行的测试工具。
* [karma](https://github.com/karma-runner/karma) - 一个优秀的的 JavaScript 测试运行器。
* [nightwatch](https://github.com/beatfactor/nightwatch) - 基于 node.js 和 selenium webdriver 的图形界面自动化测试框架。
* [intern](https://github.com/theintern/intern) - 下一代 JavaScript 代码测试栈。
* [yolpo](http://www.yolpo.com/) - 在浏览器逐句执行的 JavaScript 解释器。

<h2 id="qa-tools">QA 工具</h2>

* [JSHint](https://github.com/jshint/jshint/) - JSHint 是一个有助于发现 JavaScript 代码错误和潜在问题的工具。
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript 代码风格检测工具。
* [jsfmt](https://github.com/rdio/jsfmt) - 格式化、搜索和改写 JavaScript。
* [jsinspect](https://github.com/danielstjules/jsinspect) - 检测复制粘贴和结构类似的代码。
* [buddy.js](https://github.com/danielstjules/buddy.js) - 发现 JavaScript 代码里的 [魔术数字](https://zh.wikipedia.org/wiki/%E9%AD%94%E8%A1%93%E6%95%B8%E5%AD%97)。
* [ESLint](https://github.com/eslint/eslint) - 完全插件化的工具，能在 JavaScript 中识别和记录模式。
* [JSLint](https://github.com/douglascrockford/JSLint) - 高标准、严格和固执的代码质量工具，旨在只保持语言的优良部分。

<h2 id="mvc-frameworks-and-libraries">MVC 框架和库</h2>

* [angular.js](https://github.com/angular/angular.js) - 为网络应用增强 HTML。
* [aurelia](http://aurelia.io/) - 一个适用于移动设备、桌面电脑和 web 的客户端 JavaScript 框架。
* [backbone](https://github.com/jashkenas/backbone) - 给你的 JS 应用加入带有 Models、Views、Collections 和 Events 的 Backbone。
* [batman.js](http://batmanjs.org/) - 最适合 Rails 开发者的 JavaScript 框架。
* [ember.js](https://github.com/emberjs/ember.js) - 一个旨在创建非凡 web 应用的 JavaScript 框架。
* [meteor](https://github.com/meteor/meteor) - 一个超简单的、数据库无处不在的、只传输数据的纯 JavaScript web 框架。
* [ractive](https://github.com/ractivejs/ractive) - 新一代 DOM 操作。
* [vue](https://github.com/yyx990803/vue) - 一个用于构建可交互界面的、直观快速和可组合的 MVVM 框架。
* [knockout](https://github.com/knockout/knockout) - Knockout 用 JavaScript 让创建响应式的富 UI 更加容易。
* [spine](https://github.com/spine/spine) - 构建 JavaScript 应用的轻量 MVC 库。
* [espresso.js](https://github.com/techlayer/espresso.js) - 一个极小的、用于制作用户界面的 JavaScript 库。
* [canjs](https://github.com/bitovi/canjs) - 让 JS 更好、更快、更简单。
* [react](https://facebook.github.io/react/) - 用于建构用户界面的库。它是声明式的、高效的和极度灵活的，并使用虚拟 DOM 作为其不同的实现。
* [react-native](https://github.com/facebook/react-native) - 一个用 React 构建原生应用的框架。
* [riot](https://github.com/riot/riot) - 类 React 库，但很轻量。
* [thorax](https://github.com/walmartlabs/thorax) - 加强你的 Backbone。
* [chaplin](https://github.com/chaplinjs/chaplin) - 使用 Backbone.js 库的 JavaScript 应用架构。
* [marionette](https://github.com/marionettejs/backbone.marionette) - 一个 Backbone.js 的复合应用程序库，旨在简化大型 JavaScript 应用结构。
* [ripple](https://github.com/ripplejs/ripple) - 一个小巧的、用于构建响应界面的基础框架。
* [rivets](https://github.com/mikeric/rivets) - 轻量却拥有强大的数据绑定和模板解决方案
* [derby](https://github.com/derbyjs/derby) - 让编写实时和协同应用更简单的 MVC 框架，能够在 Node.js 和浏览器同时运行。
    * [derby-awesome](https://github.com/onerussell/awesome-derby) - 很棒的 derby 组件集合。
* [way.js](https://github.com/gwendall/way.js) - 简单、轻量、持久化的双向数据绑定。
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril 是一个客户端 MVC 框架（轻量、强大和快速）
* [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks 是一个更好的 MV-ish 框架。
* [LiquidLava](http://www.lava-framework.com/) - 易懂的、用于构建用户界面的 MVC 框架。

<h2 id="node-powered-cms-frameworks">基于 Node 的 CMS 框架</h2>

* [KeystoneJS](https://github.com/keystonejs/keystone) - 强大的 CMS 和 web 应用框架。
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - 拥有实时的架构和设计的响应式（reactive） CMS。
* [Ghost](https://github.com/tryghost/Ghost) - 简单、强大的发布平台。
* [Apostrophe](https://github.com/punkave/apostrophe) - 提供内容编辑和基本服务的 CMS。
* [We.js](https://github.com/wejs/we/) - 适用于实时应用、网站或博客的框架。
* [Hatch.js](https://github.com/inventures/hatchjs) - 拥有社交特性的 CMS 平台。
* [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) - 拥有快速、极简风格特点且基于Node.js 的 CMS。
* [Nodizecms](https://github.com/nodize/nodizecms) - 为 CoffeeScript 爱好者准备的 CMS。
* [Cody](https://github.com/jcoppieters/cody) - 拥有所见即所得的编辑器的 CMS。
* [PencilBlue](https://github.com/pencilblue/pencilblue/) - CMS 和博客平台。

<h2 id="templating-engines">模板引擎</h2>

模板引擎允许您执行字符串插值。

* [mustache.js](https://github.com/janl/mustache.js) - 是 JavaScript 中带有 {{mustaches}} 的最简模板。
* [handlebars.js](https://github.com/wycats/handlebars.js/) - 是 Mustache 模板语言的扩展。
* [hogan.js](https://github.com/twitter/hogan.js) - 是 Mustache 模板语言的编译器。
* [doT](https://github.com/olado/doT) - 最快速简洁的 JavaScript 模板引擎，适用于 nodejs 和浏览器。
* [dustjs](https://github.com/linkedin/dustjs/) - 适用于浏览器和 node.js 的异步模板。
* [eco](https://github.com/sstephenson/eco/) - 嵌入式的 CoffeeScript 模板。
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - 轻量（小于 1KB）、快速且无依赖的强大 JavaScript 模版引擎。
* [t.js](https://github.com/jasonmoo/t.js) - 小巧的 JavaScript 模板框架，压缩后约为 400 字节。
* [Jade](https://github.com/jadejs/jade) - 健壮的、优雅且功能丰富的 nodejs 模板引擎。
* [EJS](https://github.com/mde/ejs) - 高效的 JavaScript 模板。
* [xtemplate](https://github.com/xtemplate/xtemplate) - 可扩展的模板引擎，适用于 node 和浏览器。
* [marko](https://github.com/marko-js/marko) - 快速轻量且基于 HTML 的模板引擎，支持异步、流、自定义标签和 CommonJS 模编译后输出。适用于 Node.js 和浏览器。

<h2 id="data visualization">数据可视化</h2>

Web 数据可视化工具

* [d3](https://github.com/mbostock/d3) - 一个对 HTML 和 SVG 进行可视化的 JavaScript 库。
* [metrics-graphics](https://github.com/mozilla/metrics-graphics) - 更简洁和拥有更规范的数据图表布局优化算法的库。
* [pykcharts.js](https://github.com/pykih/PykCharts.js) - 经过精心设计后，去除 d3.js 复杂性的 d3.js 图表库。
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D 库。
* [Chart.js](https://github.com/nnnick/Chart.js) - 简单的、基于 canvas 标签的 HTML5 图表库。
* [paper.js](https://github.com/paperjs/paper.js) - 是矢量图形脚本中的瑞士军刀 —— 使用 HTML5 Canvas 将 Scriptographer  移植到 JavaScript 和浏览器。
* [fabric.js](https://github.com/kangax/fabric.js) - JavaScript Canvas 库，SVG 与 Canvas 可以相互解析。
* [peity](https://github.com/benpickles/peity) - 进度条、线状和饼状图。
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript 矢量库。
* [echarts](https://github.com/ecomfe/echarts) - 商业产品图表。
* [vis](https://github.com/almende/vis) - 动态的、基于浏览器的可视化库。
* [two.js](https://github.com/jonobr1/two.js) - 一个渲染器无关的适用于 web 的二维绘图 api 。
* [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) - 基于 Raphaël 图表库。
* [sigma.js](https://github.com/jacomyal/sigma.js) - 一个致力于图形绘画的 JavaScript 库。
* [arbor](https://github.com/samizdatco/arbor) - 一个使用 web workers 和 jQuery 的图形可视化库。
* [cubism](https://github.com/square/cubism) - 可视化时间序列的 D3 插件。
* [dc.js](https://github.com/dc-js/dc.js) - 与 crossfilter 无缝合作的多维图表绘制库，使用 d3.js 渲染。
* [vega](https://github.com/trifacta/vega) - 一套可视化语法。
* [processing.js](http://processingjs.org/) - Processing.js 基于 Web 标准使数据可视化，而无需任何插件。
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) - 动态的 HTML5 可视化。
* [rickshaw](https://github.com/shutterstock/rickshaw) - 用于构建交互式实时图表的 JavaScript 工具包。
* [flot](https://github.com/flot/flot) - 吸引人的、基于 jQuery 的 JavaScript 图表库。
* [morris.js](https://github.com/morrisjs/morris.js) - 漂亮的时间序列线框图。
* [nvd3](https://github.com/novus/nvd3) - 一个为 D3.js 构建可复用图表和图表组件的库。
* [svg.js](https://github.com/wout/svg.js) - 一个轻量的、用于操作和添加 SVG 动画的库。
* [heatmap.js](https://github.com/pa7/heatmap.js) - 基于 HTML5 canvas 的热力图 JavaScript 库。
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - 一个直接在浏览器端生成小型走势图的 jQuery 插件。
* [xCharts](https://github.com/tenxer/xCharts) - 一个基于 D3、用于构建自定义图表和图形的库。
* [trianglify](https://github.com/qrohlf/trianglify) - 基于 d3.js 的低多边形（low poly）风格背景图片生成器。
* [d3-cloud](https://github.com/jasondavies/d3-cloud) - 创建词云（word cloud）效果的 JavaScript 库。
* [d4](https://github.com/heavysixer/d4) - 一个基于 D3 、友好、可复用的 DSL 图表库 。
* [dimple.js](http://dimplejs.org/) - 基于 d3 的简易商业分析图表库。
* [chartist-js](https://github.com/gionkunz/chartist-js) - 简单的响应式图表。
* [epoch](https://github.com/fastly/epoch) - 一个通用的实时图表库。
* [c3](https://github.com/masayuki0812/c3) - 基于 D3 的可复用图表库。
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) - 一个运用 HTML5 和 WebGL 构建 3D 游戏的框架。

也有一些很棒的收费库，如 [amchart](http://www.amcharts.com/)、[plotly](https://www.plot.ly/) 和 [highchart](http://www.highcharts.com/)。

<h3 id="timeline">时间轴</h3>

* [TimelineJS](https://github.com/NUKnightLab/TimelineJS) -  一个用 JavaScript 编写的可叙事时间轴库。
* [timesheet.js](https://github.com/semu/timesheet.js) - 用于构建简单的 HTML5 &amp; CSS3 时间表的 JavaScript 库。

<h2 id="editors">编辑器</h2>

* [ace](https://github.com/ajaxorg/ace) - Ace（Ajax.org Cloud9 Editor）。
* [CodeMirror](https://github.com/marijnh/CodeMirror) - 浏览器端的代码编辑器。
* [esprima](https://github.com/ariya/esprima) - 用于综合分析的 ECMAScript 解析器。
* [quill](https://github.com/quilljs/quill) - 一个带有 API 的跨浏览器富文本编辑器。
* [medium-editor](https://github.com/daviferreira/medium-editor) - Medium.com 所见即所得编辑器的克隆版。
* [pen](https://github.com/sofish/pen) - 享受在线编辑（支持 markdown）。
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - 一个易用的、简洁优雅的文本编辑器。灵感来源于 Medium 的魅力。
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - 小巧的、兼容 bootstrap 的所见即所得的富文本编辑器。
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - 适用于每个人的 web 文本编辑器。
* [editor](https://github.com/lepture/editor) - 一个 markdown 编辑器，但仍在开发中。
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - 一个可嵌入的 JavaScript Markdown 的编辑器，拥有全屏编辑、即时预览、自动保存草稿和离线支持等功能。
* [jsoneditor](https://github.com/josdejong/jsoneditor) - 查看、编辑和格式化 JSON 的 web 工具。
* [vim.js](https://github.com/coolwanglu/vim.js) -  拥有持久化 ~/.vimrc 的 Vim 编辑器的 JavaScript 移植版本。
* [Squire](https://github.com/neilj/Squire) - HTML5 富文本编辑器。
* [TinyMCE](https://github.com/tinymce/tinymce) - JavaScript 富文本编辑器。
* [trix](https://github.com/basecamp/trix) - 由 Basecamp 制作，适用于每天写作的富文本编辑器。

<h3 id="files">文件</h3>

处理文件的库。

* [Papa Parse](https://github.com/mholt/PapaParse) - 一款强大的 CSV 库，支持解析 CSV 文件/字符串，也能导出 CSV。
* [jBinary](https://github.com/jDataView/jBinary) - 对用声明式语法描述文件类型和数据结构的二进制文件，进行高级 I/O（加载、解析、操作、序列化、存储）操作。

<h3 id="functional-programming">函数式编程</h3>

函数式编程库扩展了 JavaScript 的能力。

* [underscore](https://github.com/jashkenas/underscore) - JavaScript 的实用工具。
* [lodash](https://github.com/lodash/lodash) - 提供一致性、可定制、高性能和额外功能的实用库。
* [Sugar](https://github.com/andrewplummer/Sugar) - 一个扩展了原生对象功能的 JavaScript 库。
* [lazy.js](https://github.com/dtao/lazy.js) - 类似 Underscore，但性能更优越
* [ramda](https://github.com/CrossEye/ramda) - 一个针对 JavaScript 程序员的实用函数库。
* [mout](https://github.com/mout/mout) - 模块化的 JavaScript 工具库。
* [mesh](https://github.com/mojo-js/mesh.js) - 流数据同步工具。

<h3 id="reactive-programming">响应式编</h3>

响应式程序库扩展了 JavaScript 的能力。

* [RxJs](https://github.com/Reactive-Extensions/RxJS) - 对 JavaScript 进行响应式扩展。
* [Bacon](https://github.com/baconjs/bacon.js) - JavaScript 的 FPR（函数式响应式编程）库。
* [Kefir](https://github.com/pozadi/kefir) - 受 Bacon.js 和 RxJS 启发的 FRP 库，专注于高性能和低内存消耗。
* [Highland](http://highlandjs.org/) - 对 JavaScript 实用工具的重新思考，Highland 能轻易地管理同步和异步信息，而且仅使用标准 JavaScript 和类 Node 流。
* [Most.js](https://github.com/cujojs/most) - 高性能 FRP 库。

<h3 id="数据结构">数据结构</h3>

数据结构库用于构建一个更复杂的应用。

* [immutable-js](https://github.com/facebook/immutable-js) - 不可变的数据集合，包括 Sequence、Range、Repeat、Map、OrderedMap、Set 和 sparse Vector。
* [mori](https://github.com/swannodette/mori) - 使用 ClojureScript 持久化数据结构和支持原生 JavaScript API 的库。
* [buckets](https://github.com/mauriciosantos/buckets) - 完整的、经过充分测试和记录数据结构的 JavaScript 库。
* [hashmap](https://github.com/flesler/hashmap) - 简单的 hashmap 实现，支持任何类型的键值。

<h3 id="date">日期</h3>

日期库。

* [moment](https://github.com/moment/moment) - 解析、验证、操作和显示日期。
* [moment-timezone](https://github.com/moment/moment-timezone) - 基于 moment.js 的时区库。
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - 一款支持自动更新模糊时间戳的 jQuery 插件（如："4 分钟之前"）。
* [timezone-js](https://github.com/mde/timezone-js) - 让 JavaScript Date 对象拥有时区功能。使用 Olson zoneinfo 文件记录着时区数据。
* [date](https://github.com/MatthewMueller/date) - 拥有人性化的 Date() 方法。
* [ms.js](https://github.com/guille/ms.js) - 小巧的毫秒转换工具。

<h3 id="string">字符串</h3>

字符串库。

* [selecting](https://github.com/EvandroLG/selecting) - 一个允许你获取用户选定文本的库。
* [underscore.string](https://github.com/epeli/underscore.string) - 扩展了 Underscore.js 的字符串操作。
* [string.js](https://github.com/jprichardson/string.js) - 额外的 JavaScript 字符串方法。
* [he](https://github.com/mathiasbynens/he) - 健壮的 HTML 实体编码/解码器。
* [multiline](https://github.com/sindresorhus/multiline) - 多行字符串。
* [query-string](https://github.com/sindresorhus/query-string) - 解析和字符串化 URL 查询字符串。
* [URI.js](https://github.com/medialize/URI.js/) - URL 操作库。
* [jsurl](https://github.com/Mikhus/jsurl) - 轻量的 URL 操作库。
* [sprintf.js](https://github.com/alexei/sprintf.js) - 实现字符串格式化。
* [url-pattern](https://github.com/snd/url-pattern) - 让 url 和其它字符串进行比正则表达式匹配更简单。字符串和数据可相互转化。

<h3 id="number">数字</h3>

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - 对数字进行格式化和操作的库。
* [odometer](https://github.com/HubSpot/odometer) - 流畅的数字过渡效果。
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - 对数字、金钱、货币进行格式化的轻量库——完全本地化和无依赖。
* [money.js](https://github.com/josscrowcroft/money.js) - 一个小巧（1kb）的货币转换库，适用于 web 和 nodeJS。
* [Fraction.js](https://github.com/infusion/Fraction.js) - 一个有理数库。
* [Complex.js](https://github.com/infusion/Complex.js) -  一个复数库。
* [Polynomial.js](https://github.com/infusion/Polynomial.js) - 一个多项式库。

<h3 id="storage">存储</h3>

* [store.js](https://github.com/marcuswestin/store.js) - 为所有浏览器封装了 LocalStorage，而没有使用 cookies 和 flash。隐秘地使用 localStorage、globalStorage 和用户数据。
* [localForage](https://github.com/mozilla/localForage) - 改善后的离线存储。其封装了 IndexedDB、WebSQL 和 localStorage，拥有操作简单和强大的 API。
* [jStorage](https://github.com/andris9/jStorage) - jStorage 是一个简单的键值对数据库，用于在浏览器端存储数据。
* [cross-storage](https://github.com/zendesk/cross-storage) - 获得权限后，能跨域名本地存储。
* [basket.js](https://github.com/addyosmani/basket.js) - 用 localStorage 加载和缓存脚本的资源加载器。
* [bag.js](https://github.com/nodeca/bag.js) - 可以缓存脚本和加载资源，与 basket.js 相似，但增加了键值对接口和对 localStorage / websql / undexedDB 的支持。
* [basil.js](https://github.com/Wisembly/basil.js) - 智能的 JavaScript 数据持久层库。
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - 轻量简单的、用于读取、编辑和删除 cookie 的 jQuery 插件。
* [Cookies](https://github.com/ScottHamper/Cookies) - 客户端 Cookie 操作库。
* [DB.js](https://github.com/aaronpowell/db.js/) - 基于 Promise 的、封装了 IndexDB 的库。
* [lawnchair.js](https://github.com/brianleroux/lawnchair/) - 简单的客户端 JSON 存储。

<h3 id="color">颜色</h3>

* [randomColor](https://github.com/davidmerfield/randomColor) - JavaScript 颜色生成器。
* [chroma.js](https://github.com/gka/chroma.js) - 拥有各种各样颜色操作的 JavaScript 库。
* [color](https://github.com/harthur/color) - JavaScript 颜色转换和操作库。
* [colors](https://github.com/mrmrs/colors) - 更智能的默认 web 颜色。
* [PleaseJS](https://github.com/Fooidge/PleaseJS) - 随机创建出赏心悦目的颜色和配色方案。
* [TinyColor](https://github.com/bgrins/TinyColor) - 快速、轻巧的颜色操作和转换库。
* [Vibrant.js](https://github.com/jariz/vibrant.js/) - 从图像提取主要颜色。

<h3 id="i18n-and-l10n">国际化和本地化（I18n And L10n）</h3>

本地化和国际化 JavaScript 库

* [i18next](https://github.com/jamuhl/i18next) - JavaScript 最简单的国际化（i18n）方法。
* [polyglot](https://github.com/airbnb/polyglot.js) - 小巧的国际化助手库。
* [babelfish](https://github.com/nodeca/babelfish/) - i18n 提供友好易懂的 API ，并且内置多种支持。

<h3 id="class">类</h3>

* [ClassManager](https://github.com/kogarashisan/ClassManager) - 世界上最快、最方便的类系统之一。
* [klass](https://github.com/ded/klass) - 用于创建极富表现力的类工具库。
* [augment](https://github.com/javascript/augment) - 世界上最小且最快的一流 JavaScript 继承模式。

<h3 id="control-flow">控制流</h3>

* [async](https://github.com/caolan/async) - 适用于 node 和浏览器的异步工具库。
* [q](https://github.com/kriskowal/q) - 实现异步的 promise JavaScript 库。
* [step](https://github.com/creationix/step/) - 让逻辑顺序合理化的异步控制流库。
* [contra](https://github.com/bevacqua/contra/) - 利用函数风格实现的异步流控制。
* [Bluebird](https://github.com/petkaantonov/bluebird/) - 专注于革新功能和性能的，功能齐全的 promoise 库。
* [when](https://github.com/cujojs/when) - 快速可靠的、Promises/A+ 规范的 when() 实现，而且拥有异步其它的优秀特性。
* [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) - 提供增加了事件监听的原型（与 DOMElement 的 EventTarget 在浏览器行为一致）。

<h3 id="routing">路由</h3>

* [director](https://github.com/flatiron/director) - 一个小巧的、与 URL 同构的路由器。
* [page.js](https://github.com/visionmedia/page.js) - 受 Express router 启发的小型客户端路由器（约为1200字节）。
* [pathjs](https://github.com/mtrpcic/pathjs) - 简单、轻量的 web 路由器。
* [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript 路由。
* [davis.js](https://github.com/olivernn/davis.js) - 使用 pushState、RESTful 风格和可降级的 JavaScript 路由器。

<h3 id="security">安全性</h3>

* [DOMPurify](https://github.com/cure53/DOMPurify) - 针对 HTML、MathML 和 SVG 的仅支持DOM、快速、高容错的 XSS 过滤器。
* [js-xss](https://github.com/leizongmin/js-xss) - 通过白名单配置，即可过滤不信任的 HTML（防止 XSS 攻击）。

<h3 id="log">日志</h3>

* [log](https://github.com/adamschwartz/log) - 带有样式的 Console.log。
* [Conzole](https://github.com/Oaxoa/Conzole) - 对 JavaScript 原生 console 对象方法和功能进行封装的 debug 面板，使其显示在页面内。
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) - 将日志清晰地记录到 console，且兼容所有浏览器。
* [loglevel](https://github.com/pimterry/loglevel) - 最轻量的 JavaScript 日志记录工具库，向封装后可用的 console.log 方法增加可靠的日志等级。
* [minilog](http://mixu.net/minilog/) – 轻量的、用流式 API 显示的、可用于客户端和服务器端的日志记录库。

<h3 id="regexp">正则表达式</h3>

* [RegEx101](https://regex101.com/#javascript) - 在线的 JavaScript 正则表达式测试器和调试器。同时支持 Python、PHP 和 PCRE。
* [RegExr](http://regexr.com/) - 用于创建、测试和学习正则表达式的 HTML/JS  工具。
* [RegExpBuilder](https://github.com/thebinarysearchtree/regexpbuilderjs) - 使用链式方法创建正则表达式。

<h3 id="media">媒体</h3>

* [Ion.Sound](https://github.com/IonDen/ion.sound) - 可用于任何网页上简单音频。

<h3 id="voice-command">语音命令</h3>

* [annyang](https://github.com/TalAter/annyang) - 向网站添加语音命令的语音识别库。
* [voix.js](https://github.com/pazguille/voix) - 向网站、app 或游戏添加语音命令的 JavaScript 库。

<h3 id="api">API</h3>

* [bottleneck](https://github.com/SGrondin/bottleneck) - 强大的频率限制器，使调节流量变得更容易。
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - 适用于 node 和 浏览器的 OAuth 1.0a 签名生成器。
* [amygdala](https://github.com/lincolnloop/amygdala) - 为 Web 应用提供 RESTful HTTP 客户端解决方案。
* [jquery.rest](https://github.com/jpillora/jquery.rest) - 一个让 RESTful API 更易使用的 jQuery 插件。

<h3 id="vision-detection">视觉检测</h3>

* [tracking.js](https://github.com/eduardolundgren/tracking.js) - 在 web 上实现计算视觉的一种现代方法。
* [ocrad.js](https://github.com/antimatter15/ocrad.js) - 通过 Emscripten 用 JavaScript 实现 OCR（光学字符识别）。

<h3 id="browser-detection">浏览器检测</h3>

* [bowser](https://github.com/ded/bowser) - 一个浏览器检测器。

## UI

<h3 id="code-highlighting">代码高亮</h3>

* [Highlight.js](https://github.com/isagalaev/highlight.js) - JavaScript 语法高亮器。
* [PrismJS](https://github.com/LeaVerou/prism) - 轻量、健壮和优雅的语法高亮器。

<h3 id="loading-status">加载状态</h3>

指示加载状态的库。

* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - 创建谷歌 Material 设计风格的线性进度条。
* [NProgress](http://ricostacruz.com/nprogress/) - 在 Ajax'y 应用显示细长型进度条
* [Spin.js](https://github.com/fgnass/spin.js) - 一个旋转的进度指示器。
* [progress.js](https://github.com/usablica/progress.js) - 为页面任何对象创建和管理进度条。
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - 用 SVG path 动画制作的、漂亮和响应式的进度条。
* [pace](https://github.com/HubSpot/pace) - 自动向你的网站添加一个进度条。
* [topbar](https://github.com/buunguyen/topbar) - 小巧漂亮的、与网站同宽的进度指示器。
* [nanobar](https://github.com/jacoborus/nanobar) - 非常轻量的进度条。不依赖 jQuery。
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - 使用 SVG 动画展现新内容的现代方式。
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - 运用 CSS 动画的加载指示器集合。
* [Ladda](https://github.com/hakimel/Ladda) - 内置在按钮的加载指示器。
* [css-loaders](https://github.com/lukehaas/css-loaders) - 运用 CSS 动画的旋转加载指示器的集合。

除了上述这些库，还有收藏在 [Codepen](http://codepen.io/collection/HtAne/) 的，另外还有 [Ajaxload](http://www.ajaxload.info/)，[Preloaders](http://preloaders.net/) 和 [CSSLoad](http://cssload.net/) 这些生成器。

<h3 id="validation">验证</h3>

* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - 不用写一行 JavaScript 代码即可在前端验证表单。
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery 验证插件。
* [validator.js](https://github.com/chriso/validator.js) - 字符串验证和过滤（在使用用户输入之前清理用户输入中的有害或危险字符的操作）。
* [validate.js](https://github.com/rickharrison/validate.js) - 受 CodeIgniter 启发的轻量表单验证 JavaScript 库。
* [validatr](https://github.com/jaymorrow/validatr/) - 跨浏览器的 HTML5 表单验证库。
* [BootstrapValidator](https://github.com/nghuuphuoc/bootstrapvalidator) - 是验证表单域中最好的 jQuery 插件。要与 Bootstrap 3 一起使用。
* [is.js](https://github.com/arasatasaygin/is.js) - 检查类型、正则表达式、是否存在、时间等。
* [FieldVal](https://github.com/FieldVal/fieldval-js) - 多用途验证库。同时支持同步和异步验证。

<h3 id="keyboard-wrappers">键盘封装器</h3>

* [mousetrap](https://github.com/ccampbell/mousetrap) - 处理键盘快捷键的 JavaScript 库。
* [keymaster](https://github.com/madrobby/keymaster) - 定义和调度键盘快捷键的小型库。
* [Keypress](https://github.com/dmauro/Keypress) - 键入捕捉工具库，任何键都可以成为一个修饰健。
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - 一个用于绑定键盘组合的 JavaScript 库，让你脱离快捷键和快捷键组合冲突的痛苦。
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys 能让你在代码任何的地方监听键盘事件，并几乎支持所有按键组合。
* [jwerty](https://github.com/keithamus/jwerty) - 令人惊叹的键盘事件处理库。

<h3 id="tours-and-guides">浏览和引导</h3>

* [intro.js](https://github.com/usablica/intro.js) - 这是一个介绍新功能的很好方式，能一步步地引导用户浏览你的网站和项目。
* [shepherd](https://github.com/HubSpot/shepherd) - 通过引导让用户浏览你的应用程序。
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - 应用 Twitter Bootstrap 弹出框对产品进行快速简单的引导。
* [tourist](https://github.com/easelinc/tourist) - 简单、灵活的应用引导介绍库。
* [chardin.js](https://github.com/heelhook/chardin.js) - 简单的应用遮罩层介绍。
* [pageguide](https://github.com/tracelytics/pageguide) - 使用 jQuery 和 CSS3 的 web 页面元素交互引导库。
* [hopscotch](https://github.com/linkedin/hopscotch) - 让开发者更容易向其页面产品添加引导的框架。
* [joyride](https://github.com/zurb/joyride) - 基于 jQuery 的功能引导插件。
* [focusable](https://github.com/zzarcon/focusable) - 通过向页面其余部分添加遮罩层，使焦点聚集在特定 DOM 元素。

<h3 id="notifications">通知</h3>

* [messenger](https://github.com/HubSpot/messenger) - 为你的应用添加 Growl-style 弹框和信息（Crowl 是 Mac OS X 下的一个通知系统）。
* [noty](https://github.com/needim/noty) - jQuery 通知插件。
* [pnotify](https://github.com/sciactive/pnotify) - 适用于 Bootstrap、jQuery UI 和 Web Notifications Draft 的 JavaScript 通知库。
* [toastr](https://github.com/CodeSeven/toastr) - 简单的弹出框通知（[toast notifications](http://ux.stackexchange.com/questions/11998/what-is-a-toast-notification)：用来显示简单的，会自动到期的信息窗口）。
* [humane-js](https://github.com/wavded/humane-js) - 一个简单、时髦的浏览器通知系统。
* [smoke.js](https://github.com/hxgf/smoke.js) - 与框架无关的、能够自定义样式的 JavaScript 弹框系统。

<h3 id="sliders">幻灯片</h3>

* [Swiper](https://github.com/nolimits4web/Swiper) - 使用硬件加速过渡的移动设备触控滑块框架。
* [slick](https://github.com/kenwheeler/slick) - 你所需要的最后一个轮播插件。
* [slidesJs](http://www.slidesjs.com/) - 响应式的 jQuery（1.7.1+）幻灯片插件，具有触摸、 CSS3 过渡等特性。
* [FlexSlider](https://github.com/woothemes/FlexSlider) - 一款令人惊叹的、全响应式的幻灯片 jQuery 插件。
* [unslider](https://github.com/idiot/unslider) - 最简单的幻灯片 jQuery 插件。
* [colorbox](https://github.com/jackmoore/colorbox) - 轻量、可自定义的灯箱 jQuery 插件。
* [fancyBox](https://github.com/fancyapps/fancyBox) - 提供了良好优雅的方式，为页面上的图片、html 内容和多媒体添加缩放功能的工具。
* [sly](https://github.com/darsain/sly) - 基于项导航的、支持单向滚动的 JavaScript 库。
* [vegas](https://github.com/jaysalvat/vegas) - 向页面添加漂亮的全屏背景的 jQuery 插件，甚至允许幻灯片。
* [Sequence](https://github.com/IanLunn/Sequence) - 用于创建响应式的幻灯片、演示、旗帜广告和以步骤为基础的应用的 CSS 动画框架。
* [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) - 易于使用的、用纯 JavaScript 实现的遮罩层脚本。
* [reveal.js](https://github.com/hakimel/reveal.js) - 用 HTML 创建漂亮演示控件的框架。
* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - 适用于移动设备和桌面电脑的、模块化和不无依赖框架的 JavaScript 画廊控件。
* [jcSlider](https://github.com/JoanClaret/jcSlider) - 用 CSS 动画实现的响应式幻灯片 jQuery 插件。
* [basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) - 易于使用、指定主题和定制化。
* [unslider](https://github.com/idiot/unslider) -  这是最简单的幻灯片 jQuery 插件。
* [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) - 带有自适应颜色标题和导航的幻灯片 jQuery 插件。
* [slidr](https://github.com/bchanx/slidr) - 可添加一些幻灯片效果。
* [Flickity](https://github.com/metafizzy/flickity) - 可触摸的、响应式的和可轻弹的画廊。

<h3 id="range-sliders">滑块控件</h3>

* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - 强大的、易于自定义的范围滑块选择库，支持很多配置和皮肤。
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - 支持日期的滑块选择库。
* [noUiSlider](https://github.com/leongersen/noUiSlider) - 轻量无冗余的、高度定制化的滑块选择库。
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5  input 区域滑块元素。

<h3 id="form-widgets">表单组件</h3>

### 输入

* [typeahead.js](https://github.com/twitter/typeahead.js) - 快速的、功能齐全的自动补全库。
* [tag-it](https://github.com/aehlke/tag-it) - 处理多标签字段以及标签建议/自动完成的 jQuery UI 插件。
* [At.js](https://github.com/ichord/At.js) - 向你的应用添加类似 Github 的自动完成提示功能。
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - JavaScript 补全 HTML5 占位符的属性。
* [fancyInput](https://github.com/yairEO/fancyInput) - 利用 CSS3 效果让输入更有趣。
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - 利用这个 jQuery 插件，可奇妙地将一个简单的文本输入转换成一个酷酷的标签列表。
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - 一个纯 JavaScript 实现的输入控制库。
* [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) - 一个为复选框和单选按钮添加样式的 jQuery 库，支持多种皮肤。

### 日历

* [pickadate.js](https://github.com/amsul/pickadate.js) - 对移动设备友好的、响应式的和轻量的 jQuery 日期 &amp; 时间输入选择器。
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - 基于 bootstrap 的日历选择器。
* [Pikaday](https://github.com/dbushell/Pikaday) - 一个崭新的 JavaScript 日期选择器 —— 轻量、无依赖和模块化的 CSS。
* [fullcalendar](https://github.com/arshaw/fullcalendar) - 全尺寸、支持拖放事件的日历（jQuery 插件）。
* [rome](https://github.com/bevacqua/rome) - 可定制的日期（和时间）选择器。无依赖，可选 UI。
* [datedropper](https://github.com/felicegattuso/datedropper) -  datedropper 是一个 jQuery 插件，它提供了快速简易的方式去管理日期输入框。

### 选择

* [selectize.js](https://github.com/brianreavis/selectize.js) - Selectize 是文本框和选择框的混合体。它基于jQuery，拥有自动完成和键盘感应下拉列表功能，可用于标签、联系人列表等。
* [select2](https://github.com/ivaynberg/select2) - 它基于 jQuery，是选择框（select box）的替代品。支持搜索、远程数据集和无限滚动。
* [chosen](https://github.com/harvesthq/chosen) - 可以让冗长不便的选择框更友好的库。

### 文件上传

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload 是一个支持多文件选择、文件拖放、进度条、验证和图片、音频、视频预览的 jQuery 插件。
* [dropzone](https://github.com/enyo/dropzone) - Dropzone 是一个易于使用且支持多文件拖放的库。其支持图片预览并且拥有很好的进度条效果。
* [flow.js](https://github.com/flowjs/flow.js) - 一个通过 HTML5 的 File API ，提供多个同时链接的、稳定的、容错的、可恢复的/可重新开始的文件上传库。
* [fine-uploader](https://github.com/Widen/fine-uploader) - 一个带有进度条、拖放功能和支持直接上传到 S3 （Amazon Simple Storage Service，亚马逊简易存储服务）的多文件上传插件。
* [FileAPI](https://github.com/mailru/FileAPI) - JavaScript 文件工具集合。支持多文件上传、拖放和文件分块上传。对于图像，支持裁剪、调整大小和根据 [EXIF](http://baike.baidu.com/view/22006.htm) 自动调整方向。
* [plupload](https://github.com/moxiecode/plupload) - 处理文件上传的 JavaScript API，其支持多文件选择、文件类型过滤、分块请求、客户端图片缩放和根据不同的运行环境选择 HTML5、Silverlight 和 Flash。

### 其它

* [form](https://github.com/malsup/form) - jQuery 表单插件。
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - 自动在本地保存表单文本和选择框的值，直到表单被提交。
* [Countable](https://github.com/RadLikeWhoa/Countable) - 对某个 HTML 元素包含文本的段落数、单词数和字符数进行统计的 JavaScript 函数。
* [card](https://github.com/jessepollak/card) - 只需一行代码，让信用卡表单变得更友好。
* [stretchy](https://github.com/LeaVerou/stretchy) - 自适应大小的 form 元素，表单本应该是这样的。
* [list.js](https://github.com/javve/list.js) - 向表格、列表等 HTML 元素添加搜索、排序、过滤和自适应功能的库。在已有 HTML 上增加可视化。[
 ](http://www.listjs.com/)

<h3 id="tips">提示</h3>

* [tipsy](https://github.com/jaz303/tipsy) - 基于 jQuery 的 Fackbook 风格的提示工具（tooltip）。
* [opentip](https://github.com/enyo/opentip) - 开源且基于 prototype 框架的 JavaScript 工具提示库。
* [qTip2](https://github.com/qTip2/qTip2) - 非常强大的工具提示库。
* [tooltipster](https://github.com/iamceege/tooltipster) - 一个工具提示 jQuery 插件。
* [simptip](https://github.com/arashmanteghi/simptip) - 用 Sass 制作的、简单的工具提示。
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - 是一个响应式的和可访问性强的模态框（modal）和工具提示框 jQuery 插件。

<h3 id="modals-and-popups">模态框和弹出框</h3>

* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - 专注于性能、轻量、响应式的灯箱（lightbox）脚本。
* [jquery-popbox](https://github.com/gristmill/jquery-popbox) - jQuery 提示框插件。
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - 一种新的定于弹出的模态框 jQuery 插件。
* [vex](https://github.com/HubSpot/vex) - 新的、拥有高度可配置和易于改变样式功能的对话框库。
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - 对 Bootstrap 默认的模态框类进行扩展。其支持响应式、可堆叠和 ajax 等。
* [css-modal](https://github.com/drublic/css-modal) - 纯 CSS 打造的模态框。
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - 是一个响应式的和可访问性强的模态框和工具提示框（tooltips）jQuery 插件。

<h3 id="scroll">滚动</h3>

* [scrollMonitor](https://github.com/sakabako/scrollMonitor) - 滚动发生时，可以监听元素的、简单、快速的 API。
* [headroom](https://github.com/WickyNilliams/headroom.js) - 除非你需要显示页面头部（header），否则将隐藏它，以腾出页面头部空间。
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - 创建一个类似 Apple 的单页面滚动网站（iPhone 5S  网站）。
* [iscroll](https://github.com/cubiq/iscroll) - 高性能、轻量、无依赖、兼容多平台的 JavaScript 滚动组件。
* [skrollr](https://github.com/Prinzhorn/skrollr) - 独立（不依赖 jQuery） 的视差滚动库，适用于移动设备（Android + iOS）和桌面电脑。
* [parallax](https://github.com/wagerfield/parallax) - 面向智能设备的视差引擎。
* [stellar.js](https://github.com/markdalgleish/stellar.js) - 让视差滚动变简单。
* [plax](https://github.com/cameronmcefee/plax) - 基于 jQuery 的视差库。
* [jparallax](https://github.com/stephband/jparallax) - 创建可交互视差效果的 jQuery 插件。
* [fullPage](https://github.com/alvarotrigo/fullPage.js) - 简单和易于使用的、用于创建全屏滚动网站的插件（也被称为单页面网站）。
* [ScrollMenu](https://github.com/s-yadav/ScrollMenu) - 让老旧无聊的滚动条焕然一新。

<h3 id="menu">菜单</h3>

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - 当用户光标放在特定下拉菜单项时触发事件。可制作响应式的、大数据量的下拉菜单，如 Amazon 的。
* [jQuery contextMenu](https://github.com/medialize/jQuery-contextMenu) - 右键菜单（contextMenu） 管理工具。
* [Slideout](https://github.com/mango/slideout) - 为移动设备的 web 应用制作出响应式的、可触摸滑出的导航菜单。
* [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) - 一个基于 touchSwipe 库的滑出菜单插件。

<h3 id="table-grid">表格/栅格</h3>

* [jTable](https://github.com/hikalkan/jtable) - 基于 CRUD 表创建 AJAX 的 jQuery 插件。
* [DataTables](http://www.datatables.net/) - 这是一个非常灵活的工具，在渐进增强的基础上，将高级的交互效果加到 HTML 表格。（jQuery 插件）
* [floatThead](https://github.com/mkoryak/floatThead) - （jQuery 插件）锁定表格头部，只允许表格内容滚动。适用于任何表格，而且不需要额外的 html 或 css。
* [Masonry](http://masonry.desandro.com/) - 瀑布流式的网格布局库。
* [Packery](http://packery.metafizzy.co/) - 使用装箱算法（bin-packing）的网格布局库。支持拖拽布局。
* [Isotope](http://isotope.metafizzy.co/) - 可过滤和可排序的网格布局的库，它能实现 Masonry、Packery 等布局。

<h3 id="frameworks-1">框架</h3>

* [Semantic UI](http://semantic-ui.com/) - 拥有大量主题和元素的 UI 套件。

<h3 id="gesture">手势</h3>

* [hammer.js](https://github.com/hammerjs/hammer.js) - 拥有多种触摸手势的 JavaScript 库。
* [touchemulator](https://github.com/hammerjs/touchemulator) - 在桌面电脑模仿触摸输入。
* [Dragula](https://github.com/bevacqua/dragula/) - 超级易于使用的拖拽库。

<h3 id="maps">地图</h3>

* [Leaflet](https://github.com/Leaflet/Leaflet) - 对移动设备友好的、可交互的地图 JavaScript 库。
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - 开源的、基于 WebGL 实现的虚拟地球仪和地图引擎。
* [gmaps](https://github.com/HPNeo/gmaps) - 以最简单的方式使用 Google 地图。
* [polymaps](https://github.com/simplegeo/polymaps) - 一个免费的、兼容现代 web 浏览器的、用于制作动态可交互的地图 JavaScript 库。
* [kartograph.js](https://github.com/kartograph/kartograph.js) - 开源的 Kartograph SVG 地图渲染器。
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox 的 API，Leaflet 的插件。
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - 矢量地图 jQuery 插件。
* [OpenLayers3](http://openlayers.org/) - 高性能的、功能丰富的库，能满足你对地图所有需求。

<h3 id="video-audio">视频/音频</h3>

* [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) - 更完美地嵌入 YouTube —— 拥有很好的选项，如高分辨率的预览图、嵌入选项的高级定制和可选的 FitVids 支持。
* [html5media](https://github.com/etianen/html5media) - 能在所有主流浏览器播放多媒体标签中定义的多媒体文件。[http://html5media.info/](http://html5media.info/)
* [Play-em JS](https://github.com/adrienjoly/playemjs) - Play'em 是一个 JavaScript 组件，它能管理音乐/视频播放顺序，通过在一个 DIV 元素里嵌入几个播放器（Youtube、Soundcloud 和 Vimeo）来控制一系列歌曲的播放。
* [polyplayer](https://github.com/Acconut/polyplayer) - 将 YouTube、Soundcloud 和 Vimeo 播放器的 API 统一成一套。
* [flowplayer](https://github.com/flowplayer/flowplayer) -  HTML5 视频播放器 [http://flowplayer.org/](http://flowplayer.org/)
* [mediaelement](https://github.com/johndyer/mediaelement) - 让 HTML5、 Flash 播放器和模仿 HTML5 媒介元素 API 的 Silverlight shim，在所有浏览器拥有一致的 UI。[http://mediaelementjs.com/](http://mediaelementjs.com/)
* [SoundJS](https://github.com/CreateJS/SoundJS) - 让音频在 web 上运行更简单的库。它为不同浏览器提供了一致的 API。

<h3 id="animations">动画</h3>

* [velocity](https://github.com/julianshapiro/velocity) - 加速 JavaScript 动画。
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - 拥有超级流畅的 CSS3 变换和过渡的 jQuery 插件。
* [impess.js](https://github.com/impress/impress.js) - 在 HTML 文档里，运用 CSS3 变换和过渡制作类似 Prezi 的展现效果。
* [bounce.js](https://github.com/tictail/bounce.js) - 可以立刻创建有趣的 CSS3 动画。
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - 适用于所有主流浏览器的高性能 HTML5 动画。
* [TransitionEnd](https://github.com/EvandroLG/transitionEnd) - TransitionEnd 是一个运用 transitonend 事件的、跨浏览器的库。
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - 用于创建基于物理知识的 CSS 动画库。

<h3 id="image-processing">图片处理</h3>

* [lena.js](https://github.com/davidsonfellipe/lena.js) - 拥有滤镜和实用功能的图像处理库。
* [pica](https://github.com/nodeca/pica) - 高质量地调整图片大小（拥有快速的、纯 JS 实现的 Lanczos 滤镜算法）。
* [cropper](https://github.com/fengyuanchen/cropper) - 一个简单的图像裁剪 jQuery 插件。

<h3 id="es6">ECMAScript 6</h3>

* [es6features](https://github.com/lukehoban/es6features) - ECMAScript 6 特性概述。
* [es6-features](https://github.com/rse/es6-features) - ECMAScript 6:  特性概述和比较。
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables 展示了各种平台上所有 ECMAScript 6 特性的支持程度。
* [Babel (Formerly 6to5)](https://github.com/babel/babel) - 将 ES6+ 代码转换成纯 ES5。
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 特性转 ES5。包括 classes、generators、promises、destructuring patterns、default parameters 等。

<h3 id="sdk">软件开发工具包(SDK)</h3>

* [javascript-sdk-design](http://github.com/huei90/javascript-sdk-design) - 从工作和个人经验中提炼出来的 JavaScript SDK 设计指导。

<h3 id="misc">大杂烩</h3>

* [echo](https://github.com/toddmotto/echo) - 利用 data-* 属性延迟加载图片。
* [picturefill](https://github.com/scottjehl/picturefill) - 响应式图片显示插件，使浏览器支持 srcset、size 属性。
* [platform.js](https://github.com/bestiejs/platform.js) - 一个平台检测库，几乎适用于所有 JavaScript 平台。
* [json3](https://github.com/bestiejs/json3) - 一个现代 JSON 实现库，几乎兼容所有 JavaScript 平台。
* [Logical Or Not](http://gabinaureche.com/logicalornot/) - 一个关于 JavaScript 特性的游戏。
* [BitSet.js](https://github.com/infusion/BitSet.js) - 实现位向量的 JavaScript 库。

<h2 id="worth-reading">精品阅读</h2>

* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/)
* [JSbooks](https://github.com/revolunet/JSbooks)
* [Superhero.js](http://superherojs.com/) - 关于创建、测试和维护一个大型 JavaScript 代码库的资源集。

<h1 id="resources">资源</h1>

<h3 id="influential-books">有影响力的书</h3>
*具有广泛影响且值得阅读的前端经典书籍。*

*《[Limu：JavaScript 的那些书](http://web.jobbole.com/8087/)》

<h3 id="websites">知名网站</h3>
*值得关注的前端技术站点。*

<h4>中文站点</h4>

* [伯乐在线前端频道](http://web.jobbole.com/):伯乐前端分享 Web 前端开发，包括 JavaScript、CSS 和 HTML5 开发技术，前端相关的行业动态。

<h4>英文站点</h4>

待补充

<h3 id="weibo-weixin">微博、微信公众号</h3>
* 前端大全 微博：[@前端大全](http://weibo.com/u/5261893910)
* 前端大全：专注分享Web前端相关的内容，包括 JavaScript, CSS 和 HTML5 技术文章、工具资源、精选课程和Web技术领域热点资讯。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c688tqj2046046mx8.jpg" width=150 height=150>
* UI设计达人：分享 UI 设计精选文章、案例、行业趋势、课程和书籍。<br><img src="http://ww4.sinaimg.cn/mw690/bfdcef89gw1evuvyehtx4j2076076q3e.jpg" width=150 height=150>
* 网页设计精选：分享网页设计精选文章、案例、行业趋势、课程和书籍。<br><img src="http://ww2.sinaimg.cn/mw690/bfdcef89gw1evuvyhsikmj2076076dgb.jpg" width=150 height=150>
