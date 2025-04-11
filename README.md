# 🚀 JunXue-tech 个人主页项目

![GitHub Pages](https://www.junxue.tech/)

> 纯静态个人主页模板，无需服务器，Fork即可使用

## 📁 项目目录结构
```
.
├── CNAME            # 自定义域名配置
├── _data/           # 数据文件
├── _includes/       # HTML片段组件
├── _layouts/        # 页面布局模板
├── _pages/          # 内容页面
├── _sass/           # SCSS样式文件
├── assets/          # 静态资源
│   └── js/vendor/   # 第三方库（含jQuery）
├── images/          # 图片资源
└── index.html       # 网站首页
```

## 🛠️ 快速使用指南

### 1. Fork本仓库
点击右上角 `Fork` 按钮复制到您的账户

### 2. 重命名仓库
必须重命名为：
```
您的用户名.github.io
```

### 3. 修改内容
主要修改文件：
```bash
index.html      # 修改主页内容
_pages/*.html   # 编辑各子页面
images/         # 替换您的图片
```

### 4. 启用GitHub Pages
1. 进入仓库 Settings → Pages
2. 选择 `main` 分支作为发布源
3. 访问 `https://您的用户名.github.io`

## ⚙️ 核心配置

### 自定义域名
1. 创建/修改 `CNAME` 文件
2. 写入您的域名（如：`example.com`）

### 修改SEO信息
编辑 `index.html` 头部：
```html
<title>您的姓名</title>
<meta name="description" content="个人简介">
```

## 🌈 主题定制
通过修改以下文件自定义样式：
```
_sass/          # SCSS样式变量
assets/css/     # 编译后的CSS
```

## 📦 包含的第三方库
- jQuery (位于 `assets/js/vendor/jquery/`)
- Font Awesome (通过CDN引入)

## ❓ 常见问题
**Q：如何添加新页面？**  
A：在 `_pages/` 新建HTML文件，然后在导航栏添加链接

**Q：修改后未生效？**  
A：GitHub Pages最长需要2分钟构建，可强制刷新（Ctrl+F5）

---

🔄 **最近更新**  
![GitHub last commit]([https://img.shields.io/github/last-commit/JunXue-tech/JunXue-tech.github.io](https://www.junxue.tech/))

⭐ **如果觉得有用，请给个Star！**  
[![Star]](https://www.junxue.tech/)

## 📊 添加访客统计与地图功能

### 添加访客统计功能
您可以通过以下网站生成统计代码，并嵌入主页页面中：
👉 [https://www.free-website-hit-counter.com/](https://www.free-website-hit-counter.com/)

### 添加访客地图显示
注册并使用以下服务，可以在您的页面显示来自世界各地的访客分布地图：
👉 [https://clustrmaps.com/](https://clustrmaps.com/)
