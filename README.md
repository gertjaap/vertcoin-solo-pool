Vertcoin Solo Pool
================

Simple, fast Stratum-compatible Vertcoin pool for solo mining.

Please note that this is a Stratum mining pool intended for *solo* usage - shares are not tracked, and there is no payment handling. You will need to run a dedicated instance of the Vertcoin daemon.

Features
--------

- Efficient, configurable variable-difficulty Stratum implementation using [node-stratum-pool](https://github.com/zone117x/node-stratum-pool)
- Automatic coinbase address switching (sets a new address for each block mined)
- Worker connect/disconnect, share submittal, block submittal, mean ten-minute hashrate logging


