# Blockchain-and-Cryptocurrencies
Implemented blockchain application of logging remote storage file.

1. Run below geth commant on your database in the directory where your database is saved in terminal: 
geth --datadir bkc_data --networkid 89992018 --bootnodes enode://d3cd4e70fe7ad1dd7fb23539c53982e42816b4218cc370e8af13945f7b5e2b4a288f8b949dbdba6a998c9141266a0df61523de74490c91fc1e3d538b299bb8ab@128.230.208.73:30301 console 2>console.log 

2. Run below command in geth: 
admin.startRPC() 

3. Unlock your account using below command: 
personal.unlockAccount(eth.accounts[0]) 

3. Open a new terminal and run below command in the directory where the .js code is saved: nodejs SDFC_lab.js
