<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=blur&color=0:FF7A00,30:FF9900,70:FF0099,100:FF7A00&height=220&section=header&text=SkyneticLabs🔸Validator%20Infrastructure&fontSize=38&fontAlignY=50&fontColor=000000" />
</p>

<p align="center">
  <i>Engineering stability. Powering decentralization.</i><br/>
  <sub>Staking provider · bare metal in Buenos Aires 🇦🇷</sub>
</p>

<p align="center">
  <a href="https://skyneticlabs.com/"><img src="https://img.shields.io/badge/Website-skyneticlabs.com-FF7A00?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://skyneticlabs.gitbook.io/docs"><img src="https://img.shields.io/badge/Docs-GitBook-FF9900?style=for-the-badge&logo=gitbook&logoColor=white" /></a>
  <a href="https://x.com/SkyneticTeam"><img src="https://img.shields.io/badge/X-@SkyneticTeam-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="mailto:skyneticlabs@gmail.com?subject=Skyneticlabs%20inquiry"><img src="https://img.shields.io/badge/Email-Contact%20us-FF0099?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<div align="center">

| 🌐 **9** | ✅ **99.9%** | 💸 **from 5%** | 🛰️ **24/7** |
|:---:|:---:|:---:|:---:|
| mainnets & testnets | avg. signing rate | commission on mainnets | monitoring & on-call |

</div>

---

### 🪐 About Us
We are a team of blockchain engineers and node operators focused on reliability, automation, and security across decentralized networks.  
Our mission is to provide the backbone for Web3 — stable validators, real-time monitoring, and resilient infrastructure.

🧠 Continuous optimization  
🛰️ Multi-network participation  
🧩 Automated monitoring & failover  
🛡️ Security-first validation  

---

### ⚡ What We Do
- Run validators on emerging testnets and mainnets  
- Design automated monitoring & alerting systems (Grafana / Prometheus)  
- Integrate TMKMS and Horcrux for secure key management  
- Build tools that help networks grow and stay decentralized  

---

### 🖥️ Infrastructure
**We run validators on hardware we own** — no cloud, no shared hosting, nothing rented by the hour.

| | |
|---|---|
| 📍 Location | Buenos Aires, Argentina |
| 🧱 Servers | Dedicated bare metal · AMD EPYC, 32 cores |
| 🧠 Memory | 192 GB ECC |
| 💾 Storage | 16 TB NVMe on ZFS |
| 🔌 Network | 10–100 Gbps uplink |
| 🔐 Keys | Remote signer + sentry nodes, keys never on internet-facing machines |
| 📈 Ops | 24/7 metrics & alerting · upgrades tested on testnet first · off-site backups |

> 🌎 **Why Latin America?** Most validators sit in Europe (~53%) and North America (~26%); Latin America hosts **under 1%**.  
> Staking with us adds real geographic diversity to the networks you care about.

---

### 📊 Public Dashboards & Tools
Free, read-only analytics we build and maintain for the ecosystems we validate.

