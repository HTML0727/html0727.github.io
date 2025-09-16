# HTML0727's Blog

🚀 This is a personal blog built with [Hugo](https://gohugo.io/) + [m10c theme](https://github.com/vaga/hugo-theme-m10c).  
Supports **中文 / English / 日本語** and auto-deploys to GitHub Pages.

## ✨ Features
- Multilingual (ZH / EN / JA)
- Simple and clean m10c theme
- Glassmorphism fade-in effect
- Dark / light mode toggle
- GitHub Actions auto-deployment

## 📂 Structure
- `content/` → Blog posts by language
- `static/` → Static assets (images, JS, CSS)
- `layouts/` → Templates (header customized with language switcher)
- `.github/` → CI/CD workflow

## 📝 How to write posts
1. Go to `content/{lang}/posts/`
   - Chinese: `content/zh/posts/`
   - English: `content/en/posts/`
   - Japanese: `content/ja/posts/`
2. Create a Markdown file, e.g.
   ```
   content/en/posts/my-new-post.md
   ```
3. Push to repository → GitHub Actions will build & deploy automatically.

## 🌍 Live Blog
👉 https://html0727.github.io
