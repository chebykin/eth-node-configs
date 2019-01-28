# AuRa Dev Chain

## Reason
Sometimes it's useful to run your contract tests not only on a ganache/testrpc chain, but on a production implementation such as `Parity` or `Geth` too, since Truffle doesn't work well with instant sealing mode provided by `parity --chain dev` config.

This is a private chain config with Authority Round consensus and a single sealing node.

## How to run it

1. Install `Parity` https://wiki.parity.io/Setup

2. Clone this repo and run

```sh
make
```

## Credentials
```
The private keys are exposed to anyone. Use them only for testing purposes.
```

### Validator (Miner)

* Private: 319af6dec0d3c80fbb9963e6a7f42ed3f2758583e580d2ac3dbfb6abc4256b4a
* Address: a5aa6d3dce7e88059adedee8c32b8f80e54cd404

### Account 1

* Private: 0a58547a2fbacebf13d777bdc3e4a21cdb48618467ef6bec195f24623138631c
* Address: 2ab9f5132bf6b0718542955c88efa47b4139605f

### Account 2

* Private: 9af7c3dc38c59db65044bb6f37362a7110fcf1f7c35e92394e59c20930cfcd29
* Address: 9411816ffd9f1ca99712a976c8d87605e2cc27b1

### Account 3

* Private: 26e044ab4c159aca7c4520f0827b7e130fcc57d2e3736e1f7eef0e4bc89b1071
* Address: 254fccb0603859f096be3151b10ec4337b4fec57
