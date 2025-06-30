
# Octra Wallet Generation & Faucet Claim Guide

Step 1:

- Visit: https://github.com/octra-labs/wallet-gen
- Click on the green "Code" button
- Select "Codespace" and click "Create codespace on main"

---

Step 2:

Run these commands

```bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
```
```
bun install
```
```
bun run build
```
```
bun start
```

- Click on the green "Open in Browser"
- Click "generate new wallet"
- Scroll down
- Save (backup) mnemonic, private key, public key & octra address

---

Step 3:

- Visit: https://faucet.octra.network/
- Paste your octra address and claim faucet
- Join Discord: https://discord.gg/ScJc5K7sVr

---

Step 4:

# Send Transactions

Install Python


```
sudo apt install python3 python3-pip python3-venv python3-dev -y
```
2. Install CLI

```
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

cp wallet.json.example wallet.json
```

3. Add wallet to CLI

```
nano wallet.json
```

- Replace the following values:
  * `private-key-here`: Privatekey with `B64` format
  * `octxxxxxxxx...`: Octra address starting with `oct...`

3. Start CLI

```
python3 -m venv venv
source venv/bin/activate
python3 cli.py
```
4. Send transactions

- Send transactions to my address: `oct9KoXHoMmgHTL6yG2DgJRGC2imkp4qtEpXu4JTb7HpvLN`
- Use Octra Explorer to find more octra addresses

---

⚠️  I will share a detailed guide on my Twitter or YouTube once the Octra incentivized testnet goes live.

📢 Make sure to follow us for regular updates

- Twitter: https://x.com/CryptoGurujiOG
- Youtube: https://www.youtube.com/@CryptoGurujiOG
- Telegram: https://www.telegram.me/cryptogurujiog
