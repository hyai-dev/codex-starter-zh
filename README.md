# Codex 中文起步示例（config + AGENTS.md）

最小可复制示例：占位 `config.toml`、项目级 `AGENTS.md` 模板，以及安装 → 登录 → 验收顺序。  
**不含真实 API Key。** 命令与配置路径随 Codex CLI 版本变化，以官方文档为准。

## 安装 → 登录 → 验收

1. **安装**（示例，以官方当前文档为准）  
   `npm install -g @openai/codex`  
   然后执行 `codex --version` 确认命令可用。
2. **登录**  
   - ChatGPT 账号路径：按客户端提示完成浏览器授权；可用 `codex login status` 只读查看状态。  
   - API Key 路径：走 API 项目账单，与 ChatGPT 套餐额度不是同一笔账。  
   不要把 Key、`auth.json` 或 Session 发给任何代充网站或陌生人。
3. **验收**  
   - 在空目录或本仓库跑一个只读小任务。  
   - 若出现 `401` / `429` / 超时，先按报错正文分流，不要重复付款试错。

## 两个独立站点的公开文档（按需自选）

以下是两个**彼此独立**的公开站点文档入口，按你的问题自选；本文不暗示它们同属一方运营。

| 你需要 | 打开 |
|---|---|
| 套餐 / 代充交易说明（Plus、5x、20x） | [PayForGPT · Codex](https://payforgpt.com/codex) |
| 配置、401/429/超时分流 | [Nano Banana · 分流表](https://nano-banana.lol/how-to/codex-401-429-timeout-triage) |
| Codex 配置与购买总览（Nano） | [Nano Banana · Codex](https://nano-banana.lol/codex) |

## 文件说明

| 文件 | 用途 |
|---|---|
| `config.toml` | 最小占位配置；复制前先对照你的 CLI 版本 |
| `AGENTS.md` | 项目级指令模板；可按仓库改写 |
| `README.md` | 本说明 |

## License

MIT — 示例文本可自由修改；第三方商标归各自权利人。
