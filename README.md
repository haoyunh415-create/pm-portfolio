# AI 产品经理求职作品集（pm.jianla.xyz）

面向 AI 产品经理（校招 · 创业/中小厂）的独立静态作品集，与现有 `me.jianla.xyz`（AI Agent 开发向）并存。差异化主线：**「懂技术边界的 AI 产品人」**。

## 技术

- 纯 HTML5 + CSS3，零依赖、零后端、零 JS。
- `index.html`（全部内容）+ `styles.css`（设计令牌 + 布局 + 响应式）。

## 内容

- Hero 定位
- 3 个产品案例（鉴来助手 / AI Interview Agent / GraphMind，统一 8 环结构）
- AI 产品判断力
- 关于我 · 联系

## 部署（Cloudflare Pages）

站点文件在仓库根；`docs/`、`.superpowers/` 为内部规划文档，**不上传公网**。部署时只上传站点文件：

```bash
mkdir -p .deploy && cp index.html styles.css .deploy/
wrangler pages deploy .deploy --project-name=pm-portfolio --branch=master
```

- 自定义域：`https://pm.jianla.xyz`（CNAME → `pm-portfolio-ewf.pages.dev`，DNS 在阿里云万网）
- Pages 域名：`https://pm-portfolio-ewf.pages.dev`

## 联系

邮箱 `2313370765@qq.com` · GitHub `haoyunh415-create`
