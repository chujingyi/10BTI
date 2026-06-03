# 10BTI 追星人格测试

TEN 追星人格测评 · 10BTI

## 部署说明

### 部署到 Netlify

1. **创建 GitHub 仓库**
   - 访问 https://github.com/new
   - 仓库名：`10bti`
   - 选择 Private（私有）
   - 点击 Create repository

2. **上传代码**
   ```bash
   cd /Users/chujingyi/Downloads/gaoji/10BTI
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/10bti.git
   git push -u origin main
   ```

3. **连接 Netlify**
   - 访问 https://app.netlify.com
   - 点击 "Add new site" → "Import an existing project"
   - 选择 GitHub → 授权 → 选择 `10bti` 仓库
   - Deploy settings 保持默认
   - 点击 "Deploy site"

4. **自定义域名（可选）**
   - Site settings → Domain management → Add custom domain
   - 建议：`10bti.com` 或 `test.10bti.com`

## 项目结构

```
10BTI/
├── index.html    # 主页面（H5测试）
├── netlify.toml # Netlify 配置
└── README.md    # 说明文档
```

## 技术栈

- 纯前端 H5 页面
- Chart.js 雷达图
- QRCode.js 二维码生成
- Netlify 静态托管

## License

© HiTOMi · All Rights Reserved
