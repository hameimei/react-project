# NR-Enterprise
## 历史版本
### v1.0.0
1. 增加mysql数据库
2. 将数据移入mysql数据库中
### v0.1.6
1. 增加Prompt组件，替换所有alert
### v0.1.5
1. 增加了登录和注册页面的css样式
2. 支持中文文件名
### v0.1.4
1. 增加本地视频上传
2. 增加video-player组件
### v0.1.3
1. 增加视频播放时长
2. 增加视频蒙层，hover显示数据信息
3. 改造node层，增加获取数据信息的接口
### v0.1.2
1. 增加上传视频功能，扩展node层upload业务逻辑
2. 增加用户登出功能
3. 暂时所有提示框由alert代替，后期使用自定义组件代替
4. 视频目前只支持B站视频，暂时由于无B站视频源API，视频详情页由相应B站视频页代替
### v0.1.1
1. 修改信息部分从form表单上传改为fetch上传
2. 重构node层业务逻辑，增加获取用户信息接口，优化用户体验
3. 视频列表部分UI完成
### v0.1.0
初次开发，实现以下功能：
1. 用户登录以及注册
2. 用户信息修改
3. 图片上传与处理
## 技术栈
1. node.js (为了锻炼nodejs流程，没用express和koa框架，特意用原生撸的)
2. react.js （项目太小为了省事直接用react没用redux）
3. webpack (项目太小随便写写)
4. ECMAScript2015 (习惯问题)
5. pug (为了测试node配合模板输出)
6. sass (同样是习惯问题)
## 启动方式
1. 请确保3000端口以及4444端口未被占用
2. 请确保node版本在v4.4.4以上
3. 请确保电脑安装mysql数据库
4. 进入mysql创建数据库videoDB：CREATE DATABSE videoDB;
4. 在根目录安装所有依赖 npm install
5. 在终端运行脚本创建数据表 node createDB.js
6. 在终端启动node服务器 npm run start
7. 在终端启动webpack打包 npm run startfe
## 以上
