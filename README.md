# decent-docker // dcore
[docker image with decend 1.2.2 at docker-hub](https://hub.docker.com/r/yangwao/decent-docker/tags/)

# howto
### publictestnet
`docker pull yangwao/decent-docker:publictestnet-manual-1.2.2`

`docker-compose up publictestnet`

### mainnet - 1.2.2
`docker pull yangwao/decent-docker:production-manual4`

`docker-compose up mainnet`

### cli_wallet

`docker exec -it decent-docker_mainnet_1 bash`

#### wallet websocket rpc
`./cli_wallet --rpc-endpoint=0.0.0.0:8091`

#### wallet http rpc
`./cli_wallet --rpc-http-endpoint=0.0.0.0:8093`

#### http & websocket rpc
`./cli_wallet --rpc-endpoint=0.0.0.0:8091 --rpc-http-endpoint=0.0.0.0:8093`

#### connect to other daemon
`./cli_wallet --server-rpc-endpoint=ws://decent-docker_mainnet_1:8090`

### dcore documentation
https://docs.decent.ch/

### credits
credits goes to [https://github.com/Netherdrake/DECENT-docker](https://github.com/Netherdrake/DECENT-docker)
