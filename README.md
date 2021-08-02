# KsF Finance | KCC BLOCKS

Indexing all Kucoin Community Chain Blocks Data

## Converter Registry Contract

- [ConverterRegistryContract.sol](https://explorer.kcc.io/en/address/0x9dfba811a98a78aed3e39f8b303c7121ce9c2558)

#### Queries
```sh
{
  blocks(first: 5) {
    id
    number
    timestamp
    parentHash
  }
}
```

#### Running a Local Graph Node

```sh
yarn
yarn codegen
yarn create-local
yarn deploy-local
```
