# request-my

做项目的初衷：
    大家经常用http请求，以前用的比较多的是jq的ajax，现在用的多的是axios，我就是想写一个比较简单的http请求工具，平时html也能使用，就是简单使用及测试用的。希望大家多多使用。

## 安装

使用 npm:

```bash
$ npm install request-my --save
```

## 例子

Usage

ES2015

```js
import {api} from 'request-my';

api.ajax({
    url:'xxx:3000/post',
    type:'post',
    data:{
      name:'shibin'
    },
    success:function(res){
      console.log(res)
    },
    error:function(err){
      console.log(err);
    }
})
```
浏览器使用
The dist folder contains index.js.

```js

<script type="text/javascript" src="./dist/index.js"></script>
<script>
api.ajax({
    url:'xxx:3000/post',
    type:'post',
    data:{
      name:'shibin'
    },
    success:function(res){
      console.log(res)
    },
    error:function(err){
      console.log(err);
    }
})
</script>
```

# request-my

## Installing

Using npm:

```bash
$ npm install request-my --save
```


## Example

Usage

ES2015

```js
import {api} from 'request-my';

api.ajax({
    url:'xxx:3000/post',
    type:'post',
    data:{
      name:'shibin'
    },
    success:function(res){
      console.log(res)
    },
    error:function(err){
      console.log(err);
    }
})
```
Browser globals
```js
<script type="text/javascript" src="./dist/index.js"></script>
<script>
api.ajax({
    url:'xxx:3000/post',
    type:'post',
    data:{
      name:'shibin'
    },
    success:function(res){
      console.log(res)
    },
    error:function(err){
      console.log(err);
    }
})
</script>
```