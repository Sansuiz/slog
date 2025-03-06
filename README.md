# 技术日志项目

基于Jekyll构建的静态技术博客，包含以下核心组件：

- `_config.yml` 全局配置文件
- `_layouts/` 页面布局模板
- `_posts/` 技术文章集合
- `assets/css/` 样式资源

## 项目结构
├── _config.yml
├── _layouts/
│   └── default.html
├── _posts/
│   └── 2024-05-20-welcome.md
├── assets/
│   └── css/
│       └── style.css
└── README.md

## 本地运行
```bash
bundle install
bundle exec jekyll serve
```
访问 http://localhost:4000 查看效果