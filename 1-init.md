# 启动vscode项目
💡 **提示：** node 版本需要控制在20.15.1以上
### 运行 web 版本
```sh
1. git clone https://github.com/microsoft/vscode.git
2. npm install ｜ yarn
3. npm run compile
4. npm run watch | yarn watch(时时编译ts源码)
5. node ./scripts/code-web.js --verbose
```
### 运行 Electron 版本 -- todo
💡 **提示：** 如果遇见报错信息 `have 'arm64', need 'x86_64')` 
```sh
rm -rf node_modules/@vscode/spdlog/build
npm rebuild @vscode/spdlog
```
```sh
1. git clone https://github.com/microsoft/vscode.git
2. npm install ｜ yarn
3. npm run compile
4. npm run watch | yarn watch(时时编译ts源码)
5. ./scripts/code.sh
```