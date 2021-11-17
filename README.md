# heco-metabulls-contract
Contract for Metabulls

```sh
npm install -g truffle

```
Clone OpenBazaar-SmartContracts

```sh
git clone https://github.com/azimpremji/heco-metabulls-contract.git
cd heco-metabulls-contract
npm i
```

Compile and Deploy
------------------
These commands apply to the RPC provider running on port 8545. You may want to have TestRPC running in the background. They are really wrappers around the [corresponding Truffle commands](http://truffleframework.com/docs/advanced/commands).

### Compile all contracts to obtain ABI and bytecode:

```bash
npm run compile
```

### Migrate all contracts required for the basic framework onto network associated with RPC provider:

```bash
npm run migrate
```
Network Artifacts
-----------------

### Show the deployed addresses of all contracts on all networks:

```bash
npm run networks
```

Testing
-------------------
### Run all tests (requires Node version >=8 for `async/await`, and will automatically run TestRPC in the background):

```bash
npm test
```

Test Coverage
-------------------
### Get test coverage stats(requires Node version >=8 for `async/await`, and will automatically run TestRPC in the background):

```bash
npm run coverage
```

License
-------------------
MetaBulls smart contracts are released under the [MIT License](LICENSE).
