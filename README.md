# qexo-Fomal-docker
Fomalhaut + Qexo 
该项目是基于 Fomalhaut 和 Qexo 的整合项目，它将 Fomalhaut 的博客主题和 Qexo 的后端框架结合在一起，以创建一个完整的博客网站。

项目结构
该项目包含以下组件：

Fomalhaut 的前端组件，包括博客主题、样式和其他静态资源。
Qexo 的后端组件，包括数据库模型、API、身份验证和其他业务逻辑。
安装和使用
要在本地安装和运行该项目，请按照以下步骤操作：
下载docker-compose.yml
更改其中的域名内容,和hexo，qexo路径

sudo docker-compose up -d
在浏览器中访问 http://localhost:4000，你应该可以看到你的博客网站。
http://localhost:8000 访问后台
