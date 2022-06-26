# Hide my mac

Hide MAC address in WIFI IPv4 network, be undetectable to network scan and prevent
arp poisoning attacks

## 🚀 Getting Started

### 📋 Dependencies

1. Systemd [NetworkManager](https://wiki.archlinux.org/title/NetworkManager)
2. [arptables](https://man.archlinux.org/man/core/iptables/arptables-nft.8.en)
3. Dig

### 🔧 Installing

1. Copy this repository

    ```bash
    git clone https://github.com/srealmoreno/hide-my-mac.git
    cd hide-my-mac
    ```

2. Copy the script

   ```hash
   sudo cp src/01-hide-my-mac /etc/NetworkManager/dispatcher.d/
   ```

3. Add execute permission

   ```bash
   sudo chmod +x /etc/NetworkManager/dispatcher.d/01-hide-my-mac
   ```
