# AJAX

> 从jQuery 中提取出的 jQuery.ajax

1. 与 `jQuery.ajax` 接口完全一致
3. 压缩版大小 `32.65 KB`
4. GZIP大小 `13.2 KB`

## 安装

```shell
yarn add @onface/ajax
```

```html
<script src="https://unpkg.com/@onface/ajax@0.1.0/ajax.js"></script>
```

## 使用

```js
var $ = require("@onface/ajax")
// or global window.$ or window.ajax
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
