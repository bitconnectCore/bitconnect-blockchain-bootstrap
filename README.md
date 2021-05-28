# bitconnect-blockchain-bootstrap

**Chain-data files for the BCC / BitConnect Coin / bitconnectCoin blockchain. Using these files significantly reduces the time to sync from scratch.**

**General bitconnect GUI Full-Node Wallet Tutorial:** [YouTube](https://youtu.be/RTieeNXGNrE "YouTube")

**bitconnect BlockChain GUI Full-Nodes:**
[bitconnect GitHub](https://github.com/bitconnectcoin/bitconnectcoin/tree/master/setup "bitconnect GitHub")

---

## Latest GitHub Release Direct Download: [Here](https://github.com/bitconnectCore/bitconnectCoin-blockchain-bootstrap/releases/download/1.0/bitconnect.zip "Download")

**BlockChain Block Height -** 1,083,000 *(March 2020)*

**bitconnect.Zip SHA256 CheckSum -** fa28f1c06e1ce1b4d66db10046806d4e4d71298e224e6a30412ca1b0ff183992

**Contents**

**1.** blk.0001.dat *(needed)*

**2.** txleveldb folder *(needed)*

**3.** bitconnect.conf *(for updating peers)*

**4.** peers.dat *(optional)*

---

### If You Have Ran The bitconnectCoin Wallet On Your Device:

**1.** [Download the latest bootstrap files.](https://github.com/bitconnectCore/bitconnectCoin-blockchain-bootstrap/releases "The Latest BCC Bootstrap Files Release")

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

**6.** Inside the downloaded bitconnect folder there is **one** folder and **three** files. Move all **four** items into the bitconnectCoin wallet's data directory that you just removed files from.
* **txleveldb**   - File Folder
* **blk0001.dat** - DAT File
* **peers.dat** - DAT File
* **bitconnect**  - CONF File

**7.** Run the wallet and syncing should begin at the bootstrap's last block.

---

#### If You Have Not Ran The bitconnectCoin Wallet On Your Device:

**1.** [Download the latest bootstrap files.](https://github.com/bitconnectCore/bitconnectCoin-blockchain-bootstrap/releases "The Latest BCC Bootstrap Files Release")

**2.** Find the downloaded bitconnect.zip file and double-click. This will unzip the file and show a folder named bitconnect.

**3.** Move the bitconnect folder to your OS's respective data directory.

* For Windows: C:\Users\[YourUsername]\AppData\Roaming\
Or paste %appdata%\Roaming\ into the file explorer path field.
* For MacOS: ~/Library/Application Support/
Open Finder and in the program menu select Go > To Folder and enter the above path.
* For Linux: ~/
     
    *For Linux you must rename the bitconnect folder to .bitconnect*

**4.** Run the wallet and syncing should begin at the bootstrap's last block.
