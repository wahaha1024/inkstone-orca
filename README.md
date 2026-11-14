# 墨观 Inkstone · Orca 主题

六套中国色配色 —— 三浅三深 —— 由同一份语义色板生成，同时绘制 Orca 的界面与终端。版本 0.5.0。

属于[墨观 Inkstone](https://github.com/wahaha1024/inkstone)项目：同一份色板还生成 VS Code、Ghostty、Kaku、OpenCode、Zed 与 DeepSeek Harness 主题。本目录由 `pnpm build` 生成，请勿手改。

## 六个主题

| 主题 | 明暗 | 气质 |
| --- | --- | --- |
| Inkstone Xuanmo（玄墨） | 暗 | 松烟墨打底，朱砂作批注。深色画布把亮度让给代码，红色只留给需要被看见的地方——适合夜里长时间写代码。 |
| Inkstone Xuanmo Dimmed（玄墨 Dimmed） | 暗 | 同一方墨，把灯调暗一档。画布更沉、墨色不灰，矿物颜料只退半步饱和度——适合光线柔和的房间。 |
| Inkstone Xuanzhi（宣纸） | 浅 | 生宣的暖白底色，松烟写字，青绿设色。纸是暖的、墨是冷的，矿物色在中间过渡；关键字用降彩的鹤顶红，像朱批而不是警告。 |
| Inkstone Xuanzhi Dimmed（宣纸 Dimmed） | 浅 | 陈纸的暖灰，墨色再深一分。像旧书页在下午的光线里：纸不刺眼，颜料褪了半度，但仍认得出每一种颜色。 |
| Inkstone Canghai（沧海） | 暗 | 深海暮色作底，青绿矿物铺开，银朱只做海面上的一点反光。冷色画布安静，但不至于单调。 |
| Inkstone Qingci（青瓷） | 浅 | 月白釉底，青灰题字，雨过天青。像一件汝窑器：颜色都在釉下，不抢字；适合白天和浅色桌面。 |

每个主题都带一份界面主题（界面配色 + 代码高亮）与一份同名终端色板，所以编辑器旁边的终端是同一块墨。

## 安装

在 Orca 插件目录里搜 "Inkstone"（**Settings → Plugins**），或在[目录页](https://orca.dev/plugins/wahaha1024/inkstone-orca)点 **Open in Orca**。装好后在 **Settings → Appearance** 分别选浅色与深色主题：

- **浅色主题** —— Inkstone Xuanzhi、Inkstone Xuanzhi Dimmed、Inkstone Qingci
- **深色主题** —— Inkstone Xuanmo、Inkstone Xuanmo Dimmed、Inkstone Canghai

终端色板单独选：**Settings → Terminal** 里挑同名主题。

也可以按 Git 仓库直接装：**Settings → Plugins → Add plugin → From a Git URL**，填 `https://github.com/wahaha1024/inkstone-orca#v0.5.0`。

## 许可

MIT，与墨观本身一致。

## English

Six Chinese-colour themes for Orca — three light, three dark — that paint the
interface and the terminal from one semantic palette. Install it from the plugin
directory (**Settings → Plugins**, search "Inkstone"), then pick an app theme
under **Settings → Appearance** and the matching palette under
**Settings → Terminal**. Part of [Inkstone](https://github.com/wahaha1024/inkstone);
licensed MIT.
