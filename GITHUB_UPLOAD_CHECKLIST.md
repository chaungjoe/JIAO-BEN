# GitHub 上传清单

## 建议上传

- `index.html`
- `styles.css`
- `script.js`
- `api/`
- `favicon.svg`
- `og-image.svg`
- `site.webmanifest`
- `robots.txt`
- `vercel.json`
- `package.json`
- `.env.example`
- `.gitignore`
- `.vercelignore`
- `.nojekyll`
- `README.md`
- `DEPLOY.md`

## 不建议上传

- `.tools/`
- `node-v24.15.0-darwin-arm64.tar.xz`
- `short-video-script-tool.zip`
- `scriptlab-pro-vercel.zip`

## 上传到 GitHub 后

1. 打开 Vercel 新建项目页
2. 点击 `Continue with GitHub`
3. 授权并选择仓库
4. 添加环境变量 `OPENAI_API_KEY`
5. 点击 `Deploy`
