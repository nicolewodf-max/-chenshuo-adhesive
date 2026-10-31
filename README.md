# Chenshuo B2B Website（中空玻璃耗材外贸官网）

纯 HTML + CSS 静态网站，无 JavaScript，响应式（手机自适应），谷歌 SEO 友好。

## 文件结构

```
b2b-website/
├── index.html        # 首页
├── products.html     # 产品页（硅酮胶 / 丁基胶 / 铝隔条 / 分子筛）
├── about.html        # 公司介绍
├── contact.html      # 联系页（Formspree 询盘表单）
├── css/
│   └── style.css     # 全部样式（移动优先）
├── images/           # 图片占位目录，放真实图片后替换
└── README.md
```

## 上线前必改清单

1. **Formspree 表单 ID**：打开 `contact.html`，把 `action="https://formspree.io/f/YOUR_FORM_ID"` 中的
   `YOUR_FORM_ID` 换成你在 [formspree.io](https://formspree.io/) 创建表单后得到的真实 ID。
2. **图片**：把真实产品图/工厂图放入 `images/` 目录，文件名与页面中 `<img src>` 的引用一致
   （如 `hero.jpg`、`silicone-sealant.jpg`、`butyl-sealant.jpg`、`aluminum-spacer.jpg`、
   `molecular-sieve.jpg`、`factory.jpg`、`company.jpg`、`quality.jpg`）。推荐 3:2 或 16:9 横图。
3. **联系方式**：4 个页面的页脚及 `contact.html` 中，替换占位邮箱 `sales@example.com`、
   电话 `+86 138 0000 0000`、地址（江西鹰潭）为真实信息。
4. **canonical 链接**：每页 `<head>` 中的 `https://www.yourdomain.com/...` 替换为正式域名。
5. **产品参数**：`products.html` 中的规格表为行业典型值，标注了 `<!-- TODO -->` 注释，
   请与生产团队核对后发布。
6. **公司信息**：`about.html` 中的公司介绍为通用描述，成立年份、认证、产能等需核验后补充。

## 本地预览

直接双击 `index.html` 用浏览器打开即可；表单提交需配置好 Formspree ID 并联网。

## 说明

- 字体来自 Google Fonts（Barlow / Barlow Condensed），无法访问时自动回退系统字体。
- 页内锚点、移动端菜单均为纯 CSS 实现，无任何 JS。
