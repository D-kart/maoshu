# MAOSHU · 猫叔的个人网站

记录做过的项目、正在想的事，以及一些有趣的小作品。

**[访问网站](https://d-kart.github.io/maoshu/)** · [Blog](https://d-kart.github.io/maoshu/blog/) · [Craft](https://d-kart.github.io/maoshu/craft/) · [About](https://d-kart.github.io/maoshu/about/)

## 网站内容

- **Work**：OPCStudio、VibeCoders OS、象量投资工作台、MAOSHU Tradingsearch 等项目。
- **Blog**：关于 AI、Agent 与产品实践的文章。
- **Craft**：作品与视觉收藏。
- **About**：个人介绍与联系方式。
- **可以找我**：一对一服务与交流入口。
- **猫与海边**：点击猫钓起贴纸，也可能发现一个内容入口。

## 这个仓库存什么

这里是网站的 **GitHub Pages 发布仓库**，存放 Next.js 导出的静态页面与资源。源码和稿件在单独的私有仓库维护，因此这里没有用于开发的 `package.json`、`app/` 或 `content/`。

GitHub Pages 当前从 `main` 分支根目录发布，访问前缀为 `/maoshu/`。根目录中的页面、素材和框架文件共同组成可访问的网站。

| 路径 | 用途 |
| --- | --- |
| `index.html` | 首页 |
| `work/<项目>/` | 项目详情页 |
| `blog/` | 文章列表与正文 |
| `craft/`、`about/` | 作品墙、个人介绍 |
| `with-me/` | 服务与交流 |
| `admin/` | 内容管理入口；编辑需要授权登录 |
| `projects/` | 项目截图与信息图，和 `work/` 的页面分开存放 |
| `cat/` | 猫、贴纸和海边场景素材 |
| `consulting/` | 服务介绍图片 |
| `_next/` | 构建生成的 JavaScript、CSS 与字体 |
| `index.txt`、各页面下的 `index.txt` | Next.js 生成的页面数据，用于客户端导航 |
| `404.html`、`404/` | 未找到页面 |
| `robots.txt`、`sitemap.xml` | 搜索引擎访问规则与站点地图 |
| `.nojekyll` | 让 GitHub Pages 直接提供静态文件，保留 `_next/` 等资源 |
| `README.md` | 仓库说明，发布同步时保留 |

页面目录与素材路径对应现有网址；调整结构应在源码中完成并重新构建。不要直接移动生成目录或删除 `index.txt`、`_next/` 来整理文件。

## 如何更新

### 日常内容

站点维护者从 **[内容管理入口](https://d-kart.github.io/maoshu/admin/)** 登录 Pages CMS，可以管理文章、项目、作品墙、个人介绍与主页文案。

1. 编辑内容，设置草稿、已发布或已下架状态。
2. 保存到私有内容仓库。
3. 需要上线时，点击后台的 **发布网站**。
4. 等待构建、同步和 GitHub Pages 部署完成，再检查线上页面。

**保存不等于发布。** 发布按钮处理当前已保存的整站内容；草稿与下架稿不生成公开页面。

### 页面设计与功能

在私有源码仓库同步最新内容后修改、验证，再通过同一发布流程更新本站。直接编辑这里的生成文件，会在后续发布时被重新生成的版本覆盖。

发布流程为：

```text
内容后台 / 源码修改
        ↓
私有源码与稿件仓库
        ↓
测试 → 静态构建 → 同步发布文件
        ↓
本仓库 main → GitHub Pages
```

源码、内部交接、未发布稿件和凭据不属于本仓库的发布内容。

## 域名

当前访问地址为 **https://d-kart.github.io/maoshu/**。后续计划迁移至 `maoshu.work`。

迁移时在源码配置中更新域名与路径，重新构建，并检查页面链接、图片、canonical 和 sitemap；稿件无需重新录入。若同时更换托管服务，还需调整发布目标。

## 内容与素材

仓库公开是为了提供网站访问，不代表文字、插画、截图及其他素材自动获得开源授权。引用或使用时请确认相应权利与来源；联系猫叔可通过网站的 [About](https://d-kart.github.io/maoshu/about/) 页面。
