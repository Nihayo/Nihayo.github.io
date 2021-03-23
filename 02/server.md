# 启动服务器

原文：“通过运行 `docsify serve` 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 [http://localhost:3000](http://localhost:3000/) 。

```bash
docsify serve docs
```

更多命令行工具用法，参考 [docsify-cli 文档](https://github.com/docsifyjs/docsify-cli)。”

#### 问题：在哪启动？

#### 解决：在cmd窗口输入docsify serve docs，注意serve最后没有r，

效果如下：

![](C:\Users\Admin\Desktop\doc\docsify1.png)

然后在浏览器输入 给出的网址：http://localhost:40669

(注：网址不唯一，默认是http://localhost:3000

图中是因为被占用的原因吧)

回车即可打开页面预览，注意：此命令窗口点x后，服务器就关闭了，输入网址也就没用了，但是关闭服务器最好用ctrl+c快捷键关闭，如果直接点x可能导致服务器异常终止，导致某些数据丢失。