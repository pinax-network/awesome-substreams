![awesome-substreams](https://user-images.githubusercontent.com/550895/217890452-86ae6388-6570-4393-8d82-cedf5e783e0e.png)

<!-- omit from toc -->
# Awesome Substreams [![awesome-badge](https://awesome.re/badge-flat.svg)](https://awesome.re) [![LICENSE](https://img.shields.io/github/license/pinax-network/awesome-substreams?color=blue)](LICENSE)

Carefully curated list of awesome Substreams resources. **If you find the list helpful, please make sure to ⭐ star it!**

Substreams is a powerful blockchain indexing technology, developed for **The Graph** Network.

> Substreams enables developers to write Rust modules, composing data streams alongside the community, and provides extremely high-performance indexing by virtue of parallelization, in a streaming-first fashion.

<!-- omit from toc -->
## Contents

- [Technology](#technology)
- [Articles](#articles)
- [Videos](#videos)
- [Twitter](#twitter)
  - [Protocols](#protocols)
  - [Companies](#companies)
  - [Core Contributors](#core-contributors)
  - [Community Advocates](#community-advocates)
- [Blockchains](#blockchains)
  - [Substreams](#substreams)
  - [Firehose](#firehose)
- [Sinks](#sinks)
- [Substreams Tools](#substreams-tools)
- [Substreams Examples](#substreams-examples)
- [Learning Rust](#learning-rust)
- [SDK](#sdk)
  - [Rust](#rust)
  - [Python](#python)
  - [JavaScript](#javascript)
  - [Golang](#golang)
- [Endpoints](#endpoints)
- [Protobuf](#protobuf)
  - [Blocks](#blocks)
  - [Sinks](#sinks)

## Technology

- [Substreams Documentation](https://substreams.streamingfast.io) - Substreams is a powerful blockchain indexing technology, developed for The Graph Network.
- [Substreams Glossary](https://substreams.streamingfast.io/quick-access/glossary)
- [Firehose Documentation](https://firehose.streamingfast.io) - Firehose provides a files-based and streaming-first approach to processing blockchain data.
- [The Graph](https://thegraph.com/) - The Graph is an indexing protocol for querying networks like Ethereum and IPFS.

## Articles

> Articles related or describing to Substreams

- [Parallel Indexing Of Blockchain Data With Substreams](https://messari.notion.site/Parallel-Indexing-Of-Blockchain-Data-With-Substreams-28e1da982a54459b9f928e88777aea9b)
- [Substreams: Massively Faster Indexing Performance for Subgraphs](https://thegraph.com/blog/substreams-parallel-processing/)
- [Substreams: Unlocking Lightning-Fast Indexing of Blockchain Data](https://subgraphdev.hashnode.dev/substreams-unlocking-lightning-fast-indexing-of-blockchain-data)
- [Tips and Tricks for Developing Substreams](https://streamingfastio.medium.com/tips-and-tricks-for-developing-substreams-94cfc4cacbaa)
- [Unveiling Substreams.dev: A comprehensive hub to discover, build, deploy, and share Substreams  ](https://streamingfastio.medium.com/unveiling-substreams-dev-a-comprehensive-hub-to-discover-build-deploy-and-share-substreams-2545c758200e)

## Videos

![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)

> Video content related to Substreams

- [Indexing Improvements via Substreams by Sebastian Siemssen](https://www.youtube.com/watch?v=Nn6k7A-TjVE)
- [Introducing Substreams by Alexandre Bourget](https://www.youtube.com/watch?v=qWxffTKpciU)
- [Introducing The Graph Substreams for High-Performance Indexing by Alexandre Bourget
](https://www.youtube.com/watch?v=K-nhC2FCB5k&t=506s)
- [Advocating for Firehose and Substreams by Matthew Darwin of Pinax](https://youtu.be/dzCbJ2fpckA)
- [Substreams and Subgraph Quickstart by Yaro Shkvorets of Pinax](https://www.youtube.com/watch?v=sLXbMKeWKM4)
- [How Substreams Unlock High-Speed, Composable Indexing](https://youtu.be/rGkS4D97aFE?si=4weE9rMi7AyAbpW5)
- House of Web3
  - [Substreams Demystified: A Practitioner's Guide to High-Performance Blockchain Indexing (Soulbound Labs)](https://www.youtube.com/watch?v=fogh2D-vpzg)
- Substreams Unleashed Demo Series
  - [Substreams for Google Sheets with Étienne Donneger](https://youtu.be/fwLLolKvjHs)
  - [Substreams powered open-source NFT Hub with Mathieu Lefebvre](https://youtu.be/oIgYJxwAihs)
  - [Introducing the Substreams-Sink-Library with Charles Morin](https://youtu.be/DZ_0Mt49OLo)
  - [Substream Sink Library: Revolutionizing Data Routing with Charles Morin](https://www.youtube.com/watch?v=OIwcN8TL5d4)
  - [DappLooker: Pioneering Substreams for Cutting-Edge Blockchain Analytics](https://youtu.be/hMe99qR_cqE?si=7dx0CtcQCedNmbnE)
  - [Spyglass Analytics Unleashing the Power of Substreams](https://youtu.be/iGEfhpLl66A?si=q2YPs7kGaasWZFtj)
- StreamingFast Substreams Tutorials
  - [Substreams Tutorial - Understanding Substreams ](https://youtu.be/gVqGCqKVM08?si=MwWZlKpGU2MYj2sq)
  - [Substreams Tutorial - Sink events from an Ethereum smart contract to an SQL database](https://youtu.be/QbV3DFzKkdM?si=Ik59Trt1IM0QL8YH)


## Twitter

![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)

> Twitter accounts related to Substreams technology

### Protocols

- [The Graph Protocol](https://twitter.com/graphprotocol) - The Graph is a web3 protocol for organizing and accessing blockchain data 🧑‍🚀 Official account of The Graph ecosystem 🌐.

### Companies

- [StreamingFast](https://twitter.com/streamingfastio) - web3 builders & investors. Building massively scalable architecture for streaming blockchain data.
- [Pinax](https://twitter.com/PinaxNetwork) - Unleashing the power of blockchain data.
- [Messari](https://twitter.com/MessariCrypto) - Messari is the leading provider of crypto market intelligence products that help professionals navigate crypto with confidence.
- [GraphOps](https://twitter.com/graphopsxyz) - GraphOps is a blockchain data infrastructure company. We extract, transform and serve blockchain data via The Graph.
- [Semiotic Labs](https://twitter.com/semioticlabs) - The Graph core dev team. Creators of [ODOS](https://twitter.com/odosprotocol). We specialize in AI/ML, zk-SNARKs, Cryptographic Engineering, and Blockchain Infrastructure.
- [Geo Browser](https://twitter.com/geobrowser) - A web3 browser and knowledge graph app built on The Graph protocol.
- [House of Web3](https://twitter.com/thehouseofweb3) - For web3 pioneers and those who contribute knowledge, education, and code to the community at large.
- [Spyglass Pirate Collective](https://spygpc.com) - Delightfully simple web3 analytics powered by substreams.

### Core Contributors

- [Alexandre Bourget](https://twitter.com/bourgetalexndre) - Co-Founder and CTO at **StreamingFast**.
- [Matthew Darwin](https://twitter.com/matthewdarwin) - Co-Founder and CIO at **Pinax**.
- [Brandon Ramirez](https://twitter.com/RezBrandon) - Co-Founder of Graph and prior Edge & Node CEO.
- [Eva Beylin](https://twitter.com/evabeylin) - pilot **The Graph** foundation 👩‍🚀.
- [Yaniv Tal](https://twitter.com/yanivgraph) - Founder & CEO **Geo**. Cofounder **The Graph**, **Edge & Node** & **House of Web3**. Building a vibrant decentralized future.
- [Tegan Kline](https://twitter.com/theklineventure) - Co-Founder and CEO **Edge & Node**, Launched **The Graph** | Ex **Barclays** & BAML.

### Community Advocates

- [GraphAdvocatesDAO](https://twitter.com/GraphAdvocates) - A DAO driving **The Graph** ecosystem growth via community grants & Graph Advocates Program.
- [GRTiQ](https://twitter.com/grt_iq) - 🎙 Weekly podcast that interviews the people building Web3 & **The Graph**.
- [Graphtronauts](https://twitter.com/graphtronauts) - #GRT #web3 #GRTFAM #TheGraph Independent Community Group.
- [Graphtronauts Indexer](https://twitter.com/graphtronauts_x) - Graphtronauts is the largest community for long term GRT holders who believe in The Graph's web3 vision for the future 👨‍🚀.
- [Kyle LaRue](https://twitter.com/KyleLaRue11) - Graph Advocate, produces The Graph Advocates Spotlight as a newsletter.
- [Paolo Diomede](https://twitter.com/pdiomede) - Graph Advocate, Graphtronauts admin, community figure.
- [Andy S](https://twitter.com/German_TheGraph) - Graph Advocate, involved in multiple International communities.
- [Abhay | dapplooker.eth](https://twitter.com/abhayait) - Dapplooker is a growing indexer and active in the community.
- [Derek | DataNexus](https://twitter.com/datanexus) - One of the most active indexers, and a stable community resource.
- [Jim Cousins](https://twitter.com/cryptovestor) - Runs WaveFive indexer, excellent community “conscience”.
- [Chidubem](https://twitter.com/chidubemw3) - Graph Advocate in Africa, produces Graph Central, active in Advocates DAO.
- [jimxjim.eth](https://twitter.com/jim74255) - Graph Advocate in Africa, very active in the DAO.
- [Tony Kipkemboi](https://twitter.com/tonykipkemboi) - Graph Advocate, New Jersey/Kenya.
- [Christina Mills](https://twitter.com/bombayonchain) - AdvocatesDAO director.
- [GRTDataHub](https://twitter.com/GRTCrypto) - Produces most the stats graphics used across the community, Graphtronaut.
- [Paulieb.eth](https://twitter.com/PaulBarba12) - Active in many community sectors, Graphtronaut.
- [Nick Hansen](https://twitter.com/TwentyTwoNode) - Ecosystem manager at the Foundation, GRTiQ.
- [Kyle Rojas](https://twitter.com/KyleArojas) - Business Dev E&N.
- [Pranav Maheshwari](https://twitter.com/impranavm) - Dev Rel & everything else.
- [Graphrica](https://twitter.com/graphrica) - Graph community in Africa.
- [Ujjwal Thakur](https://twitter.com/subgraphdev) -  Graph Advocate,  Education & Training Lead   [The Graph India](https://twitter.com/TheGraphIndia)

## Blockchains

> Blockchains that support (official & no-official) Substreams/Firehose technology.

### Substreams

- [Substreams Ethereum](https://github.com/streamingfast/substreams-ethereum) - Substreams development kit for Ethereum chains, contains Firehose Block model and helpers as well as utilities for Ethereum ABI encoding/decoding.
- [Substreams Antelope](https://github.com/pinax-network/substreams-antelope) - This library contains the generated protobuffer for the Antelope blocks as well as helper methods to extract and parse block data.

### Firehose

- [Firehose Overview](https://firehose.streamingfast.io/introduction/firehose-overview)
- [Firehose Ethereum](https://github.com/streamingfast/firehose-ethereum)
- [Firehose Near](https://github.com/streamingfast/firehose-near)
- [Firehose Aptos](https://github.com/streamingfast/firehose-aptos)
- [Firehose Arweave](https://github.com/streamingfast/firehose-arweave) - use `thegarii` as source (The Graph Arweave Integration Implementation).
- [Firehose Solana](https://github.com/streamingfast/firehose-solana)
- [Firehose Cosmos](https://github.com/graphprotocol/firehose-cosmos)
- [Firehose Sui](https://github.com/ticketland-io/sui-sf-indexer)

## Substreams Sinks

> Substreams Sinks typically written in GoLang or Node.js

- [Prometheus Sink](https://github.com/pinax-network/substreams-sink-prometheus)
- [MongoDB Sink](https://github.com/streamingfast/substreams-sink-mongodb)
- [PostgreSQL Sink](https://github.com/streamingfast/substreams-sink-postgres)
- [ClickHouse Sink](https://github.com/aleno-ai/substreams-sink-clickhouse)
- [Files Sink](https://github.com/streamingfast/substreams-sink-files) - Binary application to consume your Substreams and output it's data out to files format (JSON, CSV, etc.).
- [CSV Sink](https://github.com/pinax-network/substreams-sink-csv) - CSV sink module.
- [Winston Sink](https://github.com/pinax-network/substreams-sink-winston) - Logger sink module.
- [Discord Sink](https://github.com/pinax-network/substreams-sink-discord)
- [Telegram Sink](https://github.com/pinax-network/substreams-sink-telegram)
- [Slack Sink](https://github.com/pinax-network/substreams-sink-slack)

## Substreams Tools

> Tools related to Substreams

- [Substreams Browser](https://substreams.vercel.app/) - Substreams Browser is a tool to help you explore the Substreams data.
- [Substreams Registry](https://substreams.dev/) - Substreams registry contains a list of useful Substreams.

## Substreams Examples

> Substreams code examples written in Rust

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
  - [ETH Block Meta](https://github.com/streamingfast/substreams-eth-block-meta)
  - [PancakeSwap Substreams](https://github.com/streamingfast/substreams-playground/tree/master/modules/pancakeswap)
  - [ETH Token Substreams](https://github.com/streamingfast/substreams-playground/tree/master/modules/eth-token)
  - [Solana SPL Tokens](https://github.com/streamingfast/substreams-playground/tree/master/modules/sol-spl-tokens)
  - [Uniswap](https://github.com/streamingfast/substreams-playground/tree/master/modules/uniswap)
  - [Example substreams consumers (Go, JavaScript, Python, Rust)](https://github.com/streamingfast/substreams-playground/tree/master/consumers)
- [BuildersDAO Substreams](https://github.com/Graph-BuildersDAO/substreams)
  - [Chainlink Prices](https://github.com/Graph-BuildersDAO/substreams/tree/master/chainlink-prices)
  - [ERC1155](https://github.com/Graph-BuildersDAO/substreams/tree/master/erc1155)

## Learning Rust

- [Rustlings - 🦀 Small exercises to get you used to reading and writing Rust code!](https://rustlings.cool/)
- [Effective Rust - 35 Specific Ways to Improve Your Rust Code](https://www.lurklurk.org/effective-rust/)
- [Rust Lang Book](https://doc.rust-lang.org/book/foreword.html)
- [Rust Tutorial #1 - Introduction To Rust Programming](https://www.youtube.com/watch?v=T_KrYLW4jw8&list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ)
- [No Boilerplate - Fast technical videos](https://www.youtube.com/@NoBoilerplate)

## SDK

> Software Development Kit related to Substreams

### Rust

![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)

> Rust libraries related to Substreams

- [Substreams Rust](https://github.com/streamingfast/substreams-rs) - Substreams is a powerful blockchain indexing technology, developed for The Graph Network.
- [Antelope Rust](https://github.com/pinax-network/antelope.rs) - Antelope Standard Library for Rust.
- [Substreams Solana](https://github.com/streamingfast/substreams-solana) - Substreams development kit for Solana chains, contains Rust Firehose Block model and helpers.

### Python

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

> Python libraries related to Substreams

- [substreams_firehose](https://github.com/pinax-network/substreams_firehose) - Extract any data from the blockchain using gRPC-enabled endpoints (powered by **Firehose** and **Substreams**).
- [substreams-python](https://github.com/messari/substreams-python) - WIP Python Interface for querying via substreams.

### JavaScript

![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=JavaScript&logoColor=%23F7DF1E)

> JavaScript libraries related to Substreams

- [Substreams JS](https://github.com/pinax-network/substreams-js) - Substream JavaScript consumer library using Node.js Event emitters.
- [substreams-sink](https://github.com/pinax-network/substreams-sink) - JavaScript/TypeScript toolset to facilitate substreams sink development.

### Golang

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)

> Golang libraries related to Substreams

- [Substreams Sink (Golang)](https://github.com/streamingfast/substreams-sink)

## Endpoints

> Operator's endpoints & chains that support Substreams.

- [StreamingFast endpoints](https://substreams.streamingfast.io/reference-and-specs/chains-and-endpoints#endpoints) - Ethereum, Polygon, BNB, Near, Solana, Arweave, Aptos.

## Protobuf

> Substreams commonly used Protobuf messages

### Blocks

- [Ethereum](https://ethereum.org/) - [`sf.ethereum.type.v2.Block`](https://github.com/streamingfast/firehose-ethereum/blob/develop/proto/sf/ethereum/type/v2/type.proto)
- [​​NEAR](https://near.org/) - [`sf.near.type.v1.Block`](https://github.com/streamingfast/firehose-near/blob/develop/proto/sf/near/type/v1/type.proto)
- [​​Solana](https://solana.com/) - [`sf.solana.type.v1.Block`](https://github.com/streamingfast/firehose-solana/blob/develop/proto/sf/solana/type/v1/type.proto)
- [​​Cosmos](https://cosmos.network/) - [`sf.cosmos.type.v1.Block`](https://github.com/figment-networks/proto-cosmos/blob/main/sf/cosmos/type/v1/type.proto)
- [​​Arweave](https://www.arweave.org/) - [`sf.arweave.type.v1.Block`](https://github.com/streamingfast/firehose-arweave/blob/develop/proto/sf/arweave/type/v1/type.proto)
- [​​Aptos](https://aptoslabs.com/) - [`aptos.extractor.v1.Block`](https://github.com/aptos-labs/aptos-core/blob/main/crates/aptos-protos/proto/aptos/extractor/v1/extractor.proto)

### Sinks

- [EntityChanges](https://github.com/streamingfast/substreams-entity-change) - [`sf.substreams.entity.v1`](https://github.com/streamingfast/substreams-entity-change/blob/develop/proto/sf/substreams/entity/v1/entity.proto)
- [DatabaseChanges](https://github.com/streamingfast/substreams-database-change) - [`sf.substreams.sink.database.v1`](https://github.com/streamingfast/substreams-database-change/blob/develop/proto/substreams/sink/database/v1/database.proto)
- [KVOperations](https://github.com/streamingfast/substreams-sink-kv) - [`sf.substreams.sink.kv.v1`](https://github.com/streamingfast/substreams-sink-kv/blob/develop/proto/substreams/sink/kv/v1/kv.proto)
- [PrometheusOperations](https://github.com/pinax-network/substreams-sink-prometheus.rs) - [`sf.substreams.sink.prometheus.v1`](https://github.com/pinax-network/substreams-sink-prometheus.rs/blob/main/proto/substreams/sink/prometheus/v1/prometheus.proto)
- [`soulbound_modules` - Hotdog Powered 🌭](https://github.com/MercuricChloride/substreams_module_repo)
