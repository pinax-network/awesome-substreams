![awesome-substreams](https://user-images.githubusercontent.com/550895/217890452-86ae6388-6570-4393-8d82-cedf5e783e0e.png)
[![awesome-badge](https://awesome.re/badge-flat.svg)](https://awesome.re)

<!-- omit from toc -->
## Contents

- [Technology](#technology)
- [Articles](#articles)
- [Sinks](#sinks)
- [Protobuf](#protobuf)
- [Substreams](#substreams)
- [Videos](#videos)
- [Twitter](#twitter)
- [SDK](#sdk)
  - [Rust](#rust)
  - [Python](#python)
  - [Javascript](#javascript)
  - [Golang](#golang)

## Technology

- [Substreams Documentation](https://substreams.streamingfast.io) - Substreams is a powerful blockchain indexing technology, developed for The Graph Network.
- [Firehose Documentation](https://firehose.streamingfast.io) - Firehose provides a files-based and streaming-first approach to processing blockchain data.
- [The Graph](https://thegraph.com/) - The Graph is an indexing protocol for querying networks like Ethereum and IPFS.

**[back to top](#contents)**

## Articles

 *Articles related or describing to Substreams*

- [Parallel Indexing Of Blockchain Data With Substreams](https://messari.notion.site/Parallel-Indexing-Of-Blockchain-Data-With-Substreams-28e1da982a54459b9f928e88777aea9b)
- [Substreams: Massively Faster Indexing Performance for Subgraphs](https://thegraph.com/blog/substreams-parallel-processing/)

**[back to top](#contents)**

## Sinks

 *Substreams Sinks typically written in GoLang*

- [Prometheus Sink](https://github.com/pinax-network/substreams-sink-prometheus)
- [MongoDB Sink](https://github.com/streamingfast/substreams-sink-mongodb)
- [PostgreSQL Sink](https://github.com/streamingfast/substreams-sink-postgres)
- [Files Sink](https://github.com/streamingfast/substreams-sink-files) - Binary application to consume your Substreams and output it's data out to files format (JSON, CSV, etc.)

**[back to top](#contents)**

## Protobuf

 *Substreams commonly used Protobuf messages*

- [DatabaseChanges](https://github.com/streamingfast/substreams-database-change/blob/develop/proto/substreams/sink/database/v1/database.proto)
- [KVOperations](https://github.com/streamingfast/substreams-sink-kv/blob/main/proto/substreams/sink/kv/v1/kv.proto)
- [PrometheusOperations](https://github.com/pinax-network/substreams-sink-prometheus/blob/main/proto/substreams/sink/prometheus/v1/prometheus.proto)

**[back to top](#contents)**

## Substreams

 *Substreams code examples written in Rust*

- [Messari Substreams](https://github.com/messari/substreams)
  - [Compound V2](https://github.com/messari/substreams/tree/master/compound-v2)
  - [ENS](https://github.com/messari/substreams/tree/master/ens-names)
  - [ERC20](https://github.com/messari/substreams/tree/master/erc20-holdings)
  - [ERC721](https://github.com/messari/substreams/tree/master/erc721)
  - [ETH Balance](https://github.com/messari/substreams/tree/master/eth-balance)
  - [Uniswap V2](https://github.com/messari/substreams/tree/master/uniswap-v2)
- [Pinax Substreams](https://github.com/pinax-network/substreams)
  - [eosio.ibc](https://github.com/pinax-network/substreams/tree/develop/eosio.ibc)
  - [eosio.token](https://github.com/pinax-network/substreams/tree/develop/eosio.token)
  - [accounts](https://github.com/pinax-network/substreams/tree/develop/accounts)
  - [eosmechanics](https://github.com/pinax-network/substreams/tree/develop/eosmechanics)
- [StreamingFast Substreams](https://github.com/streamingfast/substreams-playground)
  - [PancakeSwap Substreams](https://github.com/streamingfast/substreams-playground/tree/master/modules/pancakeswap)
  - [ETH Token Substreams](https://github.com/streamingfast/substreams-playground/tree/master/modules/eth-token)
  - [Solana SPL Tokens](https://github.com/streamingfast/substreams-playground/tree/master/modules/sol-spl-tokens)
  - [Uniswap](https://github.com/streamingfast/substreams-playground/tree/master/modules/uniswap)

**[back to top](#contents)**

## Videos

 *Video content related to Substreams*

- [Indexing Improvements via Substreams by Sebastian Siemssen](https://www.youtube.com/watch?v=Nn6k7A-TjVE)
- [Introducing Substreams by Alexandre Bourget](https://www.youtube.com/watch?v=qWxffTKpciU)
- [Introducing The Graph Substreams for High-Performance Indexing by Alexandre Bourget
](https://www.youtube.com/watch?v=K-nhC2FCB5k&t=506s)

**[back to top](#contents)**

## Twitter

 *Twitter accounts related to Substreams technology*

- [The Graph Protocol](https://twitter.com/graphprotocol) - The Graph is a web3 protocol for organizing and accessing blockchain data 🧑‍🚀 Official account of The Graph ecosystem 🌐
- [StreamingFast](https://twitter.com/streamingfastio) - web3 builders & investors. Building massively scalable architecture for streaming blockchain data.
- [Pinax](https://twitter.com/PinaxNetwork) - Unleashing the power of blockchain data.
- [Messari](https://twitter.com/MessariCrypto) - Messari is the leading provider of crypto market intelligence products that help professionals navigate crypto with confidence.
- [Alexandre Bourget](https://twitter.com/bourgetalexndre) - Co-Founder and CTO at [StreamingFast](http://StreamingFast.io)
- [Matthew Darwin](https://twitter.com/matthewdarwin) - Co-Founder and CIO at [Pinax](https://pinax.network/)

**[back to top](#contents)**

## SDK

 *Software Development Kit related to Substreams*

### Rust

 *Rust libraries related to Substreams*

- [Substreams Rust](https://github.com/streamingfast/substreams-rs) - Substreams is a powerful blockchain indexing technology, developed for The Graph Network.
- [Substreams for Antelope](https://github.com/pinax-network/substreams-antelope) - This library contains the generated protobuffer for the Antelope blocks as well as helper methods to extract and parse block data.
- [Antelope Rust](https://github.com/pinax-network/antelope.rs) - Antelope Standard Library for Rust.

**[back to top](#contents)**

### Python

 *Python libraries related to Substreams*

- [PyFirehose](https://github.com/pinax-network/pyfirehose) - Extract bulk and targeted historical blockchain data (powered by Firehose and Substreams)

**[back to top](#contents)**

### Javascript

 *Javascript libraries related to Substreams*

- [Substreams JS](https://github.com/pinax-network/substreams-js) - Substream Javascript consumer library using Node.js Event emitters.

**[back to top](#contents)**

### Golang

 *Golang libraries related to Substreams*

- [Substreams Sink (Golang)](https://github.com/streamingfast/substreams-sink)

**[back to top](#contents)**
