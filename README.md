<div align="center">

# 👋 pxlcrtiv

### AI/ML × Blockchain Engineer
*I build production tooling where machine learning meets smart contracts — and ship a commit every single day.*

[![Profile views](https://komarev.com/ghpvc/?username=pxlcrtiv&label=profile%20views&color=0e75b6&style=flat)](https://github.com/pxlcrtiv)
[![Open to work](https://img.shields.io/badge/Open%20to-SWE%20·%20AI%2FML%20·%20Web3%20roles-00C853?style=flat)](https://github.com/pxlcrtiv)
[![Daily commits](https://img.shields.io/badge/daily%20commits-%E2%9C%85-4caf50?style=flat)](https://github.com/pxlcrtiv?tab=overview)

</div>

---

## 🧭 What I do

- **AI/ML engineering** — zero-shot models at the edge, offline-first ML pipelines,
  agent frameworks, Hugging Face ecosystems (datasets, transformers, Hub CLI).
- **Blockchain engineering** — Solidity + Foundry smart contracts, on-chain
  provenance, audit-ready security tooling, Sepolia deployments, ethers.js/web3.py.
- **Full-stack glue** — Python, TypeScript, React — shipping tools that humans
  actually run.

Everything below is **open source, tested, and committed to daily** — the green
bar is the point.

---

## 🚀 Featured projects

<a href="https://github.com/pxlcrtiv/model-ledger" target="_blank">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=pxlcrtiv&repo=model-ledger&theme=radical&hide_border=true" />
</a>
<a href="https://github.com/pxlcrtiv/slither-chat" target="_blank">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=pxlcrtiv&repo=slither-chat&theme=radical&hide_border=true" />
</a>
<a href="https://github.com/pxlcrtiv/agent-wallet" target="_blank">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=pxlcrtiv&repo=agent-wallet&theme=radical&hide_border=true" />
</a>
<a href="https://github.com/pxlcrtiv/position-guard" target="_blank">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=pxlcrtiv&repo=position-guard&theme=radical&hide_border=true" />
</a>
<a href="https://github.com/pxlcrtiv/agent-lab" target="_blank">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=pxlcrtiv&repo=agent-lab&theme=radical&hide_border=true" />
</a>
<a href="https://github.com/pxlcrtiv/KARYX" target="_blank">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=pxlcrtiv&repo=KARYX&theme=radical&hide_border=true" />
</a>

| Repo | What it is | Stack |
|---|---|---|
| [**model-ledger**](https://github.com/pxlcrtiv/model-ledger) | On-chain provenance for ML models — hash a Hugging Face manifest, register it, let anyone verify it. No trusted third party. | Solidity · Foundry · Python · ethers.js |
| [**slither-chat**](https://github.com/pxlcrtiv/slither-chat) | Smart-contract **audit copilot**: explains every Slither finding in plain English (offline KB, on-device HF zero-shot model, or any LLM), with patches, SVG reports, and a benchmark vs. real audited contracts (recall 0.97). | Python · Slither · Hugging Face · transformers |
| [**chain-chat**](https://github.com/pxlcrtiv/chain-chat) | Ask on-chain history in plain English ("which token moved the most yesterday?") — schema-aware LLM → SQL over a bundled DuckDB/parquet snapshot. Zero keys, offline demo, 65 tests, Daily Green automation. | Python · DuckDB · Streamlit · NL→SQL |
| [**agent-wallet**](https://github.com/pxlcrtiv/agent-wallet) | AI agent for **safe testnet transactions** (built on my own agent-lab): inspects a wallet, checks allowances, dry-runs the tx via eth_call, and explains risk in plain English before anything is signed — Sepolia only, mainnet default-off, 67 offline tests. | Python · agent-lab · web3.py · click |
| [**chain-scout**](https://github.com/pxlcrtiv/chain-scout) | AI **wallet risk scanner**: paste any Ethereum address → plain-English risk report — rug-pulled tokens, dangerous approvals, holder concentration, estimated PnL — transparent weighted score, keyless demo, testnet-first. | Python · Streamlit · web3.py · CoinGecko |
| [**position-guard**](https://github.com/pxlcrtiv/position-guard) | DeFi **health monitor**: watches Aave v3 / Compound v3 positions via The Graph subgraphs + CoinGecko, computes health factors, and pushes LLM-written plain-English alerts ("your ETH collateral is at 1.12 HF…") — Telegram optional, keyless web-preview demo by default. | Python · The Graph · httpx · SQLite |
| [**agent-lab**](https://github.com/pxlcrtiv/agent-lab) | Zero-dependency AI agent framework in pure Python — tool use, persistent memory, retries, guards. | Python |
| [**whale-watch-tg**](https://github.com/pxlcrtiv/whale-watch-tg) | Telegram whale tracker — subscribe to any wallet, instant alerts with LLM summaries ("3,000 ETH to Binance — likely sell pressure"), zero-key demo. | Python · python-telegram-bot · web3.py |
| [**KARYX**](https://github.com/pxlcrtiv/KARYX) | Military-grade edge AI model optimization & deployment suite. | Python · ONNX |
| [**hive**](https://github.com/pxlcrtiv/hive) | Multi-agent harness for production AI. | Python |
| [**mobile-profile-shell**](https://github.com/pxlcrtiv/mobile-profile-shell) | A phone-OS style portfolio — React + Vite + Tailwind + shadcn. | TypeScript · React · Tailwind |

> Newest ships: **model-ledger** (Solidity registry + Foundry tests + Python CLI +
> web viewer, Sepolia-ready), **slither-chat** (56 tests passing, benchmarked
> against a 1,748-contract HF corpus), **agent-wallet** (AI agent for safe
> testnet transactions — agent-lab core, dry-run + plain-English risk notes,
> mainnet default-off, 67 offline tests), and **position-guard** (DeFi health
> monitor — 52 tests, golden health-factor math, keyless demo) — all
> feature-complete, documented, and contribution-ready.

---

## 🧠 AI/ML experience

- **Hugging Face zero-shot classification in production pipelines** — DeBERTa-v3
  vulnerable-class tagger running on-device (CPU, no API key) inside
  [slither-chat](https://github.com/pxlcrtiv/slither-chat).
- **Benchmarking ML pipelines** — precision/recall/F1 scoring against real-world
  ground truth from the HF Hub (recall **0.968** on Slither-audited contracts).
- **Agent frameworks** — tool use, function calling, memory, retries
  ([agent-lab](https://github.com/pxlcrtiv/agent-lab), [hive](https://github.com/pxlcrtiv/hive)).
- **Edge model optimization** ([KARYX](https://github.com/pxlcrtiv/KARYX)).

## ⛓️ Blockchain experience

- **Smart contracts with Foundry** — zero-dependency Solidity 0.8.26, 18/18
  tests incl. fuzzing and golden cross-language hashes ([model-ledger](https://github.com/pxlcrtiv/model-ledger)).
- **AI + Web3 intersection** — content-addressed model provenance on-chain,
  AI-assisted security auditing ([slither-chat](https://github.com/pxlcrtiv/slither-chat)).
- **Contract security** — Slither-based static analysis, patch-diff generation,
  severity triage.
- **Tooling** — web3.py, ethereumjs/ethers.js, Sepolia deploy + Etherscan verify
  scripts, local anvil chains.

---

## 📊 GitHub activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pxlcrtiv&show_icons=true&hide=contribs&theme=radical&hide_border=true&count_private=true" alt="GitHub stats" height="170" />
  <img src="https://streak-stats.demolab.com/?user=pxlcrtiv&theme=radical&hide_border=true" alt="GitHub streak" height="170" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pxlcrtiv&layout=compact&theme=radical&hide_border=true" alt="Top languages" height="150" />
  <br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pxlcrtiv&theme=github-dark&hide_border=true" alt="Contribution graph" />
</div>

---

## 📌 How I work

- **Daily commits, small shippable deltas** — every repo carries a day-by-day
  roadmap; the history bar stays green because the work is real.
- **Tests before claims** — every numeric claim in my READMEs is reproduced by a
  command in the repo (benchmarks, golden fixtures, live demo transcripts).
- **Honest engineering** — no empty commits, no exaggerated badges.

---

## 📬 Let's connect

- 💼 Open to **Software Engineering / AI-ML / Web3 roles** — fully remote or
  EU relocation.
- 📖 Read the code: [github.com/pxlcrtiv](https://github.com/pxlcrtiv)
- ✉️ Best way to reach me: open an issue or GitHub discussion on any repo —
  or star one of the projects above, it genuinely helps.

<div align="center">
  <i>Liked what you see? ⭐ Star a repo. It's the best feedback a solo builder gets.</i>
</div>