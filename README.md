# LeanTicket

## 开发帮助

先使用 LeanCloud 命令行工具将本项目与 LeanCloud 应用关联：

```
lean checkout
```
该项目默认 appId `qJnLgVRA9mnzVSw4Ho3HtIaI-gzGzoHsz` 。

### 安装依赖

```
npm install
```
依赖安装完毕会自动编译应用，如果后需要手动编译请执行：

```
npm run build
```

### 以生产环境方式启动
```
npm start
```

### 开发客户端

```
eval $(lean env) && npm run dev:client
```
该命令依赖 LeanCloud 命令行工具，因为需要 `lean env` 导出 appId 和 appKey。

### 开发服务端

```
lean up
# 或
eval $(lean env) && npm run dev
```
