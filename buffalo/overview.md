### 欢迎加入！

#### 虽然 Buffalo 可以被看作是一个框架，但它主要是一个go的生态系统，而 Javascript 库则被整合在一起。 这些组件中的大多数都可以切换到另一个组件，但我们只提供对这种默认组合的支持。


#### 在本章中，我们将介绍水牛城应用程序附带的默认app

----
## 后端库
### Buffalo
#### Buffalo 是所有提供的组件之间的“粘合剂” ，它包装库并管理工作流。
#### Gorilla / mux 是 Go 中使用最多的路由器之一。 虽然有些路由器速度更快(比如 httprouter) ，但 gorilla / mux 提供的功能最多，而且速度足够快
*****
### Pop
#### Pop 是 Buffalo 的默认 ORM。 它提供了 soda 工具箱来帮助您满足数据库需求，并支持多个数据库，如 PostgreSQL、 MySQL 和 SQLite。
*****
### Plush
#### plush是 Buffalo 的默认模板引擎。它的语法接近 ERB 模板(在 Ruby 中)。
*****
### Packr
#### Packr 是静态资产(模板、图像等)的一个打包机。 Packr 的目标是生成一个包含所有内容的最终二进制文件。
*****
##  前端库
### Bootstrap
#### Bootstrap 是最著名的前端工具包库之一。 它有助于使用表、旋转木马或网格布局等常见组件构建响应式界面。
*****
### JQuery
#### Jquery 是一个丰富的库，旨在简化 DOM 操作和 AJAX 查询。 虽然现在很少使用，但是许多项目仍然把它作为一个辅助工具来帮助支持所有的浏览器。
*****
### Webpack
#### Webpack 是一个著名的 Javascript 资产捆绑器，它可以处理 Javascript、 CSS、图片和静态资产文件
#### Webpack 默认配置为散列并减少资产













