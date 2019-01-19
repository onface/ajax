# AJAX

> 从jQuery 中提取出的 jQuery.ajax

1. 与 `jQuery.ajax` 接口完全一致
3. 压缩版大小 `32.65 KB`
4. GZIP大小 `13.2 KB`

## 安装

```js
yarn add @onface/ajax
```

<script src="https://unpkg.com/@onface/ajax/ajax.js"></script>

## 使用

```js
var $ = require("@onface/ajax")
$.ajax({
    type: 'get',
    url: 'https://echo.onface.live/onface/echo/mock/list',
    data: {
        page: 2
    }
}).done(function (res) {
    console.log(res)
}).fail(function () {
    alert('网络错误')
})
```
