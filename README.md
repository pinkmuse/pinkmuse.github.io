# PinkMuse Blog

基于 [Hexo](https://hexo.io/) + NexT 主题的个人博客，托管于 GitHub Pages。

## 协作方式

### 方式一：Git PR 工作流（推荐开发者）

```bash
git clone https://github.com/pinkmuse/pinkmuse.github.io.git
cd pinkmuse.github.io
npm install
hexo new "文章标题"  # 创建新文章
hexo server          # 本地预览 http://localhost:4000
```

写完后提交 PR，管理员审核合并后自动部署。

### 方式二：Decap CMS 网页编辑器（推荐非技术人员）

访问 `https://pinkmuse.github.io/admin/` 使用网页编辑器在线写作。

需要 GitHub OAuth 认证（首次需管理员配置）。

## 技术栈

- **框架**：Hexo 7.x
- **主题**：NexT (Pisces)
- **托管**：GitHub Pages
- **CI/CD**：GitHub Actions
- **CMS**：Decap CMS

## 分支保护

`main` 分支已开启保护，所有变更必须通过 Pull Request 审核。
