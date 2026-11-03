# Codex 龙娘宠物

两款用于 **Codex 桌面客户端** 的自定义宠物：白龙娘 Dot 版，以及龙娘骑大肥鱼夸张起伏版。

| 白龙娘 Dot 版 | 龙娘骑大肥鱼 |
| --- | --- |
| ![白龙娘 Dot 版](pets/dragon-dot/previews/all-states-large.gif) | ![骑大肥鱼待机](pets/dragon-whale-rider/previews/idle-large.gif) |
| [下载素材包](downloads/white-dragon-dot.zip) | [下载素材包](downloads/dragon-whale-rider.zip) |

## 安装到 Codex

1. 下载并解压对应 ZIP。
2. 打开包内的 `install.html`，点击“在 Codex 中安装”。Windows 也可双击 `Install-Codex-Pet.url`。
3. 在浏览器与 Codex 客户端确认安装，然后到设置中的宠物列表选择该宠物。

需要预先安装并开放宠物功能的 Codex 桌面客户端。**解压不会自动启用宠物**，首次导入需要联网访问 GitHub。安装入口按[官方 OpenAI 安装链接协议](https://learn.chatgpt.com/docs/reference/commands#pets)生成，并明确指定 v2 精灵表格式。

安装后可以通过客户端的宠物设置或 `/pet` 显示宠物；具体入口以当前客户端为准。GIF 和 MP4 仅用于预览。

## 动作与格式

两套精灵表均为透明 PNG，1536 × 2288 像素；每格 192 × 208，8 列 11 行，共 73 个有效帧。

前九行依次为待机、向右移动、向左移动、挥手、跳跃、失败、等待、工作和检查；末两行包含十六个顺时针视线方向。

骑鱼版将白发龙娘与蓝发鲸鱼女仆娘作为相连的骑乘组合。待机保留夸张的压低、撑起，移动时由下方交替用手膝爬跑。待机仍只有六帧，能调整动作衔接，不能达到视频般的高帧率。

## 文件

- `pets/dragon-dot/`：白龙娘 Dot 版。
- `pets/dragon-whale-rider/`：骑大肥鱼夸张起伏版。
- `downloads/`：可直接下载的两套 ZIP。
- `SHA256SUMS`：仓库发布文件的 SHA256 校验值。
- [角色来源与制作说明](CREDITS.md)。

每套目录包含安装入口、精灵表、逐状态 GIF、MP4、视线预览、联系表、关键帧，以及从实际验证报告提取的质量摘要。
