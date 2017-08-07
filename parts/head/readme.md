# Head

用于生成模板中的 HTML head



#### 使用

```html
<%- include('parts/head/main', {
  title: '标题',
    css: [
      'contents/css/reset.css',
      'contents/css/layout.css'
    ],
    mobile: false
}) %>
```



#### API

- title: [string] 网页标题
- css: [array] 要引入的样式表数组
- mobile: [boolean] 是否使用 h5 的 rem js 布局

