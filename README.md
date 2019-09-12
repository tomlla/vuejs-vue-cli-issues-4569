See https://github.com/vuejs/vue-cli/issues/4569


# How to reproduce

```shell
$ npm install
$ npm run serve

> test@0.1.0 serve /home/nt/dev/src/github.com/tomlla/vuejs-vue-cli-issues-4569
> vue-cli-service serve

 ERROR  TypeError: Cannot read property 'version' of undefined
TypeError: Cannot read property 'version' of undefined
    at module.exports (/home/nt/dev/src/github.com/tomlla/vuejs-vue-cli-issues-4569/node_modules/@vue/cli-plugin-eslint/index.js:18:27)
    at plugins.forEach (/home/nt/dev/src/github.com/tomlla/vuejs-vue-cli-issues-4569/node_modules/@vue/cli-service/lib/Service.js:83:7)
    at Array.forEach (<anonymous>)
    at Service.init (/home/nt/dev/src/github.com/tomlla/vuejs-vue-cli-issues-4569/node_modules/@vue/cli-service/lib/Service.js:81:18)
    at Service.run (/home/nt/dev/src/github.com/tomlla/vuejs-vue-cli-issues-4569/node_modules/@vue/cli-service/lib/Service.js:220:10)
    at Object.<anonymous> (/home/nt/dev/src/github.com/tomlla/vuejs-vue-cli-issues-4569/node_modules/@vue/cli-service/bin/vue-cli-service.js:37:9)
    at Module._compile (internal/modules/cjs/loader.js:816:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:827:10)
    at Module.load (internal/modules/cjs/loader.js:685:32)
    at Function.Module._load (internal/modules/cjs/loader.js:620:12)
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! test@0.1.0 serve: `vue-cli-service serve`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the test@0.1.0 serve script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     /home/nt/.npm/_logs/2019-09-12T13_03_27_753Z-debug.log
```
