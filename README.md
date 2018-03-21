# LINUX_DAEMON:Getting Started

You can setup a node on Ubuntu server using the following instructions.
Rent a VPS running `Ubuntu 14.04` server.
Step 1 : Update your VPS using the following commands.
`sudo apt-get update`
`sudo apt-get upgrade`


Step 2: Install the necessary dependencies using the following commands.
`sudo apt-get install build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev git libssl1.0.0-dbg`
`sudo apt-get install libdb-dev libdb++-dev libboost-all-dev libminiupnpc-dev libminiupnpc-dev libevent-dev libcrypto++-dev libgmp3-dev`


Step 3: Download the deamon file 
`git clone https://github.com/ltcextreme/LINUX_DAEMON.git`

Step 4: Extract the tar file using the following command.
`tar -xzvf litecoinextreme-daemon.tar.gz`

Step 5: Install the daemon.
`chmod +x litecoinextreme`
`sudo mv litecoinextreme /usr/bin/`

Step 6: Create the config file.
`mkdir $HOME/. Litecoinextreme`
`nano $HOME/. litecoinextreme / litecoinextreme.conf`

Step 7: Paste the following lines in examplecoin.conf.
`rpcuser=rpc_ litecoinextreme`
`rpcpassword= litecoinextreme`
`rpcallowip=127.0.0.1`
`listen=1`
`server=1`
`txindex=1`
`daemon=1`

Step 8: Start your node with the following command.

`./ litecoinextreme`

Incase Error Install, install the following package

`sudo apt-get install libboost-system1.53+`



