# fixedWinBtn

窗口固定按钮功能



#### 使用

```html
<%- include('parts/fixedWinBtn/main', {
    btns: [
        {
            text: '视频',
            href: '#',
            icon: 'contents/img/fixedBtn/video-icon.png'
        },
        {
            text: '联网',
            href: '#',
            icon: 'contents/img/fixedBtn/net-icon.png'
        },
        {
            text: '模板',
            href: '#',
            icon: 'contents/img/fixedBtn/mod-icon.png'
        }
    ]
}) %>
```

```css
/* 引用基础样式 */
@import url('../../parts/fixedWinBtn/contents/css/layout.css');
```

#### API

- Btns [array] 按钮数据
  - text [string] 说明
  - href [string] 地址
  - icon [string] 图片地址
  - css [class] 引用样式名

