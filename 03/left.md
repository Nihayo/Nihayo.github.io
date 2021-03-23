# 侧边栏

首先要去`index.html` 入口文件中修改代码，

如下位置添加 loadSidebar: true

```html
<script>
window.$docsify = { 
  loadSidebar: true 
}
</script> 
```

将   name: '', repo: ''去掉。

接着在根目录创建 `_sidebar.md` 文件，内容如下

```markdown
* [首页](zh-cn/)
* [指南](zh-cn/guide)
```

