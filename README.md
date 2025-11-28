# 叶凡的学术主页

这是使用Hugo和Hugo Blox Builder主题构建的个人学术网站。

## 本地预览

1. 确保已安装Hugo Extended版本 (v0.139.4或更高版本)
2. 克隆此仓库(包括子模块):
   ```bash
   git clone --recursive https://github.com/yefan/yefan.github.io.git
   ```
3. 进入项目目录:
   ```bash
   cd yefan.github.io
   ```
4. 启动本地服务器:
   ```bash
   hugo server
   ```
5. 在浏览器中访问 `http://localhost:1313`

## 自定义内容

### 个人信息
编辑 `content/authors/admin/_index.md` 文件来更新你的个人信息、教育背景、工作经历等。

### 发表论文
在 `content/publications/` 目录下添加你的论文。每篇论文一个文件夹。

### 博客文章
在 `content/blog/` 目录下添加博客文章。

### 学术报告
在 `content/events/` 目录下添加你的学术报告和演讲。

### 项目
在 `content/projects/` 目录下添加你的研究项目。

## 部署到GitHub Pages

1. 在GitHub上创建一个名为 `<username>.github.io` 的仓库
2. 将此项目推送到该仓库:
   ```bash
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git add .
   git commit -m "Initial commit"
   git push -u origin main
   ```
3. 在GitHub仓库设置中:
   - 进入 Settings > Pages
   - 在 "Source" 下选择 "GitHub Actions"
4. GitHub Actions会自动构建并部署你的网站
5. 网站将在 `https://<username>.github.io` 上线

## 更新内容

每次修改内容后:
```bash
git add .
git commit -m "更新内容"
git push
```

GitHub Actions会自动重新构建并部署网站。

## 技术栈

- [Hugo](https://gohugo.io/) - 静态网站生成器
- [Hugo Blox Builder](https://hugoblox.com/) - 学术主题
- [GitHub Pages](https://pages.github.com/) - 免费托管
- [GitHub Actions](https://github.com/features/actions) - 自动化部署

## 许可证

本项目基于MIT许可证。
