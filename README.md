## Electron 桌面开发Demo

### 打包并分发应用
1.安装依赖
npm install --save-dev @electron-forge/cli
npx electron-forge import

2.使用 Forge 的 make 命令来创建可分发的应用程序：
npm run make

### 参考链接：
1.帮助文档 https://www.electronjs.org/zh/docs/latest/tutorial/quick-start#scaffold-the-project

2.在线制作ico http://www.ico51.cn/

### 其他说明 
如下载不成功，需手动下载的资源(放置C:\Users\{{computerName}}\AppData\Local\electron-builder\Cache)：

1.https://github.com/electron-userland/electron-builder-binaries/releases/download/winCodeSign-2.6.0/winCodeSign-2.6.0.7z

2.https://github.com/electron-userland/electron-builder-binaries/releases/download/nsis-3.0.4.2/nsis-3.0.4.2.7z

3.https://github.com/electron-userland/electron-builder-binaries/releases/download/nsis-resources-3.4.1/nsis-resources-3.4.1.7z

