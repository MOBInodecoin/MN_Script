# MN-Setup Guide (Follow below Steps)

wget -q https://raw.githubusercontent.com/MOBInodecoin/MN_Script/master/mobinode.sh

sudo chmod +x mobinode.sh

./mobinode.sh

When prompted to Enter your mobinode Masternode GEN Key.

Paster your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain.
For check enter below command.

mobinode-cli getinfo

When Node Fully Synced enter below command for check masternode status.

mobinode-cli masternode status
