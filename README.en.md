# watch-for-me-demo

[中文](README.md) | English

A live example of [Watch for Me](https://github.com/QinMian5/watch-for-me): a reading page generated from a CC BY English tech talk, with Chinese notes and a bilingual English–Chinese transcript. Every note links back to the passage it came from.

View it online: https://qinmian5.github.io/watch-for-me-demo/

## Attribution

- Work: [Agentics Day: MCP + Agents: MCP in 2026: Context is All You Need](https://www.youtube.com/watch?v=k-bfLnR0VGo)
- Author: David Soria Parra (Anthropic)
- Publisher: CNCF [Cloud Native Computing Foundation]
- License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Changes: transcribed, translated into Chinese, and organized into notes. The transcript, translation, notes, and key frames in this repository are adapted from the original video.

## Files

| File | Contents |
| --- | --- |
| `media.html` | The reading page; a single file that works offline |
| `index.html` | Redirects to `media.html` |
| `source_map.json` | Timestamped bilingual transcript, speakers, and key frames |
| `notes.json` | The notes; each paragraph cites passages in the transcript |
| `source_map.md` | A copy of the transcript for agents to read |
| `assets/frames/` | Slide key frames |
