# jsMind

[![npm version](https://badge.fury.io/js/jsmind.svg)](https://www.npmjs.com/package/jsmind)
![build-test](https://github.com/hizzgdev/jsmind/actions/workflows/node.js.yml/badge.svg)

jsMind 是一个显示/编辑思维导图的纯 javascript 类库，其基于 html5 canvas (和 svg) 进行设计。jsMind 以 BSD 协议开源，在此基础上你可以在你的项目上任意使用。你可以在此浏览[适用于 jsMind 的许可协议][3]。

jsMind is mind map library built by javascript, it base on html5 canvas and svg. jsMind is released under the BSD license, you can embed it in any project as long as you abide by the license. You can read [the license agreement for jsMind][3] here.

## Get Started

```html
<html>
    <head>
        <link type="text/css" rel="stylesheet" href="style/jsmind.css" />
        <script type="text/javascript" src="js/jsmind.js"></script>
        <!--
            enable draggable node feature
            <script type="text/javascript" src="js/jsmind.draggable-node.js"></script>
        -->
    </head>
    <body>
        <div id="jsmind_container"></div>

        <script type="text/javascript">
            var mind = {
                // 3 data formats were supported ...
                // see documents for more information
            };
            var options = {
                container: 'jsmind_container',
                theme: 'orange',
                editable: true,
            };
            var jm = new jsMind(options);
            jm.show(mind);
        </script>
    </body>
</html>
```

## Links

-   Project Home :
    -   on Github: <https://github.com/hizzgdev/jsmind>
    -   on npm : <https://www.npmjs.com/package/jsmind>
-   Apps :
    -   <https://jsmind.online>
    -   <https://jsmind.sinaapp.com>
-   Demo :
    -   <http://hizzgdev.github.io/jsmind/example/1_basic.html>
    -   <http://hizzgdev.github.io/jsmind/example/2_features.html>
    -   ~~<http://hizzgdev.github.io/jsmind/example/3_mathjax.html>~~
-   Document :
    -   [简体中文][1]
    -   [English][2]
-   Wiki :
    -   [邮件列表 Mailing List](../../wiki/MailingList)
    -   [热点问题 Hot Topics](../../wiki/HotTopics)
-   Donate :
    -   [Become a sponsor][4]
    -   [资助本项目的开发][5]

## ES6 Pilot Version

-   目前处于测试阶段，欢迎试用找 bug, ES6 代码位于 `/src`, 可运行于浏览器的 js 文件位于 `/es6`
-   Currently it's in the testing stage, welcome to trial and dig bugs, the ES6 code is located in `/src`, and the js files that can run in browsers are located in `/es6`
-   Demo: <http://hizzgdev.github.io/jsmind/example/2_features_es6.html>

## Maintainer

-   [张志刚 | Zhigang Zhang](https://hizzgdev.github.io)
-   hizzgdev@163.com

[1]: docs/zh/index.md
[2]: docs/en/index.md
[3]: LICENSE
[4]: https://github.com/sponsors/hizzgdev
[5]: http://hizzgdev.github.io/sponsor.html
