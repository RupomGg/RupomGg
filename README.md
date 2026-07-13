<div align="center">

<img src="assets/banner.svg" alt="Rupom Ahamed banner" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=800&color=00D1B2&center=true&vCenter=true&width=650&lines=Shipping+production+dApps+on+Solana+%26+Ethereum;Building+RAG+systems+and+applied+ML+pipelines;Data+Engineering+%7C+Web3+%7C+Generative+AI;Open+to+Blockchain+%2F+AI+%2F+Data+roles" alt="Typing SVG"/>

[![Portfolio](https://img.shields.io/badge/Portfolio-radwanahamed.dev-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://radwanahamed.dev)
![Open to Work](https://img.shields.io/badge/Open%20to%20Work-00D1B2?style=for-the-badge&logo=handshake&logoColor=black)
![Location](https://img.shields.io/badge/Dhaka%2C%20Bangladesh-2EA3F7?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

<br/>

## 🧭 About

I'm a software engineer working across two disciplines that don't usually overlap — **blockchain systems** and **applied AI/ML** — plus the data engineering that ties both together in production.

- 🔗 I design and ship dApps end-to-end: smart contracts, wallet integration, order-matching logic, and the frontend that makes it usable
- 🧠 I build applied ML systems, from computer-vision pipelines to retrieval-augmented generation, with a focus on things that actually run in production, not just notebooks
- 💼 Junior Software Engineer @ **Betopia Group**, on a crypto-backed investment platform — transaction auditing, SQL reporting pipelines, Power BI dashboards
- 🎓 Computer Science graduate, BRAC University
- 📸 Off the clock: photography (people, stories, expressions), gaming, music
- 🟢 **Currently open to opportunities** in Blockchain Engineering, AI/ML Engineering, and Data Engineering

<br/>

## ⛓️ Blockchain Engineering

<sub>What I bring: EVM & Solana smart contracts, wallet auth (MetaMask/RainbowKit/Wagmi), payment rails (Stripe, PayPal, Coinbase Commerce), upgradeable contract patterns, and full-stack delivery from chain to UI.</sub>

### 📌 [PharmaChain](https://github.com/RupomGg/Pharmachain) — Enterprise Pharmaceutical Supply Chain Platform

A production-architected decentralized application bringing end-to-end traceability to pharmaceutical supply chains on Ethereum. Every batch — from manufacturer to pharmacy shelf — is recorded immutably on-chain and independently verifiable.

- **Multi-role system**: dedicated manufacturer, distributor, and admin dashboards with role-based access control (RBAC)
- **Batch lifecycle management**: metadata-rich batch creation (composition, expiry, quantity), bulk operations, and real-time inventory tracking
- **Advanced traceability**: interactive "Asset DNA" journey maps with geo-tagged movement, transaction hashes, and block timestamps
- **Marketplace layer**: distributors browse and order verified stock directly from manufacturers, with visual authenticity checks before acceptance
- **Contract architecture**: Solidity contracts built on the **UUPS upgradeable proxy pattern** (OpenZeppelin) for long-term maintainability, deployed and verified on Sepolia via Hardhat
- **Stack**: Solidity · Hardhat · React 19 · Vite · TailwindCSS · RainbowKit · Wagmi · Ethers.js/Viem · Framer Motion

`Solidity` `Hardhat` `React` `Web3` `RBAC` `Supply Chain`

---

### 📌 [Nebula Launchpad](https://github.com/RupomGg/Nebula-Launchpad) — Decentralized Token Launch & Investment Platform

A full-stack launchpad connecting token creators with investors, live on Sepolia testnet, covering the entire lifecycle from token creation to secondary trading and platform oversight.

- **Creator tooling**: guided token launch flow with customizable parameters, plus dedicated dashboards for owners to manage live projects
- **Investor experience**: secure presale and investment portal with a browsable gallery of launched and upcoming projects
- **Admin layer**: full platform oversight dashboard with real-time analytics on token performance and platform-wide statistics
- **Contract architecture**: upgradeable contracts (OpenZeppelin Upgradeable) deployed via Hardhat to Sepolia (Chain ID `11155111`)
- **Stack**: React · Vite · TailwindCSS · Wagmi · RainbowKit · Viem · Recharts · Hardhat · OpenZeppelin Upgradeable

`Solidity` `Token Launchpad` `DeFi` `React` `Web3`

---

### 🔒 Aurumchain — KYC-Gated Tokenized Investment Platform *(Client Project — NDA)*

Built on **Solana** using **Anchor/Rust**, Aurumchain is a KYC-gated tokenized investment platform featuring a peer-to-peer secondary market with a custom order-matching engine. This was delivered as a client engagement, so the codebase and detailed architecture are **confidential under NDA** and can't be shared publicly — happy to discuss the design and technical decisions in more depth in an interview or call.

`Solana` `Anchor` `Rust` `Order Matching` `KYC/Compliance`

<br/>

## 🧠 AI / Machine Learning

<sub>What I bring: computer vision pipelines, retrieval-augmented generation, GNN-based causal inference, and getting models from notebook to a real serving stack.</sub>

### 📌 [Smart Drone Traffic Analyzer](https://github.com/RupomGg/Smart-Drone-Traffic-Analyzer) — Neural Engine v11

A full-stack, production-grade AI application that turns raw drone footage into high-fidelity traffic analytics, built on a decoupled architecture with a GPU-accelerated backend and a real-time Next.js frontend.

- **Detection & tracking**: **YOLO11m** for small-object aerial detection, paired with **ByteTrack** for persistent multi-object tracking through occlusions
- **Robust counting logic**: dual-line tripwire system based on bounding-box intersection (not center-points) — correctly counts long vehicles like buses and trains instead of missing or double-counting them
- **Live telemetry**: a custom terminal-style interface streaming real backend events (GPU status, tracker init, detection triggers) to the frontend in real time
- **Hybrid cloud architecture**: backend deployed on **Hugging Face ZeroGPU** (Docker, A100-accelerated) via the `@spaces.GPU` decorator, frontend on **Vercel** for low-latency delivery
- **Video engineering**: integrated FFmpeg re-encoding pass (`libx264`) so every processed clip is playable in standard browsers
- **Stack**: FastAPI · YOLO11m · ByteTrack · PyTorch · Next.js · Recharts · Docker · Hugging Face ZeroGPU

`Computer Vision` `YOLO` `FastAPI` `Next.js` `MLOps`

<br/>

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Blockchain / Web3**
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Anchor](https://img.shields.io/badge/Anchor-512DA8?style=flat-square)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=flat-square&logo=ethereum&logoColor=black)
![MetaMask](https://img.shields.io/badge/MetaMask-F6851B?style=flat-square&logo=metamask&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Data / Backend / Tools**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

## 🌐 Languages

| Language | Proficiency |
|---|---|
| 🇧🇩 Bangla | Native |
| 🇬🇧 English | Professional working proficiency |

<br/>

## 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=RupomGg&show_icons=true&theme=tokyonight&hide_border=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RupomGg&layout=compact&theme=tokyonight&hide_border=true"/>
</div>

<br/>

## 📫 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://radwanahamed.dev)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)

**Open to Blockchain Engineering, AI/ML Engineering, and Data Engineering roles — reach out anytime.**

</div>
