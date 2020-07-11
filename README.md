# sunny-future.github.io
Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@sunny-future 
PanJiaChen
/
vue-element-admin
2.1k
57.1k20k
Code
Issues
634
Pull requests
39
Actions
Projects
Wiki
Security
Insights
vue-element-admin/README.zh-CN.md
@EdwinBetanc0urt
EdwinBetanc0urt docs: Improve read me files and changes in Spanish. (#3234)
Latest commit 0ae5079 on 5 Jun
 History
 9 contributors
@PanJiaChen@lePig@yugasun@yamelsenih@TinaryTree@garethx@EdwinBetanc0urt@codeyu@Armour
245 lines (175 sloc)  9.89 KB
  


vue element-ui Build Status license GitHub release gitter donate

简体中文 | English | 日本語 | Spanish

简介
vue-element-admin 是一个后台前端解决方案，它基于 vue 和 element-ui实现。它使用了最新的前端技术栈，内置了 i18n 国际化解决方案，动态路由，权限验证，提炼了典型的业务模型，提供了丰富的功能组件，它可以帮助你快速搭建企业级中后台产品原型。相信不管你的需求是什么，本项目都能帮助到你。

在线预览

使用文档

Gitter 讨论组

Donate

Wiki

Gitee 在线预览（国内用户可访问该地址）

国内访问文档 文档（方便没翻墙的用户查看）

基础模板建议使用: vue-admin-template

桌面端: electron-vue-admin

Typescript 版: vue-typescript-admin-template (鸣谢: @Armour)

awesome-project

v4.1.0+版本之后默认 master 分支将不支持国际化，有需要的请使用i18n分支，它会和 master 保持同步更新

该项目不支持低版本浏览器(如 ie)，有需求请自行添加 polyfill 详情

目前版本为 v4.0+ 基于 vue-cli 进行构建，若发现问题，欢迎提issue。若你想使用旧版本，可以切换分支到tag/3.11.0，它不依赖 vue-cli

群主 圈子 群主会经常分享一些技术相关的东西，或者加入 qq 群 或者关注 微博

前序准备
你需要在本地安装 node 和 git。本项目技术栈基于 ES2015+、vue、vuex、vue-router 、vue-cli 、axios 和 element-ui，所有的请求数据都使用Mock.js进行模拟，提前了解和学习这些知识会对使用本项目有很大的帮助。

同时配套了系列教程文章，如何从零构建后一个完整的后台项目，建议大家先看完这些文章再来实践本项目

手摸手，带你用 vue 撸后台 系列一(基础篇)
手摸手，带你用 vue 撸后台 系列二(登录权限篇)
手摸手，带你用 vue 撸后台 系列三 (实战篇)
手摸手，带你用 vue 撸后台 系列四(vueAdmin 一个极简的后台基础模板)
手摸手，带你用vue撸后台 系列五(v4.0新版本)
手摸手，带你封装一个 vue component
手摸手，带你优雅的使用 icon
手摸手，带你用合理的姿势使用 webpack4（上）
手摸手，带你用合理的姿势使用 webpack4（下）
如有问题请先看上述使用文档和文章，若不能满足，欢迎 issue 和 pr

Edit on CodeSandbox



Sponsors
Become a sponsor and get your logo on our README on GitHub with a link to your site. [Become a sponsor]



Admin Dashboard Templates made with Vue, React and Angular.

功能
- 登录 / 注销

- 权限验证
  - 页面权限
  - 指令权限
  - 权限配置
  - 二步登录

- 多环境发布
  - dev
  - sit
  - stage
  - prod

- 全局功能
  - 国际化多语言
  - 多种动态换肤
  - 动态侧边栏（支持多级路由嵌套）
  - 动态面包屑
  - 快捷导航(标签页)
  - Svg Sprite 图标
  - 本地/后端 mock 数据
  - Screenfull全屏
  - 自适应收缩侧边栏

- 编辑器
  - 富文本
  - Markdown
  - JSON 等多格式

- Excel
  - 导出excel
  - 导入excel
  - 前端可视化excel
  - 导出zip

- 表格
  - 动态表格
  - 拖拽表格
  - 内联编辑

- 错误页面
  - 401
  - 404

- 組件
  - 头像上传
  - 返回顶部
  - 拖拽Dialog
  - 拖拽Select
  - 拖拽看板
  - 列表拖拽
  - SplitPane
  - Dropzone
  - Sticky
  - CountTo

- 综合实例
- 错误日志
- Dashboard
- 引导页
- ECharts 图表
- Clipboard(剪贴复制)
- Markdown2html
开发
# 克隆项目
git clone https://github.com/PanJiaChen/vue-element-admin.git

# 进入项目目录
cd vue-element-admin

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
浏览器访问 http://localhost:9527

发布
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
其它
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
更多信息请参考 使用文档

Changelog
Detailed changes for each release are documented in the release notes.

Online Demo
在线 Demo

Donate
如果你觉得这个项目帮助到了你，你可以帮作者买一杯果汁表示鼓励 🍹 donate

更多捐赠方式

Paypal Me

Buy me a coffee

购买贴纸
你也可以通过 购买官方授权的贴纸 的方式来支持 vue-element-admin - 每售出一张贴纸，本项目将获得 2 元的捐赠。

Browsers support
Modern browsers and Internet Explorer 10+.

IE / Edge
IE / Edge	Firefox
Firefox	Chrome
Chrome	Safari
Safari
IE10, IE11, Edge	last 2 versions	last 2 versions	last 2 versions
License
MIT

Copyright (c) 2017-present PanJiaChen

© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
