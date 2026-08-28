> I build things that probably shouldn't exist yet — **privacy-first**, **on-chain**, and quietly opinionated.
> **Rust** for the parts that can't fail. **Solana** for the parts that move fast. **AI** for the parts no one else wants to think about.
> Ships real products. Reads the mempool for fun. Believes the best systems are the ones users never have to think about.

<h1 align="center">🛠️ Proof of Work</h1>


### 🪐 Solana × Real-time Intelligence

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Khaata** | Non-custodial USDC point-of-sale & merchant ledger on Solana — UPI-grade checkout, ~1.4s settlement straight to the merchant's own wallet, every receipt verifiable on-chain | Next.js 16 · Rust · Anchor · Drizzle · Postgres · Tailwind | [Live](https://khaata-orcin.vercel.app) |
| **WatchTower** | Private Telegram-controlled Solana monitoring daemon — polls token prices & wallet balances, evaluates alert rules with edge-triggered notifications, all from a single Rust binary backed by SQLite | Rust · SQLite · Telegram Bot API · Solana RPC | [Repo](https://github.com/0xuser64bit/WatchTower) |
| **Praxis** | Conversational Solana agent — plain-language intent ("send 0.5 SOL to maya") becomes a simulated on-chain action, while the Aegis program enforces spend caps, allow-lists & expiry on-chain before value moves | Next.js · Rust · Anchor · Gemini · TS | [Live](https://usepraxis.fun) · [Repo](https://github.com/0xuser64bit/Praxis) |
| **RugPulse** | Real-time Solana new-token intel — pulls fresh launches, enriches with security/holder/OHLCV data, scores deterministically, surfaces a trader-readable verdict | Next.js · TS · Birdeye · Tailwind | [Live](https://rugpulse.user64bit.wtf) · [Repo](https://github.com/0xuser64bit/RugPulse) |
| **GetToasted** | Scans any Solana wallet for sandwich attacks and quantifies MEV loss in USD — Helius webhooks + BullMQ workers + Jupiter pricing | Next.js · TS · Helius · BullMQ · Jupiter | [Live](https://gettoasted.fun) · [Repo](https://github.com/0xuser64bit/GetToasted) |
| **GhostTip** | Privacy-first social tipping — tip any X handle, X-OAuth gated claim, auto-refund if unclaimed | Next.js · Solana · Prisma · Loyal Network | [Live](https://ghost-tip.vercel.app) · [Repo](https://github.com/0xuser64bit/Ghost-Tip) |
| **Receba Guard** | Self-hosted USDC receivables verification for Brazilian merchants — WhatsApp-native agent creates Solana Pay invoices, a local Rust verifier deterministically confirms on-chain settlement; no private keys, no custody | Rust · Solana · WhatsApp · Solana Pay | [Live](https://receba-guard.vercel.app/) · [Repo](https://github.com/0xuser64bit/receba-guard) |
| **Tipmark** | Non-custodial creator support page on Solana — claim a handle, share a link, supporters send SOL directly to the creator's wallet with no platform cut; profiles stored on Arweave, every tip verifiable on-chain | Next.js 15 · Rust · Anchor · Arweave · Solana · TS | [Live](https://tipmark-platform.vercel.app) · [Repo](https://github.com/0xuser64bit/Tipmark) |
| **PollChain** | Fully on-chain decentralized voting system on Solana | Rust · Anchor · Solana · Next.js · TS | [Live](https://poll-chain.vercel.app/) · [Repo](https://github.com/0xuser64bit/poll-chain) |

---

### 🤖 AI Agents, MCP & RAG

| Project | What it does | Stack | Links |
|---|---|---|---|
| **DevDNA** | Cinematic GitHub profile analyzer — generates an animated developer identity report | Next.js · TS · Tailwind · framer-motion | [Live](https://dev-dna-theta.vercel.app) · [Repo](https://github.com/0xuser64bit/dev-dna) |
| **DD-Agent** | AI health agent inspired by Bryan Johnson's *Don't Die* blueprint — chat + structured longevity plans | Next.js · OpenAI · TS · Tailwind | [Live](https://dd-agent-ruby.vercel.app) · [Repo](https://github.com/0xuser64bit/dd-agent) |
| **Ask Genie** | Privacy-first Chrome extension (MV3) — summon a genie lamp on any page to chat with AI grounded in what you're reading; bring your own key, no backend | Vite · React · TS · OpenAI · Anthropic | [Repo](https://github.com/0xuser64bit/ask-genie) |
| **Legal Sahayak** | MCP server for Indian legal assistance — Puch AI / Claude compatible | Python · MCP · FastAPI | [Repo](https://github.com/0xuser64bit/legal-sahayak-mcp) |
| **RAG-PDF** | Django API to upload PDFs and ask cited questions over their contents | Django · ChromaDB · OpenAI | [Repo](https://github.com/0xuser64bit/rag-pdf) |

---

### 🧰 Developer Tools & Experiments

| Project | What it does | Stack | Links |
|---|---|---|---|
| **TweetFolio** | Twitter/X-styled portfolio site — share work as a feed | Next.js · TS · Tailwind | [Live](https://user64bit.wtf) · [Repo](https://github.com/0xuser64bit/The-Tweetfolio) |
| **Get Git** | GitHub activity explorer with a fancy, interactive UI | Next.js · GitHub API · TS | [Live](https://get-git-search.vercel.app/) · [Repo](https://github.com/0xuser64bit/get-git) |
| **cry-on-crash** | VS Code extension — plays a sound when terminal commands fail or new diagnostics appear | TypeScript · VS Code API | [Repo](https://github.com/0xuser64bit/cry-on-crash) |
| **Notebook** | Open-source Notion alternative with a privacy focus | Next.js · Convex · TS · Tailwind | [Live](https://notebook-self-phi.vercel.app/) · [Repo](https://github.com/0xuser64bit/notebook) |
| **Suchi** | Minimalist Rust CLI for organizing thoughts and tasks | Rust | [Crate](https://crates.io/crates/suchi) · [Repo](https://github.com/0xuser64bit/suchi) |
| **Echo GPT** | Chrome extension to bookmark & pin ChatGPT conversations | TS · Chrome APIs | [Repo](https://github.com/0xuser64bit/echo-gpt) |
| **Job Not Finished** | A wake-up call dashboard for your abandoned GitHub repos | Next.js 15 · GitHub API · TS | [Live](https://job-not-finished.vercel.app) · [Repo](https://github.com/0xuser64bit/job-not-finished) |
| **ChibiTown** | Cozy 2D virtual town for your team — pick a character, walk a pixel-art room, and watch everyone move in real time over WebSocket presence; create a room, share the ID, people walk in | React · TS · Phaser · Express · Prisma · WebSocket · Turborepo | [Demo](https://youtu.be/Whr1wNQ97Tc) · [Repo](https://github.com/0xuser64bit/ChibiTown) |

---

### 🧪 Earlier Builds

`CryptoCompass` · `CodeRunner` · `Streamify` · `Flashcards` · `Tweet-it` · `Canteen` — see the profile for the full archive.

---

## 🔎 Want more?

> Explore every PR, review & open-source contribution on **[Get Git →](https://get-git-search.vercel.app/0xuser64bit)**
