# IDDQD---Antelope-Godmode-Replay
Single Chain Testing Environment With Bios.Boot - contracts deployed including eosio.token - issued system currency, documentation keys used - atomicassets and markets deployed. 


Start - 

git clone https://github.com/mewmix/antelope-docker-minimal

##create image

 docker build --platform linux/amd64 antelope-docker-minimal


## run image

docker run --rm -it --platform linux/amd64 

## run nodeos snapshot single chain mode 

nodeos -e -p eosio --plugin eosio::chain_api_plugin --snapshot C0Iu6.bin

