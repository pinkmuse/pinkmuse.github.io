# PinkMuse Blog

基于 [Hexo](https://hexo.io/) + NexT 主题的多人协作知识博客，托管于 [GitHub Pages](https://pages.github.com/)。

## 快速开始(真快速吗)

```bash
git clone https://github.com/pinkmuse/pinkmuse.github.io.git
cd pinkmuse.github.io
npm install
npx hexo server          # 本地预览 http://localhost:4000
```

## 如何贡献文章

### 方式一：网页直接编辑（无需安装任何工具）

1. 打开博客仓库，进入 source/_posts/ 文件夹
2. 点击 Add file -> Create new file
3. 参考文章模板 source/_TEMPLATE.md 填写内容
4. 点击 Commit changes 提交
5. 等待几分钟，CI 自动部署发布

### 方式二：本地 Git 工作流

```bash
npx hexo new "文章标题"   # 在 source/_posts/ 创建新文章
npx hexo server           # 本地预览 http://localhost:4000
git add . && git commit -m "new post" && git push
```

推送后 GitHub Actions 自动构建部署到 https://pinkmuse.github.io。

## 技术栈

- 框架：Hexo 8.x
- 主题：NexT 8.x (Muse)
- 托管：GitHub Pages
- CI/CD：GitHub Actions (actions/deploy-pages)

## 目录结构

```
source/
  _posts/       # 博客文章
  about/        # 关于页面
  tags/         # 标签页面
  categories/   # 分类页面
  _TEMPLATE.md  # 文章模板
themes/next/    # NexT 主题
```
