# qexo-Fomal-docker
本项目将 ![hexo-theme-Fomalhaut](https://github.com/fomalhaut1998/hexo-theme-Fomalhaut) 和 ![Qexo](https://github.com/Qexo/Qexo) 整合在一起，创建一个完整的博客网站。其中 Fomalhaut 提供了博客主题和静态资源，Qexo 提供了后端框架和业务逻辑。

项目结构
本项目包括以下组件：

Fomalhaut 的前端组件，包括博客主题、样式和其他静态资源。
Qexo 的后端组件，包括数据库模型、API、身份验证和其他业务逻辑。
使用说明
要在本地安装和运行该项目，请按照以下步骤操作：

下载 docker-compose.yml 文件。
更改其中的域名、hexo 和 qexo 路径。
在终端中输入以下命令启动容器：sudo docker-compose up -d。
在浏览器中访问 http://localhost:4000，即可查看你的博客网站。
如果需要访问后台，请访问 http://localhost:8000。
