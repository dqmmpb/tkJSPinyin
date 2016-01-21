# tkJSPinyin
Get Chinese pinyin from Chinese. Based on [JSPinyin](https://github.com/chinalu/JSPinyin). Ported to ES6, no need for mootool, etc. See `/src` for code.


# How to use
include the js file, and type:
```js
var pinyin = new Pinyin(false, 'default');	//	checkPolyphone = false;	charcase = 'default';
alert(pinyin.getFullChars('你好中国'));
```
