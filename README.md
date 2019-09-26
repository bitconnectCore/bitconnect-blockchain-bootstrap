# bitconnectCoin-blockchain-bootstrap

Chain-data files for **The bitconnectCoin / BCC blockchain.** Using these files significantly reduces the time to sync the bitconnectCoin blockchain from scratch.

[Discord](https://discordapp.com/invite/JxMNabw)

General Wallet Tutorials: [New](https://youtu.be/RTieeNXGNrE) | [Old](https://youtu.be/OFPNmYAQYdw)

Wallets:
[bitconnect GitHub](https://github.com/bitconnectcoin/bitconnectcoin/tree/master/setup) | [bitconnectCoin.info GitHub](https://github.com/bitconnectcoininfo/bitconnectcoin/releases)

---

**If You Have Ran The bitconnectCoin Wallet On Your Device:**

**1.** [Download the latest bootstrap files.](https://github.com/bitconnectCore/bitconnectCoin-blockchain-bootstrap/releases)

**2.** Find the downloaded bitconnect.zip file and double-click. This will unzip the file and show a folder named bitconnect.

**3.** Close and quit the bitconnectCoin wallet, (if it is running).

**4.** Navigate to your OS's respective data directory.

* For Windows: C:\Users\[YourUsername]\AppData\Roaming\bitconnect\
Or paste %appdata%\Roaming\bitconnect\ into the file explorer path field
* For MacOS: ~/Library/Application Support/bitconnect/
Open Finder and in the program menu select Go > To Folder and enter the above path.
* For Linux: ~/.bitconnect/

**5.** Remove all files and folders **except** for wallet.dat, bitconnect.conf (may not have this file).
**Do not** delete the wallet.dat file as it contains the private keys for your funds. **Deleting this file will result in loss of funds!**

**6.** Inside the downloaded bitconnect folder there is **one** folder and **two** files. Move all **three** items into the bitconnectCoin wallet's data directory that you just removed files from.
* **txleveldb**   - File Folder
* **blk0001.dat** - DAT File
* **bitconnect**  - CONF File

**7.** Run the wallet and syncing should begin at the bootstrap's last block.

---

**If You Have Not Ran The bitconnectCoin Wallet On Your Device:**

**1.** [Download the latest bootstrap files.](https://github.com/bitconnectCore/bitconnectCoin-blockchain-bootstrap/releases)

**2.** Find the downloaded bitconnect.zip file and double-click. This will unzip the file and show a folder named bitconnect.

**3.** Move the bitconnect folder to your OS's respective data directory.

* For Windows: C:\Users\[YourUsername]\AppData\Roaming\
Or paste %appdata%\Roaming\ into the file explorer path field.
* For MacOS: ~/Library/Application Support/
Open Finder and in the program menu select Go > To Folder and enter the above path.
* For Linux: ~/
     
    *For Linux you must rename the bitconnect folder to .bitconnect*

**4.** Run the wallet and syncing should begin at the bootstrap's last block.

---

![alt text](https://static.wixstatic.com/media/28f073_4f483842f4bd4586ab222d2764cfca17~mv2.png/v1/fill/w_1046,h_1042/Waves.PNG.png "Coming In Waves")
