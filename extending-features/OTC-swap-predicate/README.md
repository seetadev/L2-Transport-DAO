## Atomic Swaps of Crypto using Predicates in Fuel

We are extending and adapting the support of Predicates in Fuel for Transport DAO blockchain project to enable cross blockchain interoperability, atomic swaps and transaction management with Ethereum derived crypto, Filecoin/IPFS storage.

Predicates is a unique feature available in Fuel, which lets fleet organizations enable crypto to be send uniquely to an address representing a particular predicate's bytecode and thereby enable atomic swaps in Transport DAO tooling.

### Project

In order to run the subsequent commands change into the following directory `/path/to/OTC-swap-predicate/project/<here>`.

#### Program compilation

```bash
forc build --locked
```

#### Running the tests

Before running the tests the programs must be compiled with the command above.

```bash
cargo test --locked
```

References: OTC Swap Predicate example by Fuel labs