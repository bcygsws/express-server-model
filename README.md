# 项目生成
## 项目构建
- 切换到路径 ./process18-express/day04 之下，使用命令：express 13-express-model,生成项目目录
- 进一步进入./process18-express/day04/13-express-model路径，使用命令：npm install 安装依赖包
- 改用ejs引擎，而非不熟悉的jade引擎。安装ejs包：npm install ejs --save ,卸载jade包，npm uninstall jade
- 修改app.js文件中的引擎。在引擎声明出，增加语句：app.engine('.html',ejs.__express); 设置引擎为app.set('view engine','html')
- 删除views中默认生成的3个jade文件。新建一个index.html文件
- npm run start 命令运行项目(项目默认端口为3000，如果端口被占用，在bin/www更改默认端口后，或者taskkill操作杀死占用端口3000的程序)
# 技术栈
