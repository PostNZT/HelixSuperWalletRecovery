# HelixWalletRecovery
Debian-based Linux:
 aptitude install build-essential python-dev python-twisted python-bsddb3
 pip install of the bsddb may be required.
 
python helixWalletRecovery.py wallet.dat

# AFTER GETTING THE PRIVATE KEY RUN THIS CODE:
helix-cli -rpcuser="YOURMACHINEUSERNAME" -rpcpassword="YOURMACHINEPASSWORD importprivkey "PRIVATE KEYS" 

