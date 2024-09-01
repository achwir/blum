
# Blum Bot
Auto Claim Blum

## Installation

Install with VPS/termux

VPS

```bash
  apt update && apt upgrade
```

```bash
  apt install git
```

```bash
  apt install nodejs
```

```bash
  apt install python3
```

```bash
  git clone https://github.com/achwir/blum
```

```bash
  python3 -m venv tomarket
```

```bash
  source tomarket/bin/activate
```

```bash
  pip install requests colorama
```

TERMUX

```bash
  pkg update && pkg upgrade
```

```bash
  pkg install git
```

```bash
  pkg install nodejs
```

```bash
  pkg install python
```

```bash
  git clone https://github.com/achwir/blum
```

```bash
  python -m venv tomarket
```

```bash
  source tomarket/bin/activate
```

```bash
  pip install requests colorama
```

## Untuk memasukkan query nya
```bash
  nano tgwebapp.txt
```

## Cara mencari query
```bash
  1. Buka Bot Blum di PC (Telegram Web / Desktop)
  2. Ambil query_id 
  3. Caranya > inspek elemen > terus ke application > storage (session storage) > pilih telegram.blum.codes
  4. Pilih __telegram_initparam > tgwebappdata ambil query_id=xxx (ambil semua) kecuali tgwebappnya
  5. Paste di tgwebapp.txt
```

## Running bot
```bash
  python blum.py
```

## Features

- Auto Get Token
- Auto Claim Blum
- Auto Claim Balance Friend
- Auto Playing Game with max score
- Auto Checkin Daily
- Multi Account

### SOURCE : https://github.com/LFG-AAI/taptap/tree/main/files/Blum%20Crypto
