## Set a private key for Demo
1. Generate a new address and print its private key with `-p` (for mainnet, append `-n mainnet`):
```
$ ./index address -p
private key: 055b3b79ed1621f1adfb8e9970b2bd2e2f5986a1fbd48938f18ef81c0f05a8ca
tgrs1qnxysxxrlnzc5ds6lg4l9j0sef2apn6gc58ax6m
```
2. Set the environment variable with the above private key:
```
$ export PRIVATE_KEY=055b3b79ed1621f1adfb8e9970b2bd2e2f5986a1fbd48938f18ef81c0f05a8ca
```
3. Send some balance to the address printed above (0.001 should be enough).
For testnet, you can use [this faucet](https://coinfaucet.eu/en/grs-testnet/).
