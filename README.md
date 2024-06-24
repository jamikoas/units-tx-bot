# units-tx-bot

- Regsiter Jika Belum Garap : https://app.units.network/?referral=0xFc4F17A20350e47f490bb2663E78Ce40Cf7Bf7B4
- Connect Metamask > Connect Twitter
- Claim Faucet (USE VPN) : https://faucet-testnet.unit0.dev

## Install Python

```
sudo apt update && sudo apt install git
```

```
sudo apt install python3 python3-pip && pip install requests python-dotenv eth_account colorama
```

## Clone Github

```
git clone https://github.com/jamikoas/units-tx-bot.git
cd units-tx-bot
```

## Buat File .env

```
nano .env
```

Paste dan Ubah 

```
PRIVATE_KEY=PK-KALIAN
SENDER_ADDRESS=ALAMAT-PENGIRIM-KALIAN
```

CTRL X + Y Untuk Simpan

## Jalankan Dan Mulai Transaksi

```
python3 units.py
```


