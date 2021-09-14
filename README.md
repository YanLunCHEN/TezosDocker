# Tezos Docker

## Running

### Download Dockerfile

```
git clone https://github.com/AI080973/TezosNode-client.git 
```

### Make Docker Image

```
docker build -t tezos:lastest .
```

### Importing a snapshot

#### Step 1: Download FULL Testnet [snapshot](https://snapshots-tezos.giganode.io/) File

#### Step 2: Copy the snapshot-testnet.full file into container.
	
#### Step 3: RUN clear command(This command will remove all blockchain data.)
	
```
tezos clear
```
	
#### Step 4: RUN snapshot command
	
```
tezos snapshot import <FULLPATH>/snapshot.full

```
