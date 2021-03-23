来源为官方文档：

# [封面](https://docsify.js.org/#/zh-cn/cover?id=封面)

通过设置 `coverpage` 参数，可以开启渲染封面的功能。具体用法见[配置项#coverpage](https://docsify.js.org/#/configuration?id=coverpage)。

## [基本用法](https://docsify.js.org/#/zh-cn/cover?id=基本用法)

封面的生成同样是从 markdown 文件渲染来的。开启渲染封面功能后在文档根目录创建 `_coverpage.md` 文件。渲染效果如本文档。

*index.html*

```html
<!-- index.html -->

<script>
  window.$docsify = {
    coverpage: true
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
<!-- _coverpage.md -->

![logo](_media/icon.svg)

# docsify <small>3.5</small>

> 一个神奇的文档网站生成器。

- 简单、轻便 (压缩后 ~21kB)
- 无需生成 html 文件
- 众多主题

[GitHub](https://github.com/docsifyjs/docsify/)
[Get Started](#docsify)
```