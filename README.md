# Setup and Run Wallet Generator🪂🪂




```bash
curl -fsSL https://bun.sh/install | bash
exec $SHELL
bun --version
```

```bash
sudo apt update && sudo apt install ufw -y
sudo ufw allow 8888
```

```bash
git clone https://github.com/octra-labs/wallet-gen
cd wallet-gen
bun install
bun run build
```

```bash
bun start
```



🔹 STEP 2: Install dependencies In the Codespace terminal, run:

pip install -r requirements.txt

🔹 STEP 3: Create and edit wallet.json Create the wallet file:

cp wallet.json.example wallet.json

Then open the file: wallet.json

Paste your test wallet details (⚠️ never use your real wallet): Wallet Generation

{ "priv": "private key here", "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx", "rpc": "https://octra.network" } 🔹 STEP 4: Send a test transaction python cli.py send --to oct5ziFzQJkiJFPfcQeuAmp4vhfQgjwb8gyx2W2TZdGhzJm --amount 0.01 🟢 That’s it! You can now access the wallet UI and make transactions to addresses found on the explorer: https://octrascan.io/
