# 🛡️ VibeSec: The Next-Gen Cybersecurity Forum

Built with 🚀 VibeStack — The Ultimate AI-Native Fullstack Weapon
VibeSec 是一個為 2026 年資安專家打造的極速、極簡、極致安全的討論平台。我們拒絕冗餘的傳統架構，利用 VibeStack 的特性，實現了從 Schema 到 UI 的「端到端型別安全」，讓 AI 在開發過程中幾乎零幻覺，讓討論區在運行時擁有頂級性能。



## ✨ 核心優勢 (The Vibe)
* ⚡️ 性能拉滿： 基於 Bun 運行時與 ElysiaJS，提供接近原生的 I/O 效能。配合 SolidStart 的 fine-grained reactivity，確保討論區在大規模併發下依然流暢。
* 🧠 AI-Native (Zero Hallucination)：透過 ArkType 定義「唯一真相來源 (SSOT)」，配合 .cursor/rules 嚴格鐵律，讓 AI 在生成代碼時自動遵守型別約束，徹底杜絕邏輯漏洞。
* 🛡️ 端到端型別安全： 利用 Eden Treaty，後端 API 修改的瞬間，前端立即獲得型別提示。在資安領域，型別錯誤就是安全隱患，我們從根源抹除。
* 📦 部署極簡： 真正的 Single Container 架構，一行指令即刻上線，支持 Edge Runtime。



## 📂 專案結構

```text
.
├── docker/                  # 單一容器部署配置 (Bun-optimized)
├── apps/
│   └── web/                 # SolidStart (SSR + Islands 混合架構)
├── packages/
│   ├── shared/              # ArkType Schemas (唯一真相：用戶、貼文、PoC 驗證邏輯)
│   └── config/              # 共用配置 (Strict TS, ESLint)
├── .cursor/rules/           # AI 鐵律 (讓 Cursor/Claude 自動聽從 VibeStack 規範)
├── turbo.json               # Monorepo 高速構建管理
├── package.json
└── README.md
```




## 🛠️ 技術棧 (The Stack)
Runtime: Bun (Fast all-in-one JavaScript runtime)
Backend: ElysiaJS (Ergonomic Framework for Humans)
Frontend: SolidStart (The most performant SSR framework)
Type System: ArkType (The runtime type system that's 100x faster than Zod)
Communication: Eden Treaty (Fully type-safe client)



## 🚀 快速開始

1. 複製專案

```bash
git clone https://github.com
cd vibesec
```


2. 安裝依賴 (Powered by Bun)

```bash
bun install
```


3. 開發模式

```bash
bun dev
```


4. 生產環境部署 (Docker)

```bash
docker build -t vibesec .
docker run -p 3000:3000 vibesec
```




## 🛡️ 資安承諾
VibeSec 不僅僅是一個討論區，它的開發過程體現了 **「零信任」** 的工程實踐：
嚴格輸入驗證： 所有 Request 經由 ArkType 進行運行時校驗。
* 型別隔離： 敏感邏輯強制封裝在 packages/shared，防止前端洩漏敏感元數據。
* 效能防禦： 憑藉 Bun 的高效能，天然具備更強的抗小型 DoS 能力。



## 🤝 貢獻指南
請確保你的 AI (Claude/Cursor) 已加載 `.cursor/rules`。
Vibe Coding 守則： 先定義 ArkType Schema，再寫邏輯。不合型別的代碼，連 `bun dev` 都過不了。

---

VibeSec: Security discussions at the speed of thought.<br/>
Powered by VibeStack. 🚀
