# cms2
cms2 app

# live web demo
- [https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app)

[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app)



[![travis-ci.org build-status](https://api.travis-ci.org/kaizhu256/node-cms2.svg)](https://travis-ci.org/kaizhu256/node-cms2) [![coverage](https://kaizhu256.github.io/node-cms2/build/coverage.badge.svg)](https://kaizhu256.github.io/node-cms2/build/coverage.html/index.html) [![snyk.io vulnerabilities](https://snyk.io/test/github/kaizhu256/node-cms2/badge.svg)](https://snyk.io/test/github/kaizhu256/node-cms2)

[![NPM](https://nodei.co/npm/cms2.png?downloads=true)](https://www.npmjs.com/package/cms2)

[![build commit status](https://kaizhu256.github.io/node-cms2/build/build.badge.svg)](https://travis-ci.org/kaizhu256/node-cms2)

| git-branch : | [master](https://github.com/kaizhu256/node-cms2/tree/master) | [beta](https://github.com/kaizhu256/node-cms2/tree/beta) | [alpha](https://github.com/kaizhu256/node-cms2/tree/alpha)|
|--:|:--|:--|:--|
| test-server-github : | [![github.com test-server](https://kaizhu256.github.io/node-cms2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-cms2/build..master..travis-ci.org/app) | [![github.com test-server](https://kaizhu256.github.io/node-cms2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app) | [![github.com test-server](https://kaizhu256.github.io/node-cms2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-cms2/build..alpha..travis-ci.org/app)|
| test-report : | [![test-report](https://kaizhu256.github.io/node-cms2/build..master..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-cms2/build..master..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-cms2/build..alpha..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-cms2/build..alpha..travis-ci.org/test-report.html)|
| coverage : | [![coverage](https://kaizhu256.github.io/node-cms2/build..master..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-cms2/build..master..travis-ci.org/coverage.html/index.html) | [![coverage](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/coverage.html/index.html) | [![coverage](https://kaizhu256.github.io/node-cms2/build..alpha..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-cms2/build..alpha..travis-ci.org/coverage.html/index.html)|
| build-artifacts : | [![build-artifacts](https://kaizhu256.github.io/node-cms2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-cms2/tree/gh-pages/build..master..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-cms2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-cms2/tree/gh-pages/build..beta..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-cms2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-cms2/tree/gh-pages/build..alpha..travis-ci.org)|

[![npmPackageListing](https://kaizhu256.github.io/node-cms2/build/screenshot.npmPackageListing.svg)](https://github.com/kaizhu256/node-cms2)

![npmPackageDependencyTree](https://kaizhu256.github.io/node-cms2/build/screenshot.npmPackageDependencyTree.svg)



# table of contents
1. [cdn download](#cdn-download)
1. [documentation](#documentation)
1. [quickstart standalone app](#quickstart-standalone-app)
1. [quickstart example.js](#quickstart-examplejs)
1. [extra screenshots](#extra-screenshots)
1. [package.json](#packagejson)
1. [changelog of last 50 commits](#changelog-of-last-50-commits)
1. [internal build script](#internal-build-script)
1. [misc](#misc)



# cdn download
- [https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app/assets.cms2.js](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app/assets.cms2.js)



# documentation
#### cli help
![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.npmPackageCliHelp.svg)

#### api doc
- [https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/apidoc.html](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/apidoc.html)

[![apidoc](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/apidoc.html)

#### todo
- none

#### changelog for v2018.1.16
- npm publish 0.0.2
- initial app
- none

#### this package requires
- darwin or linux os



# quickstart standalone app
#### to run this example, follow the instruction in the script below
- [assets.app.js](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app/assets.app.js)
```shell
# example.sh

# this shell script will download and run a web-demo of cms2 as a standalone app

# 1. download standalone app
curl -O https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/app/assets.app.js
# 2. run standalone app
PORT=8081 node ./assets.app.js
# 3. open a browser to http://127.0.0.1:8081 and play with the web-demo
# 4. edit file assets.app.js to suit your needs
```

#### output from browser
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleSh.browser.%252F.png)](https://kaizhu256.github.io/node-cms2/build/app/assets.example.html)

#### output from shell
![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleSh.svg)



# quickstart example.js
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.browser.%252F.png)](https://kaizhu256.github.io/node-cms2/build/app/assets.example.html)

#### to run this example, follow the instruction in the script below
- [example.js](https://kaizhu256.github.io/node-cms2/build..beta..travis-ci.org/example.js)
```javascript
/*
example.js

this script will run a web-demo of cms2

instruction
    1. save this script as example.js
    2. run the shell command:
        $ npm install cms2 && PORT=8081 node example.js
    3. open a browser to http://127.0.0.1:8081 and play with the web-demo
    4. edit this script to suit your needs
*/



/* istanbul instrument in package cms2 */
/*jslint
    bitwise: true,
    browser: true,
    maxerr: 8,
    maxlen: 100,
    node: true,
    nomen: true,
    regexp: true,
    stupid: true
*/
(function () {
    'use strict';
    var local;



    // run shared js-env code - init-before
    (function () {
        // init local
        local = {};
        // init modeJs
        local.modeJs = (function () {
            try {
                return typeof navigator.userAgent === 'string' &&
                    typeof document.querySelector('body') === 'object' &&
                    typeof XMLHttpRequest.prototype.open === 'function' &&
                    'browser';
            } catch (errorCaughtBrowser) {
                return module.exports &&
                    typeof process.versions.node === 'string' &&
                    typeof require('http').createServer === 'function' &&
                    'node';
            }
        }());
        // init global
        local.global = local.modeJs === 'browser'
            ? window
            : global;
        // init utility2_rollup
        local = local.global.utility2_rollup || (local.modeJs === 'browser'
            ? local.global.utility2_cms2
            : require('cms2'));
        // init exports
        local.global.local = local;
    }());
    switch (local.modeJs) {



    // run browser js-env code - init-test
    /* istanbul ignore next */
    case 'browser':
        local.testRunBrowser = function (event) {
            if (!event || (event &&
                    event.currentTarget &&
                    event.currentTarget.className &&
                    event.currentTarget.className.includes &&
                    event.currentTarget.className.includes('onreset'))) {
                // reset output
                Array.from(
                    document.querySelectorAll('body > .resettable')
                ).forEach(function (element) {
                    switch (element.tagName) {
                    case 'INPUT':
                    case 'TEXTAREA':
                        element.value = '';
                        break;
                    default:
                        element.textContent = '';
                    }
                });
            }
            switch (event && event.currentTarget && event.currentTarget.id) {
            case 'testRunButton1':
                // show tests
                if (document.querySelector('#testReportDiv1').style.maxHeight === '0px') {
                    local.uiAnimateSlideDown(document.querySelector('#testReportDiv1'));
                    document.querySelector('#testRunButton1').textContent = 'hide internal test';
                    local.modeTest = true;
                    local.testRunDefault(local);
                // hide tests
                } else {
                    local.uiAnimateSlideUp(document.querySelector('#testReportDiv1'));
                    document.querySelector('#testRunButton1').textContent = 'run internal test';
                }
                break;
            // custom-case
            default:
                break;
            }
            if (document.querySelector('#inputTextareaEval1') && (!event || (event &&
                    event.currentTarget &&
                    event.currentTarget.className &&
                    event.currentTarget.className.includes &&
                    event.currentTarget.className.includes('oneval')))) {
                // try to eval input-code
                try {
                    /*jslint evil: true*/
                    eval(document.querySelector('#inputTextareaEval1').value);
                } catch (errorCaught) {
                    console.error(errorCaught);
                }
            }
        };
        // log stderr and stdout to #outputTextareaStdout1
        ['error', 'log'].forEach(function (key) {
            console[key + '_original'] = console[key];
            console[key] = function () {
                var element;
                console[key + '_original'].apply(console, arguments);
                element = document.querySelector('#outputTextareaStdout1');
                if (!element) {
                    return;
                }
                // append text to #outputTextareaStdout1
                element.value += Array.from(arguments).map(function (arg) {
                    return typeof arg === 'string'
                        ? arg
                        : JSON.stringify(arg, null, 4);
                }).join(' ') + '\n';
                // scroll textarea to bottom
                element.scrollTop = element.scrollHeight;
            };
        });
        // init event-handling
        ['change', 'click', 'keyup'].forEach(function (event) {
            Array.from(document.querySelectorAll('.on' + event)).forEach(function (element) {
                element.addEventListener(event, local.testRunBrowser);
            });
        });
        // run tests
        local.testRunBrowser();
        break;



    // run node js-env code - init-test
    /* istanbul ignore next */
    case 'node':
        // init exports
        module.exports = local;
        // require builtins
        Object.keys(process.binding('natives')).forEach(function (key) {
            if (!local[key] && !(/\/|^_|^sys$/).test(key)) {
                local[key] = require(key);
            }
        });
        // init assets
        local.assetsDict = local.assetsDict || {};
        /* jslint-ignore-begin */
        local.assetsDict['/assets.index.template.html'] = '\
<!doctype html>\n\
<html lang="en">\n\
<head>\n\
<meta charset="UTF-8">\n\
<meta name="viewport" content="width=device-width, initial-scale=1">\n\
<!-- "assets.index.default.template.html" -->\n\
<title>{{env.npm_package_name}} (v{{env.npm_package_version}})</title>\n\
<style>\n\
/*csslint\n\
    box-sizing: false,\n\
    universal-selector: false\n\
*/\n\
*,\n\
*:after,\n\
*:before {\n\
    box-sizing: border-box;\n\
}\n\
body {\n\
    background: #dde;\n\
    font-family: Arial, Helvetica, sans-serif;\n\
    margin: 0 40px;\n\
}\n\
body > a,\n\
body > button,\n\
body > div,\n\
body > input,\n\
body > pre,\n\
body > select,\n\
body > span,\n\
body > textarea {\n\
    margin-bottom: 20px;\n\
}\n\
body > button {\n\
    width: 20rem;\n\
}\n\
button {\n\
    cursor: pointer;\n\
}\n\
pre {\n\
    overflow-wrap: break-word;\n\
    white-space: pre-wrap;\n\
}\n\
@keyframes uiAnimateShake {\n\
    100% {\n\
        transform: translateX(0);\n\
    }\n\
    0%, 20%, 60% {\n\
        transform: translateX(10px);\n\
    }\n\
    40%, 80% {\n\
        transform: translateX(-10px);\n\
    }\n\
}\n\
.uiAnimateShake {\n\
    animation-duration: 500ms;\n\
    animation-name: uiAnimateShake;\n\
}\n\
.uiAnimateSlide {\n\
    overflow-y: hidden;\n\
    transition: max-height ease-in 250ms, min-height ease-in 250ms, padding-bottom ease-in 250ms, padding-top ease-in 250ms;\n\
}\n\
@keyframes uiAnimateSpin {\n\
    0% { transform: rotate(0deg); }\n\
    100% { transform: rotate(360deg); }\n\
}\n\
.utility2FooterDiv {\n\
    text-align: center;\n\
}\n\
.zeroPixel {\n\
    border: 0;\n\
    height: 0;\n\
    margin: 0;\n\
    padding: 0;\n\
    width: 0;\n\
}\n\
</style>\n\
<style>\n\
/*csslint\n\
*/\n\
textarea {\n\
    font-family: monospace;\n\
    height: 10rem;\n\
    width: 100%;\n\
}\n\
textarea[readonly] {\n\
    background: #ddd;\n\
}\n\
</style>\n\
</head>\n\
<body>\n\
<div id="ajaxProgressDiv1" style="background: #d00; height: 2px; left: 0; margin: 0; padding: 0; position: fixed; top: 0; transition: background 500ms, width 1500ms; width: 0%; z-index: 1;"></div>\n\
<div class="uiAnimateSpin" style="animation: uiAnimateSpin 2s linear infinite; border: 5px solid #999; border-radius: 50%; border-top: 5px solid #7d7; display: none; height: 25px; vertical-align: middle; width: 25px;"></div>\n\
<script>\n\
/*jslint\n\
    bitwise: true,\n\
    browser: true,\n\
    maxerr: 8,\n\
    maxlen: 100,\n\
    node: true,\n\
    nomen: true,\n\
    regexp: true,\n\
    stupid: true\n\
*/\n\
(function () {\n\
    "use strict";\n\
    var ajaxProgressDiv1,\n\
        ajaxProgressState,\n\
        ajaxProgressUpdate,\n\
        timerIntervalAjaxProgressUpdate;\n\
    ajaxProgressDiv1 = document.querySelector("#ajaxProgressDiv1");\n\
    setTimeout(function () {\n\
        ajaxProgressDiv1.style.width = "25%";\n\
    });\n\
    ajaxProgressState = 0;\n\
    ajaxProgressUpdate = (window.local &&\n\
        window.local.ajaxProgressUpdate) || function () {\n\
        ajaxProgressDiv1.style.width = "100%";\n\
        setTimeout(function () {\n\
            ajaxProgressDiv1.style.background = "transparent";\n\
            setTimeout(function () {\n\
                ajaxProgressDiv1.style.width = "0%";\n\
            }, 500);\n\
        }, 1500);\n\
    };\n\
    timerIntervalAjaxProgressUpdate = setInterval(function () {\n\
        ajaxProgressState += 1;\n\
        ajaxProgressDiv1.style.width = Math.max(\n\
            100 - 75 * Math.exp(-0.125 * ajaxProgressState),\n\
            Number(ajaxProgressDiv1.style.width.slice(0, -1)) || 0\n\
        ) + "%";\n\
    }, 1000);\n\
    window.addEventListener("load", function () {\n\
        clearInterval(timerIntervalAjaxProgressUpdate);\n\
        ajaxProgressUpdate();\n\
    });\n\
}());\n\
</script>\n\
<h1>\n\
<!-- utility2-comment\n\
    <a\n\
        {{#if env.npm_package_homepage}}\n\
        href="{{env.npm_package_homepage}}"\n\
        {{/if env.npm_package_homepage}}\n\
        target="_blank"\n\
    >\n\
utility2-comment -->\n\
        {{env.npm_package_name}} (v{{env.npm_package_version}})\n\
<!-- utility2-comment\n\
    </a>\n\
utility2-comment -->\n\
</h1>\n\
<h3>{{env.npm_package_description}}</h3>\n\
<!-- utility2-comment\n\
<h4><a download href="assets.app.js">download standalone app</a></h4>\n\
<button class="onclick onreset" id="testRunButton1">run internal test</button><br>\n\
<div class="uiAnimateSlide" id="testReportDiv1" style="border-bottom: 0; border-top: 0; margin-bottom: 0; margin-top: 0; max-height: 0; padding-bottom: 0; padding-top: 0;"></div>\n\
utility2-comment -->\n\
\n\
\n\
\n\
<label>stderr and stdout</label>\n\
<textarea class="resettable" id="outputTextareaStdout1" readonly></textarea>\n\
<!-- utility2-comment\n\
{{#if isRollup}}\n\
<script src="assets.app.js"></script>\n\
{{#unless isRollup}}\n\
utility2-comment -->\n\
<script src="assets.utility2.rollup.js"></script>\n\
<script>window.utility2.onResetBefore.counter += 1;</script>\n\
<script src="jsonp.utility2.stateInit?callback=window.utility2.stateInit"></script>\n\
<script src="assets.cms2.js"></script>\n\
<script src="assets.example.js"></script>\n\
<script src="assets.test.js"></script>\n\
<script>window.utility2.onResetBefore();</script>\n\
<!-- utility2-comment\n\
{{/if isRollup}}\n\
utility2-comment -->\n\
<div class="utility2FooterDiv">\n\
    [ this app was created with\n\
    <a href="https://github.com/kaizhu256/node-utility2" target="_blank">utility2</a>\n\
    ]\n\
</div>\n\
</body>\n\
</html>\n\
';
        /* jslint-ignore-end */
        [
            'assets.index.css',
            'assets.index.template.html',
            'assets.swgg.swagger.json',
            'assets.swgg.swagger.server.json'
        ].forEach(function (file) {
            file = '/' + file;
            local.assetsDict[file] = local.assetsDict[file] || '';
            if (local.fs.existsSync(local.__dirname + file)) {
                local.assetsDict[file] = local.fs.readFileSync(
                    local.__dirname + file,
                    'utf8'
                );
            }
        });
        local.assetsDict['/'] =
            local.assetsDict['/assets.example.html'] =
            local.assetsDict['/assets.index.template.html']
            .replace((/\{\{env\.(\w+?)\}\}/g), function (match0, match1) {
                // jslint-hack
                String(match0);
                switch (match1) {
                case 'npm_package_description':
                    return 'the greatest app in the world!';
                case 'npm_package_name':
                    return 'cms2';
                case 'npm_package_nameLib':
                    return 'cms2';
                case 'npm_package_version':
                    return '0.0.1';
                default:
                    return match0;
                }
            });
        // init cli
        if (module !== require.main || local.global.utility2_rollup) {
            break;
        }
        local.assetsDict['/assets.example.js'] =
            local.assetsDict['/assets.example.js'] ||
            local.fs.readFileSync(__filename, 'utf8');
        // bug-workaround - long $npm_package_buildCustomOrg
        /* jslint-ignore-begin */
        local.assetsDict['/assets.cms2.js'] =
            local.assetsDict['/assets.cms2.js'] ||
            local.fs.readFileSync(
                local.__dirname + '/lib.cms2.js',
                'utf8'
            ).replace((/^#!/), '//');
        /* jslint-ignore-end */
        local.assetsDict['/favicon.ico'] = local.assetsDict['/favicon.ico'] || '';
        // if $npm_config_timeout_exit exists,
        // then exit this process after $npm_config_timeout_exit ms
        if (Number(process.env.npm_config_timeout_exit)) {
            setTimeout(process.exit, Number(process.env.npm_config_timeout_exit));
        }
        // start server
        if (local.global.utility2_serverHttp1) {
            break;
        }
        process.env.PORT = process.env.PORT || '8081';
        console.error('server starting on port ' + process.env.PORT);
        local.http.createServer(function (request, response) {
            request.urlParsed = local.url.parse(request.url);
            if (local.assetsDict[request.urlParsed.pathname] !== undefined) {
                response.end(local.assetsDict[request.urlParsed.pathname]);
                return;
            }
            response.statusCode = 404;
            response.end();
        }).listen(process.env.PORT);
        break;
    }
}());
```

#### output from browser
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.browser.%252F.png)](https://kaizhu256.github.io/node-cms2/build/app/assets.example.html)

#### output from shell
![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.svg)



# extra screenshots
1. [https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp%252Fassets.swgg.html.png](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp%252Fassets.swgg.html.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp%252Fassets.swgg.html.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp%252Fassets.swgg.html.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp.png](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithub.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithubTest.browser.%252Fnode-cms2%252Fbuild%252Fapp.png](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithubTest.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithubTest.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.deployGithubTest.browser.%252Fnode-cms2%252Fbuild%252Fapp.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.npmTest.browser.%252F.png](https://kaizhu256.github.io/node-cms2/build/screenshot.npmTest.browser.%252F.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.npmTest.browser.%252F.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.npmTest.browser.%252F.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.browser.%252F.png](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.browser.%252F.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.browser.%252F.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleJs.browser.%252F.png)

1. [https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleSh.browser.%252F.png](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleSh.browser.%252F.png)
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleSh.browser.%252F.png)](https://kaizhu256.github.io/node-cms2/build/screenshot.testExampleSh.browser.%252F.png)



# package.json
```json
{
    "author": "kai zhu <kaizhu256@gmail.com>",
    "description": "cms2 app",
    "devDependencies": {
        "electron-lite": "kaizhu256/node-electron-lite#alpha",
        "utility2": "kaizhu256/node-utility2#alpha"
    },
    "engines": {
        "node": ">=4.0"
    },
    "homepage": "https://github.com/kaizhu256/node-cms2",
    "keywords": [],
    "license": "MIT",
    "main": "lib.cms2.js",
    "name": "cms2",
    "nameLib": "cms2",
    "nameOriginal": "cms2",
    "os": [
        "darwin",
        "linux"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/kaizhu256/node-cms2.git"
    },
    "scripts": {
        "build-ci": "utility2 shReadmeTest build_ci.sh",
        "env": "env",
        "heroku-postbuild": "npm uninstall utility2 2>/dev/null; npm install kaizhu256/node-utility2#alpha && utility2 shDeployHeroku",
        "nameAliasPublish": "",
        "postinstall": "[ ! -f npm_scripts.sh ] || ./npm_scripts.sh postinstall",
        "start": "PORT=${PORT:-8080} utility2 start test.js",
        "test": "PORT=$(utility2 shServerPortRandom) utility2 test test.js"
    },
    "version": "2018.1.16"
}
```



# changelog of last 50 commits
[![screenshot](https://kaizhu256.github.io/node-cms2/build/screenshot.gitLog.svg)](https://github.com/kaizhu256/node-cms2/commits)



# internal build script
- build_ci.sh
```shell
# build_ci.sh

# this shell script will run the build for this package

shBuildCiAfter() {(set -e
    # shDeployCustom
    shDeployGithub
    # shDeployHeroku
    shReadmeTest example.sh
)}

shBuildCiBefore() {(set -e
    # shNpmTestPublished
    shReadmeTest example.js
)}

# run shBuildCi
eval $(utility2 source)
shBuildCi
```



# misc
- this package was created with [utility2](https://github.com/kaizhu256/node-utility2)
