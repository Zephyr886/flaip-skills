# FLAIP agent skills

让 AI Agent 在 [FLAIP](https://flaip.xyz)（BNB Chain）上创建代币和交易。

```bash
npx skills add Zephyr886/flaip-skills
```

安装后对 Agent 说一句话即可，例如“在 FLAIP 创建一个叫 Moon Cat 的代币”或“用 0.1 BNB 买入这个 CA：0x…”。Agent 会一次问清缺少的选择、生成钱包预览，用户确认一次后签名并跟进结果。

- 签名依赖币安 Agentic Wallet 技能：`npx skills add binance/binance-skills-hub --skill binance-agentic-wallet`，并在 Binance App 开启 Developer Mode。
- 创建与内盘买卖需要钱包持有官方 .ai Agent ID。
- 接口说明：https://flaip.xyz/api/agent ；完整指南：https://flaip.xyz/agent-skill.md

本仓库由 AGENT//PAD 项目的 `scripts/build-skill-package.mjs` 生成，请勿手工修改。
