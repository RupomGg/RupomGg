<div align="center">

<img src="assets/banner.png" alt="Rupom Ahamed banner" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2800&pause=900&color=00D1B2&center=true&vCenter=true&width=680&lines=Blockchain+engineer+%E2%80%94+Solana+%26+Ethereum;Computer+vision+%7C+RAG+%7C+Applied+ML;Data+Engineering+that+actually+ships;Open+to+Blockchain+%2F+AI+%2F+Data+roles" alt="Typing SVG"/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-rupomgg.dev-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://radwanahamed.dev)
![Open to Work](https://img.shields.io/badge/Open+to+Work-%2300D1B2?style=for-the-badge&logo=checkmarx&logoColor=black)
![Dhaka](https://img.shields.io/badge/Dhaka%2C+Bangladesh-2EA3F7?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 👋 Hey, I'm Rupom

I fell into blockchain through curiosity and stayed because it's genuinely hard — the kind of hard where debugging a re-entrancy bug at midnight actually feels satisfying. On the side I've been building ML pipelines, mostly computer vision and RAG systems, which turned out to pair surprisingly well with on-chain data.

Right now I'm at **Betopia Group** shipping a crypto-backed investment platform — audit trails, SQL reporting, the glue work that nobody talks about but everything depends on.

**What I actually do well:**
- Writing Solidity and Rust contracts that hold up under pressure, not just on testnets
- Wiring a full dApp together — wallet auth, payment rails, frontend — without the seams showing
- Getting ML models out of notebooks and into something that serves real traffic
- Building data pipelines that are boring in the best possible way (reliable, observable, no surprises)

Outside work: street photography, gaming when I have the time, music as background to everything else.

**Currently looking for** Blockchain Engineering, AI/ML, or Data Engineering roles — DM me.

<br/>

## ⛓️ Blockchain

> EVM & Solana smart contracts · wallet auth (MetaMask / RainbowKit / Wagmi) · payment rails · upgradeable proxy patterns · full-stack delivery

### [PharmaChain](https://github.com/RupomGg/Pharmachain) — Supply Chain on Ethereum

Pharmaceutical supply chains are a mess — counterfeits, opacity, paper trails that vanish. PharmaChain puts every batch on-chain so it can be independently verified at any point from manufacture to shelf.

The interesting parts: a multi-role RBAC system where manufacturers, distributors, and admins each get their own dashboard; an "Asset DNA" traceability view that maps a batch's full journey with geo-tags and block timestamps; and contracts built on the UUPS upgradeable proxy pattern so the protocol can evolve without nuking existing data.

`Solidity` `Hardhat` `React 19` `Vite` `TailwindCSS` `RainbowKit` `Wagmi` `Viem` `RBAC`

---

### [Nebula Launchpad](https://github.com/RupomGg/Nebula-Launchpad) — Token Launchpad & DeFi Platform

A full-stack launchpad on Sepolia covering the whole token lifecycle — creators launch with custom parameters, investors browse presales, an admin layer watches platform-wide metrics in real time. Upgradeable contracts throughout so the protocol keeps evolving after launch.

`Solidity` `DeFi` `React` `Vite` `Wagmi` `RainbowKit` `Viem` `Recharts` `OpenZeppelin`

---

### 🔒 Aurumchain — KYC-Gated Investment Platform *(Client — NDA)*

Built on **Solana / Anchor + Rust**. KYC-gated tokenized investments with a peer-to-peer secondary market and a custom order-matching engine I'm pretty happy with. Can't share the repo, but happy to walk through the design decisions in a call.

`Solana` `Anchor` `Rust` `Order Matching` `KYC`

<br/>

## 🧠 AI / ML

> Computer vision pipelines · retrieval-augmented generation · GNN-based causal inference · production serving

### [Smart Drone Traffic Analyzer](https://github.com/RupomGg/Smart-Drone-Traffic-Analyzer)

Drone footage → traffic analytics, built as a proper decoupled system rather than a monolithic script. Backend runs YOLO11m + ByteTrack on an A100 via Hugging Face ZeroGPU; the Next.js frontend streams live telemetry in a terminal-style UI.

The part I'm most proud of: a dual-line tripwire system using bounding-box intersection instead of center-points, so long vehicles like buses and articulated trucks get counted correctly instead of being missed or double-counted.

`FastAPI` `YOLO11m` `ByteTrack` `PyTorch` `Next.js` `Docker` `ZeroGPU` `FFmpeg`

<br/>

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%"><b>Languages</b></td>
      <td align="center" width="25%"><b>Blockchain / Web3</b></td>
      <td align="center" width="25%"><b>AI / ML</b></td>
      <td align="center" width="25%"><b>Backend / Data / Tools</b></td>
    </tr>
    <tr>
      <td align="center" valign="top">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /><br/>
        <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
      </td>
      <td align="center" valign="top">
        <img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Anchor-512DA8?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/Hardhat-FFF04D?style=flat-square&logo=ethereum&logoColor=black" /><br/>
        <img src="https://img.shields.io/badge/RainbowKit-7B3FE4?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/Wagmi-1C1C1C?style=flat-square" />
      </td>
      <td align="center" valign="top">
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square" /><br/>
        <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black" /><br/>
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
      </td>
      <td align="center" valign="top">
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" /><br/>
        <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" /><br/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </td>
    </tr>
  </table>
</div>

<br/>

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=RupomGg&theme=tokyonight&hide_border=true&stroke=0000&background=0D1117&ring=00D1B2&fire=FF6B6B&currStreakLabel=00D1B2" alt="GitHub Streak" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api?username=RupomGg&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D1B2&icon_color=6C63FF&text_color=c9d1d9&count_private=true" alt="GitHub Stats" width="49%"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RupomGg&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D1B2&text_color=c9d1d9&langs_count=8" alt="Top Languages" width="49%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=RupomGg&theme=tokyonight&utcOffset=6" alt="Most Productive Time" width="49%"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RupomGg&bg_color=0D1117&color=00D1B2&line=6C63FF&point=FFFFFF&area=true&hide_border=true" alt="Contribution Graph" width="98%"/>

</div>

<br/>

## 🌐 Languages

| | Language | Level |
|---|---|---|
| 🇧🇩 | Bangla | Native |
| 🇬🇧 | English | Professional |

<br/>

## 📫 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://radwanahamed.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@example.com)

<br/>

*Looking for Blockchain Engineering, AI/ML, or Data Engineering roles — drop me a message.*

</div>
