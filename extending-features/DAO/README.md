Enabling Transport DAO with Sway Contracts powered by Fuel Labs

We are utilizing DAO implementation using Sway smart contracts mainly for Government organizations, who would only prefer to use DAO tooling for providing government subsidies for greener fuel and pollution check credits. Government organizations can send crypto from source-chain to destination-chain and distribute it equally among all accounts specified for subsidy or reimbursement using call contract with token. Cross chain lending platform: We can supply collateral and borrow tokens from a satellite chain to a fork of Ethereum's mainnet using existing Compound Protocol. Smart contracts for DAO enablement and extension using Sway contracts powered by Fuel Labs.

### Project

In order to run the subsequent commands change into the following directory `/path/to/DAO/project/<here>`.

#### Program compilation

```bash
forc build --locked
```

#### Running the tests

Before running the tests the programs must be compiled with the command above.

```bash
cargo test --locked
```
Reference: DAO example by Fuel Labs
