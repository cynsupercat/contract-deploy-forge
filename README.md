## How to use

`forge build`

Deploying:

```
forge create --rpc-url https://rpc.testnet.immutable.com --private-key $PRIVATE_KEY src/Other.sol:Other --legacy
```

Verifying:

```
forge verify-contract --compiler-version "0.8.19+commit.7dd6d404" --etherscan-api-key $ETHERSCAN_API_KEY --verifier-url https://explorer.testnet.immutable.com/api\? <CONTRACT_AADRESS> src/Other.sol:Other
```