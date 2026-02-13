# 快速开始指南 | Quick Start Guide

## 🚀 5分钟快速部署

### 第一步：初始化 Git 仓库

```powershell
cd c:\Users\31588\Desktop\Profile
git init
git config user.name "Zhang Xu"
git config user.email "mail_zhangxu@126.com"
```

### 第二步：创建 GitHub 仓库

1. 访问 [github.com/new](https://github.com/new)
2. 仓库名：`yourusername.github.io`（用你的GitHub用户名替换）
3. 选择 **Public**
4. 创建仓库

### 第三步：推送到 GitHub

```powershell
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

稍等2-5分钟，你的网站将在以下位置上线：
**https://yourusername.github.io**

---

## 📋 项目内容清单

### 核心文件
- ✅ [index.html](index.html) — 主网页（包含所有内容）
- ✅ [css/style.css](css/style.css) — 完整样式系统（~800行）
- ✅ [js/script.js](js/script.js) — 交互与动画

### 文档
- ✅ [README.md](README.md) — 项目介绍
- ✅ [DEPLOYMENT.md](DEPLOYMENT.md) — 部署指南
- ✅ [STYLE_GUIDE.md](STYLE_GUIDE.md) — 设计系统
- ✅ [QUICK_START.md](QUICK_START.md) — 本文件

### 配置
- ✅ [package.json](package.json) — 项目元数据
- ✅ [.gitignore](.gitignore) — Git 忽略文件
- ✅ [.github/workflows/deploy.yml](.github/workflows/deploy.yml) — 自动部署

---


