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

| 目录 | 名称 | 描述 |
| --- | --- | --- |
| [peach-oolong](./peach-oolong) | 蜜桃乌龙 | 暖色调浅色主题，适合长时间阅读 |
| [minimal](./minimal) | Minimal | Obsidian Minimal 移植 - 极简黑白灰 |
| [things](./things) | Things | Obsidian Things 移植 - 温暖橙色调 |
| [github-light](./github-light) | GitHub Light | GitHub 官方文档浅色风格 |
| [solarized-light](./solarized-light) | Solarized Light | Ethan Schoonover Solarized - 米黄护眼 |
| [lapis](./lapis) | Lapis | Typora Lapis - 蓝灰简约学术风 |

## 暗色主题

| 目录 | 名称 | 描述 |
| --- | --- | --- |
| [nord](./nord) | Nord | Arctic Ice Studio Nord - 北欧极地 |
| [dracula](./dracula) | Dracula | Dracula 官方配色 - 经典紫黑 |
| [catppuccin-mocha](./catppuccin-mocha) | Catppuccin Mocha | 柔和暗紫调 |
| [atom-one-dark](./atom-one-dark) | Atom One Dark | Atom/VSCode One Dark Pro |
| [gruvbox-dark](./gruvbox-dark) | Gruvbox Dark | 复古暖色调暗色 |

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

- Obsidian [Minimal](https://github.com/kepano/obsidian-minimal) / [Things](https://github.com/colineckert/obsidian-things)
- Typora [Lapis](https://github.com/peaceandme/typora-lapis-theme)
- [Catppuccin](https://github.com/catppuccin/catppuccin)
- [Dracula](https://draculatheme.com/)
- [Nord](https://www.nordtheme.com/)
- [One Dark](https://github.com/atom/atom/tree/master/packages/one-dark-ui)
- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Solarized](https://ethanschoonover.com/solarized/)
- [GitHub Primer](https://primer.style/)

感谢以上作者及社区贡献者。如有版权或归属问题，欢迎提 Issue 指正。
