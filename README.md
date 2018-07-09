# eslint-config-fmfe-vue

ESLint configuration of [Followme Frontend Team](https://github.com/fmfe)
Vuejs group, base on [standard](https://github.com/standard/standard).

## usage

edit configuration file:

```
$ touch .eslintrc.js
```
```javascript
module.exports = {
  extends: '@fmfe/fmfe-vue',
};
```

## install

```
$ npm install eslint @fmfe/eslint-config-fmfe-vue -D
$ ./node_modules/.bin/eslint *.vue
```
or
```
$ npm install eslint @fmfe/eslint-config-fmfe-vue -g
$ eslint *.vue
```

## rules

*   基本规则
    *   [standard 规范](https://standardjs.com/rules-zhcn.html)
*   附加规则
    *   行尾必须加分号
    *   缩进使用 4 个空格
    *   要求使用 let 或 const 而不是 var
    *   优先使用 const，其次才是 let

## contributing
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## license
this repo is released under the [MIT License](http://www.opensource.org/licenses/MIT).
