# 免费个人作品集网站

这是一个不需要买域名也能使用的静态网站模板。

## 怎么预览

直接双击 `index.html`，或者在浏览器里打开它。

## 网站结构

- `index.html`：首页，包含代表作品卡片。
- `works/`：二级详情页，每个作品一个 HTML 文件。
- `assets/projects/`：放你上传的作品文件，比如 PDF、图片、截图。
- `assets/portfolio-cover.svg`：当前占位封面图。
- `styles.css`：页面样式。

## 怎么替换内容

- 把 `Your Name` 换成你的名字或英文名。
- 把邮箱、微信、个人介绍换成你的真实信息。
- 把 3 个项目卡片换成你的代表作品。
- 把你的 PDF 简历命名为 `resume.pdf`，放到这个文件夹里。
- 如果有作品集 PDF，也可以放进来，并在 `index.html` 里增加下载按钮。

## 怎么上传作品并让卡片打开详情

现在首页的 3 张作品卡片已经分别链接到：

- `works/worldbuilding-narrative.html`：世界观剧情叙事类
- `works/script-video.html`：编导脚本效果类，可以放录屏
- `works/ai-workflow.html`：AI 结合使用类

你可以在 GitHub 里这样更新：

1. 进入仓库。
2. 打开 `assets/projects/`。
3. 上传你的作品文件，比如 `worldbuilding-narrative.pdf`、`script-video.mp4` 或 `ai-workflow.pdf`。
4. 打开对应的详情页，比如 `works/worldbuilding-narrative.html`。
5. 点铅笔图标编辑文字、图片路径和 PDF 链接。
6. 点 `Commit changes`，等 GitHub Pages 自动更新。

如果想新增第 4 个作品：

1. 复制一个 `works/` 里的详情页，改成新文件名。
2. 在 `index.html` 的作品区复制一张卡片。
3. 把卡片链接改成新的详情页路径。
4. 上传对应作品文件到 `assets/projects/`。

## 免费发布方式

你可以把这个文件夹发布到这些免费平台：

- GitHub Pages：会得到类似 `用户名.github.io/项目名` 的免费网址。
- Vercel：会得到类似 `项目名.vercel.app` 的免费网址。
- Netlify：会得到类似 `项目名.netlify.app` 的免费网址。

如果之后买域名，也可以再绑定自己的域名；不买也可以正常投递简历。
