TypeScript 'ts-node-dev' Restart on Changes Demo
==================================================

使用`nodemon`的`--exec`来运行`ts-node`，监听文件自动重启可能会遇到一个问题，
就是`ts-node`没有成功重启，导致之前监听的端口没有释放，后续重启失败。

使用`ts-node-dev`则没有这个问题。

```
npm install
npm run dev
```
