## 版本迭代信息
### v1.0.0
1. 使用mysql数据库
2. 提示信息使用Prompt组件
3. video-player实现视频上传
4. 视频蒙层，hover显示数据信息
5. 改造node层，增加获取数据信息的接口
6. 修改信息部分从form表单上传改为fetch上传
7. 用户注册，登录，修改个人信息，退出
## 技术栈
1. node.js (为了锻炼nodejs流程，没用express和koa框架，特意用原生写的)
2. react.js （项目太小为了省事直接用react没用redux）
3. webpack (项目太小随便写写)
4. ECMAScript2015 (学习ES6)
5. pug (jade的更名为了测试node配合模板输出)
6. sass (css更快)
## 启动方式
1. 请确保3000端口以及4444端口未被占用
2. 请确保node版本在v4.4.4以上
3. 请确保电脑安装mysql数据库
4. 进入mysql创建数据库videoDB：CREATE DATABSE videoDB;
4. 在根目录安装所有依赖 npm install
5. 在终端运行脚本创建数据表 node createDB.js
6. 在终端启动node服务器 npm run start
7. 在终端启动webpack打包 npm run startfe
