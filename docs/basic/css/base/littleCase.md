# 小知识点

## link 和@import 的区别

两者都是外部引用 CSS 的方式, 它们的区别如下：

- `link` 是 XHTML 标签, 除了加载 CSS 外, 还可以定义 RSS 等其他事务
- `@import` 属于 CSS 范畴, 只能加载 CSS.
  - <span class="cor-in">link 引用 CSS 时, 在页面载入时同时加载</span>
  - <span class="cor-wa">@import 需要页面网页完全载入以后加载.</span>
  - <span class="cor-in">link 是 XHTML 标签, 无兼容问题</span>
  - <span class="cor-wa">@import 是在 CSS 2.1 提出的, 低版本的浏览器不支持.</span>
  - <span class="cor-in">link 支持使用 Javascript 控制 DOM 去改变样式</span>
  - <span class="cor-wa">@import 不支持.</span>
