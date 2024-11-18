## BLOCKMESH NETWORK AUTO REFERRAL BOT

Automatic Referral Script for BlockMesh Network Account using proxies.

## PREREQUISITE

1. BlockMesh Network Account : [Register](https://app.blockmesh.xyz/register?invite_code=b54361aa-8051-463e-bd05-fe016a572215)
3. VPS or RDP (OPTIONAL)
4. Python3 Latest Version

## INSTALLATION

Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)

1. Clone project repository
   ```bash
   git clone https://github.com/Rambeboy/blockmesh-autoreferral-bot.git && cd blockmesh-autoreferral-bot
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

## RUN BOT

- Replace the proxies example in ```proxies.txt``` to your own proxies with format:
  ```bash
  http://host:port
  http://user:pass@host:port
  ```

- only http proxies support for now, if you want to run without proxies, just remove proxies.txt content or delete `proxies.txt`.

## RUN COMMAND

- Windows:
  ```bash
  python main.py
  ```

- Unix
  ```bash
  python3 main.py
  ```

- Insert your full referral URL, example: ``https://app.blockmesh.xyz/register?invite_code=XXXXXXXXXX``
- Enter how many referrals you want
- Result account generated will be saved to ``accounts.txt``.

## NOTE

- Run this bot, and it will update your referrer code to my invite code if you don't have one.

- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.

---
