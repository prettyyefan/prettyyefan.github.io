# 快速开始指南

## 🎯 目标
使用Hugo搭建并部署你的个人学术主页到GitHub Pages。

## ✅ 前提条件
- Git已安装
- Node.js已安装
- 有GitHub账号

## 🚀 快速部署(5步完成)

### 1️⃣ 更新个人信息

编辑 `content/authors/admin/_index.md`:
- 修改姓名、职位、机构
- 更新邮箱和社交媒体链接
- 修改研究兴趣、教育背景、工作经历
- 替换 `content/authors/admin/avatar.png` 为你的头像

### 2️⃣ 更新网站配置

编辑 `config/_default/hugo.yaml`:
```yaml
title: 你的名字的学术主页
baseURL: 'https://<你的GitHub用户名>.github.io/'
```

编辑 `config/_default/params.yaml`:
```yaml
header:
  navbar:
    logo:
      text: '你的名字'
```

### 3️⃣ 在GitHub创建仓库

1. 访问 https://github.com/new
2. 仓库名: `<你的用户名>.github.io` (例如: `yefan.github.io`)
3. 选择 Public
4. 点击 Create repository

### 4️⃣ 推送代码

```bash
# 在academic-site目录下执行
git remote add origin https://github.com/<你的用户名>/<你的用户名>.github.io.git
git branch -M main
git push -u origin main
```

### 5️⃣ 启用GitHub Pages

1. 进入仓库 Settings → Pages
2. Source 选择: **GitHub Actions**
3. 等待1-3分钟,访问 `https://<你的用户名>.github.io`

## 🎨 自定义内容

### 添加论文
```bash
# 复制示例论文文件夹
cp -r content/publications/conference-paper content/publications/my-paper

# 编辑 content/publications/my-paper/index.md
# 添加论文标题、作者、摘要等信息
```

### 添加博客文章
```bash
# 创建新文章
mkdir content/blog/my-post

# 创建 content/blog/my-post/index.md
# 添加文章内容
```

### 添加项目
```bash
# 复制示例项目
cp -r content/projects/pandas content/projects/my-project

# 编辑 content/projects/my-project/index.md
```

## 🔧 本地预览

```bash
# 在项目根目录(github_yefan)执行
.\hugo.exe server -s academic-site

# 浏览器访问 http://localhost:1313
```

## 📝 更新网站

每次修改后:
```bash
git add .
git commit -m "更新描述"
git push
```

GitHub会自动重新部署。

## 🎯 重要文件说明

```
academic-site/
├── config/
│   └── _default/
│       ├── hugo.yaml        # 网站基本配置
│       ├── params.yaml      # 网站参数
│       ├── menus.yaml       # 导航菜单
│       └── languages.yaml   # 语言设置
├── content/
│   ├── _index.md           # 首页内容
│   ├── authors/admin/      # 个人信息
│   ├── publications/       # 论文
│   ├── blog/              # 博客
│   ├── projects/          # 项目
│   └── events/            # 学术活动
├── static/
│   └── uploads/           # 上传文件(如简历PDF)
└── .github/
    └── workflows/
        └── hugo.yml       # 自动部署配置
```

## 💡 提示

1. **删除示例内容**: 删除 `content/` 下不需要的示例文件
2. **上传简历**: 将PDF简历放到 `static/uploads/resume.pdf`
3. **修改主题颜色**: 在 `params.yaml` 中修改 `appearance.color`
4. **添加Google Analytics**: 在 `params.yaml` 中添加跟踪ID

## 🆘 常见问题

**Q: 本地预览正常,但GitHub Pages显示空白?**
A: 检查 `baseURL` 是否正确设置为你的GitHub Pages URL。

**Q: 推送后没有自动部署?**
A: 检查 Settings → Pages 是否选择了 "GitHub Actions"。

**Q: 图片无法显示?**
A: 确保图片路径正确,使用相对路径。

**Q: 如何更改语言?**
A: 修改 `config/_default/hugo.yaml` 中的 `defaultContentLanguage`。

## 📚 更多资源

- [完整部署指南](DEPLOYMENT.md)
- [Hugo文档](https://gohugo.io/documentation/)
- [Hugo Blox文档](https://docs.hugoblox.com/)
- [Markdown语法](https://www.markdownguide.org/)

---

**现在你的学术主页已经准备好了!** 🎉

访问 http://localhost:1313 预览,满意后推送到GitHub即可上线!

