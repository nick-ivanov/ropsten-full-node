# Full Ropsten Node Intaller and Runner
Automatically install and run a Ropsten full node on Ubuntu, with or without mining.

**NOTE:** This project is not part of the official Ethereum stack. This is a third-party script that automates deployment of a Ropsten testnet full node.

## System Requirements

This script is tested on Ubuntu 21.04, and it is likely to work with Ubuntu 16.04+, as well as Linux Mint. Support for other distributions is planned to be implemented in the future.

## Installation

Before using the full node scripts for the first time, please install Ethereum using the following command:

```
./setup-ethereum.sh
```

The script will ask for the sudo password in order to install Go-Ethereum.

## Usage

To start the node, use the following command:

```
./start-ropsten-full-node.sh
```

If you want to mine Ropsten Ether, use the following command instead:

```
./start-ropsten-full-node-with-mining.sh <ETHEREUM_ADDRESS>
```

where `<ETHEREUM_ADDRESS> is the etherbase address, i.e., the address where the mined Ethers will be deposited to.




