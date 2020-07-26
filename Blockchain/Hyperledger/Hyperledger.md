# Hyperledger

## Description

Hyperledger is an umbrella project of open source blockchains and related tools, started in December 2015 by the Linux Foundation, and has received contributions from IBM, Intel and SAP Ariba, to support the collaborative development of blockchain-based distributed ledgers

## Hyperledger resources

- ## White Papers

- [An Introduction to Hyperledger](https://www.hyperledger.org/wp-content/uploads/2018/08/HL_Whitepaper_IntroductiontoHyperledger.pdf)

- [Hyperledger Architecture: Volume 1](https://www.hyperledger.org/wp-content/uploads/2017/08/Hyperledger_Arch_WG_Paper_1_Consensus.pdf)

- [Hyperledger Architecture: Volume 2](https://www.hyperledger.org/wp-content/uploads/2018/04/Hyperledger_Arch_WG_Paper_2_SmartContracts.pdf)

## Hyperledger fabric

## The Hyperledger Fabric Install Guide

### Environment

Ubuntu 16.04 AWS instance.

### Install Fabric 1.0

Please go through the documents first to get a better understanding:

- https://domsteil.com/2017/04/22/how-to-setup-hyperledger-fabric-v1-0-on-aws/

- https://wiki.hyperledger.org/groups/twgc/fabric-doc/getting_started.md

The command sequence to install Hyperledger Fabric v1.0.0-beta:

```

$ sudo apt-get update

$ sudo apt install libtool libltdl-dev git

```

```

$ cd $GOPATH

$ mkdir src

$ cd src

$ mkdir github.com

$ cd github.com

$ mkdir hyperledger

$ cd hyperledger

