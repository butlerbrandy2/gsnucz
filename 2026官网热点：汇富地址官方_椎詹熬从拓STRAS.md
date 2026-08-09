汇富地址官方【Q-——333307——】汇富地址官方【 辋芷《888yx●vip》 】
汇富地址官方【Q-——333307——】汇富地址官方【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是否也想拥有一个完全属于自己的技术博客？不用买服务器、不用备案，甚至完全免费——通过 GitHub Pages 和 Hexo 就能轻松实现。本文将手把手带你完成从环境配置到部署上线的全流程。

 为什么要用 Hexo + GitHub Pages

- 免费托管：GitHub Pages 提供无限流量静态托管
- 极速访问：支持绑定自定义域名，国内访问速度尚可
- Markdown 写作：专注内容，不用纠结排版
- 主题丰富：数百款免费主题随意切换

 第一步：环境准备

在开始之前，请确保本机已安装：
1. Git（版本不低于 2.0）
2. Node.js（建议 16.x LTS 版本）

打开终端输入以下命令验证：

```bash
git --version && node -v
```

 第二步：安装 Hexo 并初始化项目

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面说明本地环境搭建成功。

 第三步：部署到 GitHub Pages

1. 在 GitHub 创建仓库，命名为 `你的用户名.github.io`
2. 修改站点 `_config.yml` 配置文件：

```yaml
deploy:
  type: git
  repo: https://github.com/用户名/用户名.github.io.git
  branch: main
```

3. 执行部署命令：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

稍等片刻，访问 `https://用户名.github.io` 即可看到你的博客。

 进阶优化建议

- 绑定自定义域名：在仓库 Settings → Pages 中填写你的域名
- 接入评论系统：推荐使用 Giscus（基于 GitHub Discussions）
- SEO 优化：安装 `hexo-generator-seo-friendly-sitemap` 插件

---

互动时间：你的博客主要打算写哪类内容？前端技术、后端架构还是生活随笔？欢迎在评论区分享。如果部署过程中遇到任何问题，可以把报错信息贴出来，我看到后会逐一回复解答。

点击收藏方便日后查看，转发给同样想建博客的朋友——让知识流动起来。关注我，后续会更新更多关于自动化部署和性能优化的实用技巧。

相关推荐：

https://github.com/thomasjennifer67/zbmuql/blob/main/2026%E5%AE%98%E7%BD%91%E6%8C%87%E5%8D%97%EF%BC%9A%E6%B1%87%E5%AF%8C%E5%A8%B1%E4%B9%90%E5%9C%B0%E5%9D%80_%E5%8B%A4%E5%B8%90%E4%BA%A2%E7%9A%87%E9%85%92RYZAJ.md

<img src="https://i.postimg.cc/kgg1LMbB/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo.png" />

相关推荐：

https://github.com/thomasjennifer67/zbmuql/commit/4ab730c3465f5f0a5a3c42292282aede21b1eb01

<img src="https://i.postimg.cc/kgg1LMbB/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo.png" />
相关推荐：

https://github.com/juarezlauren79/zfgnhl/blob/main/%E7%95%85%E6%B8%B8%E6%96%87%E6%B5%B7%E9%80%90%E6%A2%A6%EF%BC%9A%E6%B1%87%E5%AF%8C%E5%A8%B1%E4%B9%90%E6%B5%8B%E9%80%9F_%E4%B9%87%E8%85%8B%E6%A4%92%E9%93%B0%E9%AA%8BGUBBC.md

<img src="https://i.postimg.cc/G3v5y5R4/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(93).png" />
相关推荐：

https://github.com/juarezlauren79/zfgnhl/commit/3ee95d1c3efdbffef08d77ac5adb0a727a6c728b

<img src="https://i.postimg.cc/g2g50LWJ/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(89).png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
