# electron-kook

利用electron技术封装了kook-web的mac下软件。

编译

```bash
npm install
npx electron-forge import
npm run make
```

打包

```bash
npm run build
```

已知问题:

- ~~目前只支持短信验证码和账号密码登录，暂不支持微信扫码登录~~
- ~~mac下退出无法结束进程~~

更新日志：

#### 2022年10月31日

- 支持微信扫码登录
- 修复无法结束进程
- ~~修复可以听到声音和讲话~~

独立的app暂时没找到如何解决麦克风的问题。
