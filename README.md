# For-top-100-nodes
<h1 align=center> If you want to keep your old-eth-mainnet-node use this steps-no gas-needed </h1>


>If your node is down already, follow this steps to make it online back, without paying any gas fee </h1>

#Firstly, be sure that, you back up your "peer-id.json" file (thats located in root/quickstart-archaeologist and old version ".env" (we will use it for some info) 

#Lets clean the old files first and start to set up
```console
cd && rm -rf quickstart-archaeologist

git clone https://github.com/sarcophagus-org/quickstart-archaeologist && cd quickstart-archaeologist

cp .env.sample .env
```
#Now, we have a new version of ".env" file, we will fill it with our old info and there is some new settings in it. we will use etherium mainnet and we should pick chain id as "1"

#Another diffirence is, we were using http connection before, now we will use wss connection. You should go to your provider (like infura,alch...) and get the eth-mainnet "web socket" url. like wss.mainnet.infura/ws/v3...



