# Front-end and back-end separation blog based on Springboot + Vue development
<p align="center">
   <a target="_blank" href=https://github.com/YunhaoHan1997/myblog>
      <img src="https://img.shields.io/hexpm/l/plug.svg"/>
      <img src="https://img.shields.io/badge/JDK-1.8+-green.svg"/>
      <img src="https://img.shields.io/badge/springboot-2.4.2.RELEASE-green"/>
      <img src="https://img.shields.io/badge/vue-2.5.17-green"/>
      <img src="https://img.shields.io/badge/mysql-8.0.20-green"/>
      <img src="https://img.shields.io/badge/mybatis--plus-3.4.0-green"/>
      <img src="https://img.shields.io/badge/redis-6.0.5-green"/>
      <img src="https://img.shields.io/badge/elasticsearch-7.9.2-green"/>
      <img src="https://img.shields.io/badge/rabbitmq-3.8.5-green"/>
   </a>
</p>

[URL](#URL) | [Directory](#Directory) | [Feature](#Feature) | [Technology](#Technology)

## URL

**BLOG URL：** [www.sisyphean.ltd](http://www.sisyphean.ltd/)

**ADMIN URL：** [admin.sisyphean.ltd/website](http://admin.sisyphean.ltd/website)

test account: test@qq.com, password：123456, log in to view.

## Directory

````
blog-springboot
├── annotation -- custom annotation
├── aspect -- aop module
├── config -- configure module
├── constant -- constant module
├── consumer -- MQ consumer module
├── controller -- controller module
├── dao -- framework core module
├── dto -- dto module
├── enums -- enumerate modules
├── exception -- custom exception module
├── handler -- handler module (extended security filter, custom security prompt information, etc.)
├── service -- service module
├── strategy -- strategy module (used to expand third-party login, search mode, upload file mode and other strategies)
├── util -- utility module
└── vo -- vo module
````

## Feature

- The front desk refers to the "Butterfly" design of "Hexo", which is beautiful and simple, and has a good responsive experience.
- The background refers to the design of "element-admin", sidebar, history tab, and breadcrumbs are automatically generated.
- Using the Markdown editor, the writing method is simple.
- Comments support expression input reply, etc., refer to Valine for style.
- Add music player to support online search for songs.
- The front and back ends are deployed separately to adapt to the current trend.
- Access to third-party login to reduce registration costs.
- Support posting and talking, share interesting stories at any time.
- The message adopts the bullet curtain wall, which is more cool.
- Support code highlighting and copying, image preview, dark mode and other functions to improve user experience.
- Search articles support word segmentation, and the response speed is fast.
- Added functions such as article directory and recommended articles to optimize user experience.
- Added online chat room, which supports functions such as withdrawal, voice input, and unread count.
- Added aop annotation to implement log management.
- Support dynamic permission modification, adopt RBAC model, front-end menu and background permissions are updated in real time.
- Background management supports modifying background pictures, blog configuration and other information, easy to operate, and supports uploading photo albums.
- The code supports multiple search modes (Elasticsearch or MYSQL), supports multiple upload modes (OSS or local), and supports configuration.
- The code follows the Alibaba development specifications, which is beneficial for developers to learn.

## Technology
**Backend:** SpringBoot + nginx + docker + SpringSecurity + Swagger2 + MyBatisPlus + Mysql + Redis + elasticsearch + RabbitMQ + MaxWell + Websocket
**Frontend:** vue + vuex + vue-router + axios + vuetify + element + echarts
