# 音频计算器NEXT

基于 Tauri v2 的跨平台桌面应用。前端为纯静态页面（`index/`），由 Tauri 内嵌 WebView 渲染。

## 本地开发

```bash
npm i
npm run tauri:dev
```

## 构建

```bash
npm run tauri:build
```

## CI（GitHub Actions）

推送到 `main/master` 将触发多平台构建，产物见 Actions artifacts。

## 目录

- index/           静态页面（入口 `index.html`）
- src-tauri/       Tauri 配置与 Rust 程序
- .github/workflows/build.yml  多平台构建工作流
