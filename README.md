<div align="center">
    <img src="public/cover.png" alt='砚台封面' style="background-color: white;"/>
    <p align="center">
    <img src="https://img.shields.io/badge/vue-3.x-brightgreen.svg" alt="Vue 3" />
    <img src="https://img.shields.io/badge/github-api-blue.svg" alt="GitHub API" />
    <img src="https://img.shields.io/badge/typescript-4.x-007ACC.svg" alt="TypeScript" />
    <img src="https://img.shields.io/github/stars/2061360308/InkStone.svg?style=social" alt="Stars" />
    <img src="https://img.shields.io/github/forks/2061360308/InkStone.svg?style=social" alt="Forks" />
    <img src="https://img.shields.io/github/issues/2061360308/InkStone.svg?color=yellow" alt="Issues" />
    <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License" />
</p>
</div>

<h1>相关文档请见官网: <a href="https://inkstone.work" target="_blank">https://inkstone.work</a></h1>

# 砚台/InkStone

## develop分支开发新计划
> 功能都开发完了，接下来重点是一堆fix和chore，敬请期待。

- [ ] 重构css样式，更换sass语法。添加夜间模式支持
- [ ] 重构组件代码，分离混合搅乱的部分
- [ ] 添加按需导入，分片打包。优化加载速度
- [ ] 添加更加实用的图床管理功能
- [ ] 添加Wasm本地处理图片的能力
- [ ] Pwa优化，向本地编辑器功能看齐
- [ ] 完善现有的Codemirror编辑器功能
- [ ] 修复编辑器全屏Bug
- [ ] Front Matter 可视化编辑改为可选
- [ ] 修复个人Token登录流程



## 💡 介绍

《砚台》是一款由 Vue 开发的在线 Markdown 编辑器，特意为 Hexo、Hugo 等静态站点生成器设计，支持同步到 Github，可视化编辑 yaml front matter 等贴心功能。《砚台》完全运行在浏览器，可以和静态站点一起发布。

![展示图](docs/images/new-mian-image.png)

<div style="text-align: center;">
    <a href="docs/screenshots.md">@更多截图</a>
</div>

### 体验地址

[Vercel](https://dev.inkstone.work)

<!-- 1. [Github Pages](https://www.1think2program.cn/HugoEditor) -->

> 由于以上体验方式中 Github 认证服务所用服务器均由 Vercel 支持,且 Github Pages 无法重写路由规则，登录回调中重定向到/login 路径无法识别，所以暂不提供 Github Pages 体验方式。请等待后续修复路由模式。

## ✨ 特性

- 纯前端静态页面，可无需服务器
- 支持直接从 Github 仓库获取文件
- 支持批量提交文件到 Github
- 支持根据更改内容自动生成提交信息
- 本地缓存数据使用 IndexDB 保存
- 支持可视化编辑 Yaml Front Matter
- Markdown 编辑器支持所见即所得，及时渲染，分屏预览三种模式
- 支持大纲列表
- 支持对接对象存储作为图床

## ✅预计开发任务

- [x] 迁移整理图标相关代码
- [x] GitHub 拉取/提交文件策略更新
- [x] 文件管理器优化，外观，功能
- [ ] 主题统一，支持切换
- [x] 允许加载/保存全局配置
- [x] 编辑器添加处理格式字符串的功能
- [x] 事件总线完善
- [x] 更加完整的底部状态条功能
- [x] 提供更多登录方式,注册成为 GitHub App
- [x] 大纲列表
- [x] 搜索列表
- [x] 更完整的设置面板，支持更多可选项配置
- [x] 图床开发
- [x] 适配 history 和 hash 两种模式
- [ ] 自定义 Github 接口代理

> 如有新的需求或者急需上述某个功能可在 issue 中提出

## 🛠️ 开发/自部署

1. clone
2. pnpm install
3. pnpm run dev / pnpm build

自己部署需要：

1. 将 build 构建内容（dist 下）部署到自己服务器（可以和静态站点一同发布）
2. 如需自行配置 Github 登录服务器，则需自行申请 Github App，之后将 api 下接口部署到服务器

目前访问量较少不需要这么操作,如果觉得页面网速慢的话可以把静态文件放在自己服务器上，加快访问速度

## 📄 授权

InkStone 使用 MIT 开源协议。

## 🙏 鸣谢
**Vditor**：是一款浏览器端的 Markdown 编辑器，支持所见即所得、即时渲染（类似 Typora）和分屏预览模式。它使用 TypeScript 实现，支持原生 JavaScript 以及 Vue、React、Angular 和 Svelte 等框架。

**Vue**：Vue (pronounced /vjuː/, like view) is a progressive framework for building user interfaces. 

**Lute**：🎼 一款结构化的 Markdown 引擎，支持 Go 和 JavaScript

**highlight.js**：JavaScript syntax highlighter

**mermaid**：Generation of diagram and flowchart from text in a similar manner as Markdown

**incubator-echarts**：A powerful, interactive charting and visualization library for browser

**abcjs**：JavaScript library for rendering standard music notation in a browser