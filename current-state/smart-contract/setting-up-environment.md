# Setting Up Environment

### URL

[https://github.com/Institution-for-a-Global-Society/ongaeshi-nft-mgmt-smtcon.git](https://github.com/Institution-for-a-Global-Society/ongaeshi-nft-mgmt-smtcon.git)

### Clone Repo

```bash
$ git clone
```

### Installation

```bash
$ npm install
```

### Create local node

Use the SAMPLE-secrets.json file to create a secrets.json file

Add in the RPC and Private Key

```bash
# start the node
$ npx hardhat node

# run a script on localhost
$ npx hardhat run .\filename.js --network localhost
```

### Test

```bash
# run unit test
$ npx hardhat test.\filename.js --network localhost
```
