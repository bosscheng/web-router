# 简介
利用 window.history api 结合  popstate 实现的  路由，推荐 wap 端 单页面使用。



## 使用


```
// AMD
import SnRouter from 'web-router';

var router = new Router();
```


```
// CMD
var Router = require('./storage');

var router = new Router();
```


```
// browser
var Router = window.Router;

var router = new Router();
```


## API


### getCurrentRoute

### registerRoute

### forwardRoute

### replaceRoute

### forwardUrl

### replaceUrl
