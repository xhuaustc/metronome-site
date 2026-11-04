知拍节拍器 · 官网页面

- [应用介绍 / 推广落地页](https://xhuaustc.github.io/metronome-site/intro.html)
- [隐私政策](https://xhuaustc.github.io/metronome-site/)
- [技术支持](https://xhuaustc.github.io/metronome-site/support.html)

## 页面说明

- `index.html` 是已填入 App Store Connect 的隐私政策 URL，**请勿改动或移动**，否则审核中的链接会失效。
- `intro.html` 是面向微信等自媒体的应用详情推广页：单文件、内联 CSS/JS、无外部字体或 CDN 依赖，移动端优先并适配桌面宽屏。
- `assets/` 存放压缩后的 7 张产品截图与 900×900 的微信分享封面 `share.jpg`，总计约 400 KB。
- 应用上架后，把 `intro.html` 脚本顶部的 `APP_STORE_URL` 常量填成 App Store 链接，两个下载按钮会自动切换为可点击状态；当前显示「审核中 · 即将上线」。
- 分享卡片使用 `og:image` 指向 GitHub Pages 上的绝对地址，需先推送并由 Pages 重建后，微信才能抓到缩略图。
- 推送到 `main` 后 Pages 自动重建；新增页面不会影响隐私政策与技术支持的既有 URL。
