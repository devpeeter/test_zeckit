# test_zeckit

A demonstration project for integrating **ZecKit**, the rapid Zcash devnet toolkit for GitHub Actions.

## 🚀 Overview
This repository serves as a minimal example of how to spin up a private Zcash regression testing (regtest) environment in CI/CD. It uses ZecKit to provide:
- A 2-node **Zebra** cluster (Miner + Sync).
- An embedded **Shielded Faucet**.
- A **Zaino** privacy backend.

## 🧪 Automated Testing
Every commit to this branch triggers a ZecKit environment. You can find the CI configuration in [`.github/workflows/zeckit-e2e.yml`](.github/workflows/zeckit-e2e.yml).

## 🛠️ Local Development
To run this devnet locally, install the `zeckit` CLI and run:
```bash
zeckit up --backend zaino
```

---
Built with [ZecKit](https://github.com/intelliDean/ZecKit).
