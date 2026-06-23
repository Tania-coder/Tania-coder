# Tatiana Radchenko 🇩🇰

**AI Infrastructure Engineer & Founder** · Aarhus, Denmark

---

## 🧠 How I Think About AI Reliability

Most teams find out their model silently changed at 2am — from parse errors, not from their monitoring stack. Latency is normal. Uptime is 100%. But the model underneath is different.

I built infrastructure to detect this before it becomes a crisis. Not by trusting a single observer, but by correlating signals across independent organizations — so no single noise source triggers a false alarm.

---

## 🛠 What I Built

### [SEISMOGRAPH](https://github.com/Tania-coder/SEISMOGRAPH)
*Federated, privacy-preserving early-warning network for silent LLM API drift.*

- **Canary Probe SDK** — raw prompts never leave your perimeter. Only DP-noised features and SHA-256 hashes are transmitted.
- **Page-CUSUM detection** — change-point detection per `(model, metric)` tuple with shared cross-org baseline.
- **Quorum gate** — a single-org signal never becomes a public alert.

---

## 📈 Proven in the Wild

Detected the **Anthropic Claude 3.5 Sonnet** silent degradation on 2025-08-10 —
**38 days before the official postmortem** and 19 days before load-balancer escalation became visible to users.

```bash
pip install seismograph-probe
```

---

## 📬 Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tania--radchenko-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/tania-radchenko)
[![Twitter](https://img.shields.io/badge/Twitter-@tatyanti-1DA1F2?style=flat&logo=twitter)](https://x.com/tatyanti)
[![GitHub](https://img.shields.io/badge/GitHub-Tania--coder-181717?style=flat&logo=github)](https://github.com/Tania-coder)
[![SEISMOGRAPH](https://img.shields.io/badge/Project-SEISMOGRAPH-00c896?style=flat)](https://github.com/Tania-coder/SEISMOGRAPH)
