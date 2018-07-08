# koa-web
koa-web

- website：https://koa.bootcss.com/#

- demo: 
  - n-club: https://github.com/nswbmw/N-club
  - doc: https://nswbmw.github.io/N-club/


## quick staart
```
const Koa = require('koa');
const app = new Koa();

app.use(async ctx => {
  ctx.body = 'Hello World';
});

app.listen(3000);

app.js 中有一个 ctx，这是一个 Koa 提供的 Context 对象，封装了 request 和 response
```

## install

```
npm i koa -S

一点点搭建环境的话，感觉好麻烦, 狼叔-桑世龙写的koa-generator
npm install -g koa-generator

 koa2 Hello
 
 cd Hello
$ npm install
  npm start

open http://localhost:3000/
```


