# 工业 AI 科普动画

## 剪报拼贴动画技能（1.1.0）

[下载 opus5.5 cut-out animation v1.1.zip](https://raw.githubusercontent.com/yydy5079-del/-/main/opus5.5%20cut-out%20animation%20v1.1.zip)

输入口播文案和MP3，调用 `$opus55-cut-out-animation`，从对齐、分镜、无字剪贴资产与分层、代码动画到混音和1080p30/H.264渲染。

本版已实际读取用户480p参考，按雕版/照片剪贴和编辑式报刊版面校准。新增撕纸/平直揭示、细纸边合成、Bezier弧线摄影机、正式项目关键词对齐与素材尺寸门禁。循环模式检查实际H.264首末帧和起止相机状态；音频循环单独判断。

第0帧只有纸底，重要元素先入场再进行有语义的二次动作。渲染与声音共用事件表，检查真实二次动作像素变化、接触音、因果顺序与主音效低约8dB。主字Noto Sans SC、辅助字Alibaba PuHuiTi Regular。支持多方向局部摄影机和按要求启用的视觉循环。

[技能源码与安装说明](https://github.com/yydy5079-del/html-code-animation/tree/main/.agents/skills/opus55-cut-out-animation) · [压缩包校验信息](cut-out-animation-package.json)

ZIP只包含源码、文档和字体清单，不含原声、媒体、字体二进制、凭据或依赖。标准仓库Skill安装已验证；跨Agent按宿主支持的Skill导入方式安装。技术用例不等于完整参考影片或未来文案成片已通过艺术与听觉验收。

## 可复用动画技能（1.0.0）

[下载 Opus5.5×Camera Motion Whiteboard Animation.zip](https://raw.githubusercontent.com/yydy5079-del/-/main/Opus5.5%C3%97Camera%20Motion%20Whiteboard%20Animation.zip)

工程简报板风格的标准 Agent Skill，已安装在原代码仓库的 `.agents/skills/opus55-camera-motion-whiteboard-animation`。新任务上传口播 MP3 和文案，调用 `$opus55-camera-motion-whiteboard-animation`，默认从分镜持续制作到成片。

固定 1080p30/H.264、2D/2.5D 局部运镜、无字幕、原声同步、音效低约 8 dB；Noto Sans SC 主字，Alibaba PuHuiTi Regular 辅助字。禁止辅助字随机变形，禁止结尾全板回顾。

[查看修复后的辅助字体测试](camera-motion-whiteboard-font-check.jpg) · [技能源码与安装说明](https://github.com/yydy5079-del/html-code-animation/tree/main/.agents/skills/opus55-camera-motion-whiteboard-animation) · [压缩包校验信息](camera-motion-whiteboard-package.json)

ZIP 仅含源码和文档，不包含原声、视频、字体、模型或凭据。字体由设置工具下载并校验。本安装范围是指定仓库，不是账号插件商店；其他电脑可用包内安装器安装到自己的仓库。

## 工程简报板版（最新）

[直接下载 MP4](https://raw.githubusercontent.com/yydy5079-del/-/main/industrial-ai-briefing-board.mp4)

48.7667 秒，1920×1080 / 原生 30 fps / H.264 + AAC。使用加长版原始口播；一面连续简报板承载人物协同、工业压力、资本交易、软件与数据布局、国内政策、2027 年目标和生产成果追问。没有烧录字幕、交互 UI 或黑场转场。

[查看分镜预览](industrial-ai-briefing-board-preview.jpg) · [查看全板封面](industrial-ai-briefing-board-poster.jpg) · [源码、构建说明与素材授权](https://github.com/yydy5079-del/html-code-animation/tree/main/industrial-ai/briefing-board)

人物与设备为原创模型渲染剪贴，工艺区注明结构示意。字体沿用参考片的 Noto Sans SC 700/900 与霞鹜漫黑。交易按用户补充的“已签协议、待审批交割”状态呈现；四项政策数量作为 2027 年目标展示。

技术检查：1463 帧、完整解码通过、−14.11 LUFS、−1.5 dBTP；主要音效在有人声的效果窗口内平均低于口播约 8.1 dB。校验信息见 [交付清单](industrial-ai-briefing-board-manifest.json)。原代码仓库不存放成片、音频、图片或字体大文件。

## 逐句语义动画版（历史版本）

[直接下载新版 MP4](https://raw.githubusercontent.com/yydy5079-del/-/main/industrial-ai-semantic.mp4)

1920×1080 / 30 fps / H.264 + AAC / 23.433 秒。使用新上传的纯口播，17 个语义画面，独立表达人物协同、四项生产压力、控制闭环与资本布局。无字幕、无交互 UI、无黑场。交易画面按用户补充的已签协议、待审批交割状态表达。

[查看分镜预览图](industrial-ai-semantic-preview.jpg) · [动画源码与构建说明](https://github.com/yydy5079-del/html-code-animation/tree/main/industrial-ai/semantic-hologram)

技术检查：703 帧、完整解码通过、−14.14 LUFS、−1.5 dBTP；音效在有人声的效果窗口内平均低于口播约 8 dB。

## 写实工业版（历史版本）

[直接下载 industrial-ai-realistic.mp4](https://raw.githubusercontent.com/yydy5079-del/-/main/industrial-ai-realistic.mp4)

1920 × 1080、30 fps、H.264 / AAC，14.50 秒。含用户原始口播与原创程序音效，无字幕或界面面板。人物协同、实体流程设备、四项生产压力与控制反馈沿同一工厂场景展开。

[查看封面静帧](industrial-ai-realistic-poster.jpg)

[动画源码、可复现构建脚本与素材来源](https://github.com/yydy5079-del/html-code-animation/tree/main/industrial-ai/realistic)保存在原代码仓库；该代码仓库不存放视频、音频、字体或模型大文件。

## 早期版本

- [Neon-Cyberpunk 版](https://raw.githubusercontent.com/yydy5079-del/-/main/industrial-ai-neon.mp4)
- [初版](https://raw.githubusercontent.com/yydy5079-del/-/main/industrial-ai.mp4)