| Tool | What it shows |
|---|---|
| 🟣 **[Celestia Economic Dashboard](https://skyneticlabs.com/celestia)** | Live staking yield, inflation ladder & 10-year supply projection, who pays for security, flat per-MB data costs, stake concentration, self-bond, unclaimed rewards, trends, correlations and the bot.fun agent economy |
| 🔎 **[Celestia Validator & Fund Lookup](https://skyneticlabs.com/celestia/lookup/)** | Foundation Delegation Program seats, uptime of seat holders, jailed validators and archived cohorts |
| 🟪 **[Monad Economics Terminal](https://skyneticlabs.com/monad)** | Real cost of a MON transfer, block headroom, fee predictability (base / priority fee p50–p90), stake distribution, commissions and top validators |
| 📚 **[Node Operator Guides](https://skyneticlabs.gitbook.io/docs)** | Installation, upgrades, useful commands, DA nodes, TMKMS / Horcrux and monitoring setup |

#### 🔌 Celestia Public API
Open, read-only JSON API behind the Celestia dashboard — **no auth, open CORS, 30s cache.**

```bash
curl https://skyneticlabs.com/celestia/api/v1/insights
```

| Endpoint | Returns |
|---|---|
| `/network` | Chain state, block load, mempool |
| `/economics/supply` · `/staking` · `/fees` | Supply & inflation, bonded ratio & top-N share, fee stats |
| `/economics/da-cost?mb=24000` | Data-availability cost calculator |
| `/validators` · `/validators/<moniker-or-valoper>` | Filterable validator list and single profiles |
| `/namespaces/<namespace_id>` | DA footprint of a rollup or appchain |
| `/series/<key>` | Historical time series |
| `/insights` | 24h / 7d changes in plain English |

Full index: [`skyneticlabs.com/celestia/api/v1/`](https://skyneticlabs.com/celestia/api/v1/) · 🚧 **skynetic-da** — open-source Python SDK for tracking namespace DA costs, coming soon.

---

### 🛠️ Services
- **Validator Operations** — sentry architecture, double-sign protection & alerts, multi-region layouts, backups and recovery runbooks  
- **Infrastructure as a Service** — dedicated RPC & indexer deployments, observability-first monitoring pipelines, on-call rotations  
- **Staking Solutions** — non-custodial delegation, reward tracking & alerts, optional auto-compounding. No hidden or withdrawal fees — your tokens never leave your wallet  
- **Custom Infrastructure** — validators, sentries and monitoring for other networks or funds, from testnet to mainnet  

---

### 🌐 Networks
<p>
  <a href="https://celestia-dashboard.krews.xyz/celestia-mocha/validators/celestiavaloper1uqnlzylk0uld4azf2n0awclxxtllmr7d0xrj3m"><img src="https://img.shields.io/badge/Celestia-7B2BF9?style=flat-square" /></a>
  <a href="https://testnet.monad-watchtower.xyz/validator/0x034799aeb98c40f05cfb068aa5ed17e72646932dce1c567aef43ee9873265a204e"><img src="https://img.shields.io/badge/Monad-836EF9?style=flat-square" /></a>
  <a href="https://solscan.io/account/9jJ3YRBL611e7xjXFMBExuninmTWjDnv3FXNotHmPnK2"><img src="https://img.shields.io/badge/Solana-14F195?style=flat-square&logoColor=black" /></a>
  <a href="https://voyager.online/staking?validator=0x0557b00b15bcad5ee10b708b41bd4291f319d4e4bf1fd43bfd88a5391f24318d"><img src="https://img.shields.io/badge/Starknet-EC796B?style=flat-square" /></a>
  <a href="https://lavacenter.xyz/lava/staking/lava@valoper1qfqv8p0la87pfjlhzf8tgdr0cv0x6xv4tweetd"><img src="https://img.shields.io/badge/Lava-E5352C?style=flat-square" /></a>
  <a href="https://explorer.kyve.network/kyve/staking/kyvevaloper156nsewj7e9ekyqe359fkfxvphuvl47mt5j5a7j"><img src="https://img.shields.io/badge/KYVE-1A1A1A?style=flat-square" /></a>
  <a href="https://explorer.nodestake.org/gitopia/staking/gitopiavaloper1wywnym4hduwp5nu9pfelhda79ugk0t09fc9ny0"><img src="https://img.shields.io/badge/Gitopia-D946EF?style=flat-square" /></a>
  <a href="https://explorer.nodestake.org/arkeo/staking/arkeovaloper1wnx2p0phrh780p2k4xaqpqp0hxa62usjhq6xt5"><img src="https://img.shields.io/badge/Arkeo-2DD4BF?style=flat-square" /></a>
  <a href="https://explorer.nodestake.org/aura/staking/auravaloper18q3rc7y0q00u26tm8ejua5c4kh93axrk4pzp3k"><img src="https://img.shields.io/badge/Aura-F59E0B?style=flat-square" /></a>
</p>

<sub>👆 Click a network to open our validator in its explorer. Mainnet: Solana, Starknet, Lava, KYVE, Gitopia, Arkeo, Aura · Testnet: Celestia (Mocha, our home network), Monad.</sub>

📦 Validator details, dashboards, Celestia API and security checklists for every network: **[SkyneticLabs-Validator-Portal](https://github.com/Skyneticlabs/SkyneticLabs-Validator-Portal)**

---

### 🤝 How to Delegate
1. **Pick a network** from the list above  
2. **Check us on-chain** — commission, uptime and voting history are all public  
3. **Delegate from your own wallet** — delegation never transfers custody  

---

### 🔭 Vision
> “Infrastructure should be invisible — only its reliability should be felt.”

We aim to make validator operations seamless, transparent, and trusted —  
so Web3 networks can scale without compromise.

---

<p align="center">
  <a href="https://skyneticlabs.com/">skyneticlabs.com</a> ·
  <a href="https://skyneticlabs.com/celestia">Celestia Dashboard</a> ·
  <a href="https://skyneticlabs.com/monad">Monad Terminal</a> ·
  <a href="https://skyneticlabs.com/celestia/api/v1/">API</a> ·
  <a href="https://skyneticlabs.gitbook.io/docs">Docs</a> ·
  <a href="https://x.com/SkyneticTeam">X / Twitter</a>
</p>



