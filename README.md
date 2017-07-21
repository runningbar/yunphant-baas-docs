# yunphant-baas-docs
BaaS平台的文档仓库

文档页面：

使用方法：

* 使用Markdown编写帮助文档
* 不要使用中文作为md文件名，否则会导致RTD自动编译失败
* 将md文件存放在`docs`目录下。
* 在`./mkdocs.yml`文件中更新目录索引，就像下面这样：
```
pages:
- 首页: index.md
- 创建区块链网络环境: CreateNetwork.md
```
