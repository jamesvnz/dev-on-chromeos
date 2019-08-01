Fork of https://github.com/ukabu/dev-on-chromeos.git

Setup development tool on Chrome OS Terminal (aka Crostini).

These scripts setup all the tools I need :
- NodeJS and Docker
- Bash scripting (jq, httpie, curl)
- VSCode for coding
- python3, pip and pipenv

Open the Terminal app, then

```bash
sudo apt update
sudo apt install git
git clone https://github.com/jamesvnz/dev-on-chromeos.git
cd dev-on-chromeos
./setup.sh
```

Install script are more or less idempotent. This mean that you can rerun them to update or if it fails without causing any issues.
