# Flaip agent skills

English and Chinese guidance for launching, trading and claiming on [Flaip](https://flaip.xyz), BNB Chain. The Agent follows the user's language and preserves the same preview and confirmation rules.

```bash
npx skills add Zephyr886/flaip-skills
```

## English

After installation, try “Create a token named Moon Cat, use QQQB, and buy 0.5 BNB worth of QQQB for its initial purchase”, “Buy this CA with 0.1 BNB”, or “Claim tokens {CA} to {wallet}”. The Agent asks once for missing creation choices and does not make you convert the funding budget into quote-token units. A different claim destination requires a claim followed by a transfer, each previewed and confirmed separately.

- [English quick start](skills/flaip-launchpad/references/quickstart.en.md)
- [Full English API reference](skills/flaip-launchpad/references/full-guide.md)
- Website: https://flaip.xyz/?lang=en · Online guide: https://flaip.xyz/agent-quickstart.en.md

## 中文

安装后直接告诉 Agent：“在 Flaip 创建 Moon Cat，选 QQQB 底池，购买 0.5 BNB 的 QQQB 作为首购”“用 0.1 BNB 买入这个 CA”或“领取代币 {CA} 到 {收款钱包}”。Agent 一次问清缺失选择，自动报价、预览并跟进；指定另一收款钱包时先领取、再转出，各自确认。

- [中文快速指南](skills/flaip-launchpad/references/quickstart.zh-CN.md)
- 官网：https://flaip.xyz/?lang=zh · 在线指南：https://flaip.xyz/agent-quickstart.md

Both languages require the official Binance Agentic Wallet skill and Developer Mode for contract calls. Creation and curve trading require official .ai Agent ID. 安装语言版本不改变钱包、链、合约或授权规则。

Generated from the Flaip project's deploy guides by `scripts/build-skill-package.mjs`; edit those source guides rather than generated files.
