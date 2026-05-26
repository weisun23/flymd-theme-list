# flyMD 主题列表

本仓库收录适配 [flyMD](https://github.com/weisun23/flymd) 编辑器（flymd-theme-plugin）的常用主题，覆盖 Obsidian、Typora、VSCode 等社区热门主题的移植版，涵盖浅色与暗色两类风格，便于在阅读、写作与编码笔记之间随心切换。

## 安装方法

方式一：在 flyMD 中直接安装

1. 打开 flyMD，点击顶栏 **主题 → 来自 GitHub...**
2. 在输入框中填写 `weisun23/flymd-theme-list/<主题目录>`，例如 `weisun23/flymd-theme-list/gruvbox-dark`
3. 安装完成后，在主题菜单中即可切换

方式二：手动安装

1. 下载本仓库对应子目录（含 `theme.json` 与 `style.css`）
2. 将整个目录放入 flyMD 的主题目录
3. 重启 flyMD 后在主题菜单中选择该主题

## 浅色主题

| 目录 | 名称 | 来源 | 描述 |
| --- | --- | --- | --- |
| [peach-oolong](./peach-oolong) | 蜜桃乌龙 | 原创 | 暖色调浅色，适合长时间阅读 |
| [minimal](./minimal) | Minimal | Obsidian | @kepano 极简黑白灰 |
| [things](./things) | Things | Obsidian | @colineckert 温暖橙色调 |
| [sanctum](./sanctum) | Sanctum | Obsidian | @jdanielmourao 羊皮纸风 |
| [shimmering-focus](./shimmering-focus) | Shimmering Focus | Obsidian | @chrisgrieser 极简专注白 |
| [blue-topaz](./blue-topaz) | Blue Topaz | Obsidian | @PKM-er 蓝水晶配色，含暗色兜底 |
| [primary](./primary) | Primary | Obsidian | @CeciliaMay 纯净奶油亮色 |
| [california-coast](./california-coast) | California Coast | Obsidian | @mgmeyers 加州海岸暖蓝 |
| [lyt-mode](./lyt-mode) | LYT Mode | Obsidian | @nickmilo 笔记法专用米白 |
| [cupertino](./cupertino) | Cupertino | Obsidian | macOS Big Sur 风 |
| [its-theme](./its-theme) | ITS Theme | Obsidian | @SlRvb 多色调可切换基调 |
| [lapis](./lapis) | Lapis | Typora | 蓝灰简约学术风 |
| [vue](./vue) | Vue | Typora | Vue.js 官方文档风格 |
| [whitey](./whitey) | Whitey | Typora | 纯白衬线书写风（Georgia） |
| [han](./han) | Han | Typora | 中式古典宣纸+宋体+朱红 |
| [typora-github](./typora-github) | Typora GitHub | Typora | Typora 自带 GitHub 主题 |
| [newsprint](./newsprint) | Newsprint | Typora | 报纸版式衬线（Times） |
| [pixyll](./pixyll) | Pixyll | Typora | 轻盈白衬线极简（Lora） |
| [academic](./academic) | Academic | Typora | 学术论文 LaTeX 风（Computer Modern） |
| [github-light](./github-light) | GitHub Light | GitHub | GitHub 官方文档浅色 |
| [solarized-light](./solarized-light) | Solarized Light | 跨编辑器 | Ethan Schoonover 米黄护眼 |
| [ayu-light](./ayu-light) | Ayu Light | 跨编辑器 | Ayu 暖橙浅色 |

## 暗色主题

| 目录 | 名称 | 来源 | 描述 |
| --- | --- | --- | --- |
| [anuppuccin](./anuppuccin) | AnuPpuccin | Obsidian | @AnubisNekhet Catppuccin 衍生彩色层级 |
| [border](./border) | Border | Obsidian | @Akifyss 高对比度边框风 |
| [royal-velvet](./royal-velvet) | Royal Velvet | Obsidian | 紫色丝绒奢华暗色 |
| [cybertron-flow](./cybertron-flow) | Cybertron Flow | Obsidian | 赛博霓虹（标题带光晕） |
| [drake](./drake) | Drake | Typora | 深绿暗色阅读风 |
| [tokyo-night](./tokyo-night) | Tokyo Night | 跨编辑器 | 深紫蓝东京夜景 |
| [rose-pine](./rose-pine) | Rosé Pine | 跨编辑器 | 柔和粉紫调 |
| [kanagawa](./kanagawa) | Kanagawa | 跨编辑器 | 日式浮世绘暗色 |
| [everforest-dark](./everforest-dark) | Everforest Dark | 跨编辑器 | 森林绿护眼暗色 |
| [nord](./nord) | Nord | 跨编辑器 | Arctic Ice Studio 北欧极地 |
| [dracula](./dracula) | Dracula | 跨编辑器 | Dracula 官方配色 |
| [catppuccin-mocha](./catppuccin-mocha) | Catppuccin Mocha | 跨编辑器 | 柔和暗紫调 |
| [solarized-dark](./solarized-dark) | Solarized Dark | 跨编辑器 | Solarized 经典暗色 |
| [github-dark](./github-dark) | GitHub Dark | GitHub | GitHub 官方文档暗色 |
| [atom-one-dark](./atom-one-dark) | Atom One Dark | Atom/VSCode | One Dark Pro 经典暗色 |
| [gruvbox-dark](./gruvbox-dark) | Gruvbox Dark | 跨编辑器 | 复古暖色调暗色 |
| [monokai-pro](./monokai-pro) | Monokai Pro | 跨编辑器 | Monokai Pro 经典编辑器配色 |
| [ayu-mirage](./ayu-mirage) | Ayu Mirage | 跨编辑器 | Ayu 介于明暗之间 |
| [ayu-dark](./ayu-dark) | Ayu Dark | 跨编辑器 | Ayu 深色暖橙 |

## 主题包结构

每个主题目录均包含以下两个核心文件：

```
<theme-id>/
├── theme.json   # 主题元数据：id / name / author / description / version / entry
└── style.css    # 主题样式，作用域限定在 .container 内的预览与编辑视图
```

- `theme.json` 字段说明：
  - `id`：主题唯一标识，需与目录名一致
  - `name`：在主题菜单中显示的名称
  - `version`：版本号
  - `author`：主题作者
  - `description`：简短描述
  - `main`：样式入口文件（通常为 `style.css`）
- `style.css` 通过覆盖 `.container` 上的 CSS 变量以及 `.container .preview` 与 `.container.wysiwyg-v2 .ProseMirror` 两套选择器，保证预览与所见即所得编辑视图的视觉一致。

## 致谢

本仓库的多数主题为社区流行配色的 flyMD 适配版，灵感与配色来自以下优秀开源项目：

**Obsidian 主题**

- [Minimal](https://github.com/kepano/obsidian-minimal)（@kepano）
- [Things](https://github.com/colineckert/obsidian-things)（@colineckert）
- [Sanctum](https://github.com/jdanielmourao/obsidian-sanctum)（@jdanielmourao）
- [Shimmering Focus](https://github.com/chrisgrieser/shimmering-focus)（@chrisgrieser）
- [Blue Topaz](https://github.com/PKM-er/Blue-Topaz_Obsidian-css)（@PKM-er）
- [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin)（@AnubisNekhet）
- [Border](https://github.com/Akifyss/obsidian-border)（@Akifyss）
- [Primary](https://github.com/CeciliaMay/Primary-Obsidian)（@CeciliaMay）
- [California Coast](https://github.com/mgmeyers/obsidian-california-coast-theme)（@mgmeyers）
- [LYT Mode](https://github.com/nickmilo/LYT-Mode)（@nickmilo）
- [Cupertino](https://github.com/jdmaher/cupertino)
- [ITS Theme](https://github.com/SlRvb/Obsidian--ITS-Theme)（@SlRvb）
- [Royal Velvet](https://github.com/caro401/royal-velvet)
- [Cybertron Flow](https://github.com/420World69/Cybertron-Flow)

**Typora 主题**

- Lapis、Vue、Whitey、Han、Drake、Newsprint、Pixyll、Academic、GitHub（[Typora 官方主题库](https://theme.typora.io/)）

**跨编辑器经典配色**

- [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme)
- [Rosé Pine](https://github.com/rose-pine/rose-pine-theme)
- [Catppuccin](https://github.com/catppuccin/catppuccin)
- [Dracula](https://draculatheme.com/)
- [Nord](https://www.nordtheme.com/)
- [Kanagawa](https://github.com/rebelot/kanagawa.nvim)
- [Everforest](https://github.com/sainnhe/everforest)
- [One Dark](https://github.com/atom/atom/tree/master/packages/one-dark-ui)
- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Solarized](https://ethanschoonover.com/solarized/)
- [Monokai Pro](https://monokai.pro/)
- [Ayu](https://github.com/ayu-theme/ayu-colors)
- [GitHub Primer](https://primer.style/)

感谢以上作者及社区贡献者。如有版权或归属问题，欢迎提 Issue 指正。
