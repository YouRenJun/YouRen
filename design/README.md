# YouRen · 黄昏工作间

这套文件用于 `YouRen1320/YouRen1320` 的 GitHub Profile。主题是「写工具，也写故事。」

## 放入仓库

把压缩包内 `YouRen1320` 文件夹中的 `README.md`、`assets/` 和 `design/` 合并到你现有仓库的根目录，然后正常 commit、push。不要在仓库中再套一层 `YouRen1320` 文件夹。

这是内容文件包，没有 `.git` 目录；不会改变你的远程地址、分支和提交历史。README 已经启用图片，无需替换占位符或安装依赖。

旧的 `assets/logo.png` 已不再被新版 README 引用，是否保留由你决定。

## 文件用途

| 文件 | 用途 |
| --- | --- |
| `../README.md` | GitHub Profile 正文，包含可点击的项目与联系入口 |
| `../assets/youren-banner-light.webp` | 浅色主题的页面展示图 |
| `../assets/youren-banner-dark.webp` | 深色主题的页面展示图 |
| `../assets/youren-banner-light.png` | 浅色完整 PNG 与格式回退 |
| `../assets/youren-banner-dark.png` | 深色完整 PNG 与格式回退 |
| `illustration-light.png` | 无身份文字的浅色插画底图 |
| `illustration-dark.png` | 同一构图的深色插画底图 |
| `banner-light.svg` | 浅色版排版源文件 |
| `banner-dark.svg` | 深色版排版源文件 |
| `prompts.md` | 实际使用的生成与编辑提示词 |

## 图片与主题

两张插画使用内置 imagegen 制作；深色版以浅色版为编辑目标，保持人物、窗形和桌面构图。

原始插画均为 **2172 × 724**。最终将插画与矢量字标统一排版为 **2400 × 800（3:1）**；名字与副标题独立以矢量排版。

PNG 保留完整排版导出；WebP 使用质量 94 的展示压缩，浅色约 270 KiB、深色约 240 KiB。README 优先加载对应主题的 WebP，并保留 PNG 回退路径。

GitHub 使用 `<picture>` 和 `prefers-color-scheme` 选择主题图片。源文件、文件名和目录已保持匹配，不需要额外工作流或远程图片服务。

## 编辑源文件

两个 SVG 分别链接同目录的 `illustration-light.png` 和 `illustration-dark.png`。编辑时保持这些文件在同一个目录，使用支持链接图片的 SVG 编辑器打开。

SVG 将插画、名字、副标题和短线分成独立分组。文字已转为矢量路径，显示时不依赖系统字体；可以修改颜色、大小与位置。若要改变文字内容，需要重新排字并转曲。

字标使用 URW Bookman Light 的字形，副标题使用 DejaVu Sans Mono 的字形，均未附带字体文件。

固定文案：

- `YouRen`
- `TOOLS, AGENTS & STORIES`
- 正文短句：`写工具，也写故事。`

主色：骨白 `#F3EBDD`、墨灰 `#282B2A`、苔绿 `#707A60`、琥珀 `#CB9458`、赭色 `#A56449`。

## 本次核对

- 检查成品为 2400 × 800，原始插画为 3:1，图片文件可以正常解码。
- 已查看完整排版；最终页面效果由你自行预览。
- 检查 README 中全部相对图片路径、SVG 底图路径与文件大小写。
- README 使用普通 Markdown 与 picture/source/img，没有脚本、自定义 CSS 或缺失的占位资源。
- 项目与联系信息沿用本次已读取的公开仓库资料；没有新增版本、在线率或熟练度承诺。

本次没有在 GitHub 上发布。上传后可自行切换浅色与深色主题预览。

参考：[GitHub 官方主题图片说明](https://github.blog/developer-skills/github/how-to-make-your-images-in-markdown-on-github-adjust-for-dark-mode-and-light-mode/)。
