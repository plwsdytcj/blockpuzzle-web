# Block Puzzle – 官方网站

静态站点，包含：
- 首页（index.html）
- 隐私政策（privacy.html）
- 使用条款（terms.html）
- 支持与联系（support.html）
- `app-ads.txt`（用于 AdMob 授权）

## 本地预览
任何静态服务器都可以，例如：

```
python3 -m http.server -d . 5500
```

访问 http://localhost:5500

## 部署到 Vercel
- 直接导入此仓库，Framework 选择 `Other`
- 自有域名绑定后，确保 `https://你的域名/app-ads.txt` 可访问

