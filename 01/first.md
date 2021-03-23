# 初始化项目

#### 遇到的问题：在哪初始化？

#### 解决：在cmd窗口输入

```docsify init ./docs```

其中init表示初始化，“.”表示当前目录，“/“后面取一个项目的名字

初始化成功后，可以看到 `./docs` 目录下创建的几个文件

- `index.html` 入口文件
- `README.md` 会做为主页内容渲染
- `.nojekyll` 用于阻止 GitHub Pages 忽略掉下划线开头的文件

直接编辑 `docs/README.md` 就能更新文档内容。

