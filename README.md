<div align=center><img src="logo.jpg"/></div>

---
### 相关工程
##### 领课教育系统(roncoo-education)：[码云地址](https://gitee.com/roncoocom/roncoo-education) | [Github地址](https://github.com/roncoo/roncoo-education)
##### 前端门户系统(roncoo-education-web)：[码云地址](https://gitee.com/roncoocom/roncoo-education-web) | [Github地址](https://github.com/roncoo/roncoo-education-web)
##### 后台管理系统(roncoo-education-admin)：[码云地址](https://gitee.com/roncoocom/roncoo-education-admin) | [Github地址](https://github.com/roncoo/roncoo-education-admin)
---

# 领课教育 - 一个全行业都适用的分布式在线教育系统

### 项目介绍（如果对你有用，请给个star！）
领课教育（roncoo-education）是基于领课网络多年的在线教育平台开发和运营经验打造出来的产品，致力于打造一个全行业都适用的分布式在线教育系统。系统采用前后端分离模式，前台采用vue.js为核心框架，后台采用Spring Cloud为核心框架。系统目前主要功能有课程点播功能，支持多家视频云的接入，课程附件管理功能，支持多家存储云的接入，讲师管理功能，支持讲师入驻功能，可以帮助个人或者企业快速实现一个轻量级的在线教育平台。

### 特别说明
* 系统功能通用，无论是个人还是企业都可以利用该系统快速搭建一个属于自己的在线教育平台。
* 系统采用MIT开源协议，可以在商业项目中免费使用或者二次开发而不必支付任何费用。
* 基于领课网络的商业项目，代码保证100%开源。

### 前台主要功能介绍
* 首页功能，导航模块（自定义导航设置），广告模块（自定的轮播设置），课程模块（自定义课程设置）
* 列表功能，分类模块（自定义分类设置），搜索模块（自定义搜索设置）
* 课程详情页功能，课程介绍、目录的展示和购买、播放功能等等
* 个人中心，具有个人信息设置、密码修改、订单管理、学习记录等功能
* 讲师中心，讲师信息管理、课程管理（课程的添加、修改）、收益管理等功能

### 后台主要功能介绍
* 权限管理功能，多角色多用户自定义配置
* 系统配置功能，自定义进行站点配置及第三方参数配置
* 讲师管理功能，讲师申请入驻，后台具有审核功能
* 课程管理功能，讲师管理自有课程，后台具有审核功能
* 用户登录功能，同一时间只允许同一个账号在同一个地方登录，防止账号共享
* 广告管理功能，后台自定义广告设置，增加营销效果
* 支付功能模块，系统无缝集成了龙果支付

### 演示地址
##### 前端演示地址：[领课教育](http://edu.os.roncoo.com/) | 后台演示地址：[运营后台](http://roncoo.vicp.net/web)

### 使用文档
##### [项目介绍](https://blog.roncoo.com/article/1105321762337357826) | [部署文档](https://blog.roncoo.com/article/1103554925858197505) | [常见问题](https://blog.roncoo.com/article/1105309620724858882)

### 官方QQ群（加群免费获取sql脚本）

<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=1ab031ece9d457fb7c275b0e95466dedfdf71091784f4c0b2c93ca4cc89e736d"><img border="0" src="https://pub.idqqimg.com/wpa/images/group.png" alt="在线教育系统-领课⑤" title="在线教育系统-领课⑤"> 903738971</a>

<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=e28093a355b157fd5d907856a336a558a16255abb466bdfa9e7a5cc91274b871"><img border="0" src="https://pub.idqqimg.com/wpa/images/group.png" alt="在线教育系统-领课④" title="在线教育系统-领课④"> 74876271</a> 已满

<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=b574c38c199744e267868108f509c06259314305130ac488d1734bdac4c8ed9f"><img border="0" src="https://pub.idqqimg.com/wpa/images/group.png" alt="在线教育系统-领课③" title="在线教育系统-领课③"> 774890501</a> 已满

<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=eb6b00779393483d8675185a7ab159326d493b5e220d73a3ee8843c8643ab340"><img border="0" src="https://pub.idqqimg.com/wpa/images/group.png" alt="在线教育系统-领课②" title="在线教育系统-领课②"> 702189511</a> 已满

<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=496f164099fc5c49fa5b4766cb6623f64f6318841e79aee54a60e4a6efe0a7f4"><img border="0" src="https://pub.idqqimg.com/wpa/images/group.png" alt="在线教育系统-领课①" title="在线教育系统-领课①"> 826617734</a> 已满

### 商业合作
* 如果想使用教育系统，我们商业版功能更强大！
* 如果想定制教育系统，我们提供有偿服务支持！
* 如果想运营教育平台，我们有提供Saas云服务！
* 支持其他合作方式，欢迎来撩！
* 商务合作联系QQ：513781560
* 商务合作联系QQ：2955237748
* 官网地址：[https://edu.roncoo.net](https://edu.roncoo.net/index.html)

#### 目录结构
``` 
roncoo-education-web/
├── api/ api接口列表目录
│   ├── method.js
│   ├── main.js
├── assets/ 公用的静态资源目录
│   ├── CSS/
│   ├── JS
│   ├── fonts
│   ├── image
├── component/ 
│   ├── 所有的自定义组件
├── config/ 配置文件目录
│   ├── conf.js  系统编译配置文件
│   ├── index.js  系统全局配置文件
│   ├── dev.env.js  开发模式的全局配置
│   ├── pro.env.js  生产模式的全局配置
│   ├── index.js  测试模式的全局配置
├── layouts/
│   ├── 布局目录
├── middleware/
│   ├── 中间件目录
├── pages/
│   ├── 页面目录
├── plugins/
│   ├── 所有的第三方或自定义插件的目录
├── static/
│   ├── 静态文件目录
├── store/
│   ├── actions.js
│   ├── getters.js
│   ├── index.js
│   ├── mutations.js
├── utils/
│   ├── 自定义工具类目录
└── next.config.js   nextjs 配置文件 
```

#### 编译使用
``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

```
