# Full Ropsten Node Intaller and Runner
Automatically install and run a full Ropsten node on Ubuntu, with or without mining.

**NOTE:** This project is not part of the official Ethereum stack. This is a third-party script that makes it easier for you to run a full Ropsten testnet node.

## System Requirements

This script is tested on Ubuntu 21.04. It is likely to work with any Ubuntu 16.04 and older, as well as Linux Mint. Support of other distributions is planned for the future.

## Installation

Before using it for the first time, please install Ethereum using the following command:

```
./setup-ethereum.sh
```

The script will ask for the sudo password for installing Go-Ethereum.

## Usage

To start the node, use the following command:

```
./start-ropsten-full-node.sh
```

If you want to mine Ropsten Ether, use the following command instead:

```
./start-ropsten-full-node-with-mining.sh <ETHEREUM_ADDRESS>
```




