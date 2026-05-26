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
| [minimal](./minimal) | Minimal | Obsidian | @kepano 极简黑白灰，Obsidian 市场长期 Top 1 |
| [things](./things) | Things | Obsidian | @colineckert 温暖橙色调 |
| [sanctum](./sanctum) | Sanctum | Obsidian | @jdanielmourao 羊皮纸风，h1 双线分割 |
| [shimmering-focus](./shimmering-focus) | Shimmering Focus | Obsidian | @chrisgrieser 极简专注白 |
| [blue-topaz](./blue-topaz) | Blue Topaz | Obsidian | @PKM-er 蓝水晶配色，含暗色兜底 |
| [lapis](./lapis) | Lapis | Typora | 蓝灰简约学术风 |
| [vue](./vue) | Vue | Typora | Vue.js 官方文档风格，绿色强调 |
| [whitey](./whitey) | Whitey | Typora | 纯白衬线书写风（Georgia） |
| [han](./han) | Han | Typora | 中式古典宣纸+宋体+朱红 |
| [github-light](./github-light) | GitHub Light | GitHub | GitHub 官方文档浅色 |
| [solarized-light](./solarized-light) | Solarized Light | 跨编辑器 | Ethan Schoonover 米黄护眼 |

## 暗色主题

| 目录 | 名称 | 来源 | 描述 |
| --- | --- | --- | --- |
| [anuppuccin](./anuppuccin) | AnuPpuccin | Obsidian | @AnubisNekhet Catppuccin 衍生彩色层级 |
| [border](./border) | Border | Obsidian | @Akifyss 高对比度边框风 |
| [drake](./drake) | Drake | Typora | 深绿暗色阅读风 |
| [nord](./nord) | Nord | 跨编辑器 | Arctic Ice Studio 北欧极地 |
| [dracula](./dracula) | Dracula | 跨编辑器 | Dracula 官方配色，经典紫黑 |
| [catppuccin-mocha](./catppuccin-mocha) | Catppuccin Mocha | 跨编辑器 | 柔和暗紫调 |
| [atom-one-dark](./atom-one-dark) | Atom One Dark | Atom/VSCode | One Dark Pro 经典暗色 |
| [gruvbox-dark](./gruvbox-dark) | Gruvbox Dark | 跨编辑器 | 复古暖色调暗色 |

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

**Typora 主题**

- Lapis、Vue、Whitey、Han、Drake（[Typora 官方主题库](https://theme.typora.io/)）

**跨编辑器经典配色**

- [Catppuccin](https://github.com/catppuccin/catppuccin)
- [Dracula](https://draculatheme.com/)
- [Nord](https://www.nordtheme.com/)
- [One Dark](https://github.com/atom/atom/tree/master/packages/one-dark-ui)
- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Solarized](https://ethanschoonover.com/solarized/)
- [GitHub Primer](https://primer.style/)

感谢以上作者及社区贡献者。如有版权或归属问题，欢迎提 Issue 指正。
