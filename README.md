# movie-card

一个用纯 HTML + CSS 写的电影卡片练习。

## 效果

鼠标悬停时卡片会轻微上浮、阴影加深，带 0.3 秒过渡动画。

## 内容

展示电影《生活多美好》(It's a Wonderful Life, 1946) 的海报、标题和简介。

## 用到的 CSS 知识点

| 属性 | 作用 |
|---|---|
| max-width + margin auto | 卡片限宽并水平居中 |
| padding | 内容到边框的距离 |
| border-radius | 圆角 |
| box-shadow | 阴影 |
| transition | 让属性变化变平滑 |
| transform: translateY | 悬停时向上位移 |
| @media (max-width: 720px) | 小屏幕下缩小留白，简单响应式 |
| text-align: justify | 简介文字两端对齐 |
| line-height | 行距 |

## 文件说明

- `movie-card.html` —— 自包含单文件，CSS 写在 `<style>` 标签里
- `p771490367.webp` —— 海报图片，需与 html 放在同一目录

## 怎么打开

双击 `movie-card.html`，用浏览器打开即可。
