# Metapoo Staking Pool

## Overview
What is Metapoo and other non-Technical Documentation


## Technical Documentation

### Deploy program to the solana blockchain
1. Create a program keypair, save it to dist folder
    ```
    yarn keypair
    ```
2. Copy and paste pubkey to lib.rs
    ```
    declare_id!("set the program's public key");
    ```
3. Compile
    ```
    yarn build
    ```
4. Deploy
    ```
    yarn deploy
    ```
5. Generate IDL
    ```
    yarn idl
    ```

### Repositories 

This is the Smart Contract repository. The Web App UI is at https://github.com/Narwallets/metastaking-webapp


### Change Log
#### `0.1.0`

- Initial version based on core-contracts/lockup and core-contracts/staking-pool
- Deposit, withdraw
- Distributed stake/unstake
- Boost/Unboost NFT