# 开发工具

`Dcat Admin`提供了一些开发工具以帮助开发者提升开发效率，以下所有工具都需要开启`app.debug`配置参数后才能使用。

### 代码生成器

代码生成器可以通过界面一键生成增删改查代码，支持根据已有数据表生成增删改查代码，打开浏览器访问`http://localhost:8000/admin/helpers/scaffold`即可使用。


### 扩展包管理
`Dcat Admin`支持可视化管理扩展包，只要通过`composer`安装进来的扩展包都能在管理界面中看到，支持通过界面启用和导入扩展包，打开浏览器访问`http://localhost:8000/admin/helpers/extensions`即可使用。

### IDE自动补全
通过`php artisan admin:ide-helper`命令可以生成IDE自动补全文件，可以生成`Grid`、`Form`、`Show`等功能的IDE自动补全提示文件。

### 图标
访问`http://localhost:8000/admin/helpers/icons`可以查看已支持的图标列表。

