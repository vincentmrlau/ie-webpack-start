# Pcss

## 修改配置文件
文件地址：[config/webpack/base/base.js](/config/webpack/base/base.js)
* 重点：
  * 修改项： `cssType`
  * 样式文件后缀需要与`cssType`对应;

```js
module.exports = {
  mainJS: true,
  devHost: '0.0.0.0',
  devPort: '3000',
  viewType: 'html',
  cssType: 'pcss', // sass,scss,less,pcss,css...
  cdnPath: './', 
  version: '1.0.0'
};
```