If you took part in the Pipe Network Node Devnet, you can now upgrade your PoP Node from the Testnet to the Alpha Testnet (Devnet 2) 🕺

Requirements:  
▫️ OS: Ubuntu/Debian
▫️ RAM: Minimum 4GB
▫️ Disk: Minimum 100GB
▫️ 24/7 internet connectivity required


Automation upgrade:
  ```bash
   cd $HOME && wget https://raw.githubusercontent.com/Gifty7/pipe/main/devnet-two.sh && chmod +x devnet-two.sh && ./devnet-two.sh

   ```
If you need referral code:
  ```bash
./pop --signup-by-referral-route f56c292db5871b0f

   ```

Update to v0.2.6 

  ```bash
   sudo systemctl stop pipe && cd $HOME/gifty7 && wget -O pop "https://dl.pipecdn.app/v0.2.6/pop" && chmod +x pop && sudo systemctl daemon-reload && 
sudo systemctl restart pipe && journalctl -u pipe -fo cat

   ```
Manual upgrade, if automation failed:
https://docs.pipe.network/devnet-2


https://x.com/amrit12005
