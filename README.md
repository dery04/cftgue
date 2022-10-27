# Clash For Termux Without Root

# Install
- pkg update && pkg install upgrade -y

- pkg install git -y

- git clone https://github.com/dery04/cftgue.git

- cd ClashForTermux && bash install.sh

- cd

# Edit akun VPN
- ketik micro .config/clash/vpn.yaml
- ctrl + s -> untuk save
- ctrl + q -> untuk keluar

# Running Clash
- ketik "clash" tanpa tanda petik lalu enter

# Open Yacd-Dashboard
- Buka Chrome
- http://127.0.0.1:9090/ui/#/proxies

# Setting IPTABLE Without Root
- Buka pengaturan jaringan
- masuk ke Access Point Names (APN)
- APN : Bebas (Reccomended : internet)
- Proxy : 127.0.0.1
- Port : 7890

