# FLAIP agent skills

让 AI Agent 在 [FLAIP](https://flaip.xyz)（BNB Chain）上创建代币和交易。

```bash
npx skills add Zephyr886/flaip-skills
```

安装后对 Agent 说一句话即可，例如“在 FLAIP 创建一个叫 Moon Cat 的代币，选 QQQB 底池，购买 0.5 BNB 的 QQQB 作为首购”或“用 0.1 BNB 买入这个 CA：0x…”。Agent 会一次问清缺少的选择，完成实时报价或钱包预览后合并确认，并自动跟进结果。BNB 预算兑换报价币后，以本次实际净到账数量完成首购；兑换、必要授权和创建各自预览/确认，已有订单不重复提交。

- 签名依赖币安 Agentic Wallet 技能：`npx skills add binance/binance-skills-hub --skill binance-agentic-wallet`，并在 Binance App 开启 Developer Mode。
- 创建与内盘买卖需要钱包持有官方 .ai Agent ID。
- 接口说明：https://flaip.xyz/api/agent ；完整指南：https://flaip.xyz/agent-skill.md

本仓库由 AGENT//PAD 项目的 `scripts/build-skill-package.mjs` 生成，请勿手工修改。
