# watch-for-me-demo

中文 | [English](README.en.md)

[Watch for Me](https://github.com/QinMian5/watch-for-me) 的在线示例：用一场 CC BY 授权的英文技术演讲生成的阅读页，包含一份中文笔记和一份中英对照全文，笔记每段都能点回原话。

在线查看：https://qinmian5.github.io/watch-for-me-demo/

## 署名

- 作品：[Agentics Day: MCP + Agents: MCP in 2026: Context is All You Need](https://www.youtube.com/watch?v=k-bfLnR0VGo)
- 作者：David Soria Parra（Anthropic）
- 发布者：CNCF [Cloud Native Computing Foundation]
- 协议：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- 改动：已转写、翻译和整理。本仓库的文字稿、中文翻译、笔记和关键帧截图都由原视频改编而来。

## 文件

| 文件 | 内容 |
| --- | --- |
| `media.html` | 阅读页，单个文件，可离线打开 |
| `index.html` | 跳转到 `media.html` |
| `source_map.json` | 带时间戳的中英对照全文、说话人和关键帧 |
| `notes.json` | 笔记，每段都引用全文里的段落 |
| `source_map.md` | 给 agent 读的全文副本 |
| `assets/frames/` | 幻灯片关键帧 |
