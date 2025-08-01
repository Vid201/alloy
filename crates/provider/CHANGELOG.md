# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.13](https://github.com/alloy-rs/alloy/releases/tag/v1.0.13) - 2025-06-26

### Documentation

- Fix typo in comments ([#2611](https://github.com/alloy-rs/alloy/issues/2611))

## [1.0.12](https://github.com/alloy-rs/alloy/releases/tag/v1.0.12) - 2025-06-18

### Features

- [provider] Conversion between `MulticallItem` and `CallItem` ([#2589](https://github.com/alloy-rs/alloy/issues/2589))

### Miscellaneous Tasks

- Release 1.0.12
- Release 1.0.11

### Other

- Added overrides_opt fn ([#2595](https://github.com/alloy-rs/alloy/issues/2595))

## [1.0.10](https://github.com/alloy-rs/alloy/releases/tag/v1.0.10) - 2025-06-17

### Bug Fixes

- The bundle hash is null on root level, not the value ([#2588](https://github.com/alloy-rs/alloy/issues/2588))
- ERC20 endpoints return type ([#2577](https://github.com/alloy-rs/alloy/issues/2577))
- Make pollers and `Heartbeat` more reliable ([#2540](https://github.com/alloy-rs/alloy/issues/2540))

### Dependencies

- Bump MSRV to 1.85 ([#2547](https://github.com/alloy-rs/alloy/issues/2547))

### Features

- [provider] Add eth_sendBundle support to provider ([#2556](https://github.com/alloy-rs/alloy/issues/2556))
- [provider] Add block_number_for_id helper method ([#2581](https://github.com/alloy-rs/alloy/issues/2581))
- [provider] Add setERC20Allowance endpoint ([#2574](https://github.com/alloy-rs/alloy/issues/2574))
- Added missing blockoverrides setter ([#2559](https://github.com/alloy-rs/alloy/issues/2559))

### Miscellaneous Tasks

- Release 1.0.10
- Release 1.0.10
- Add anvil_dealerc20 ([#2558](https://github.com/alloy-rs/alloy/issues/2558))
- [rpc] `eth_sendBundle` allow hex and integer for input and output always integer ([#2553](https://github.com/alloy-rs/alloy/issues/2553))

### Other

- Improve mock transport error messages ([#2536](https://github.com/alloy-rs/alloy/issues/2536))

## [1.0.9](https://github.com/alloy-rs/alloy/releases/tag/v1.0.9) - 2025-05-28

### Miscellaneous Tasks

- Release 1.0.9

## [1.0.8](https://github.com/alloy-rs/alloy/releases/tag/v1.0.8) - 2025-05-27

### Bug Fixes

- [provider] CacheLayer - Add block_id to RequestType::params_hash() ([#2512](https://github.com/alloy-rs/alloy/issues/2512))

### Documentation

- [provider] Use multicall.dynamic() in more places ([#2508](https://github.com/alloy-rs/alloy/issues/2508))
- Rm redundant ref ([#2502](https://github.com/alloy-rs/alloy/issues/2502))
- Unhide `SendableTx` ([#2501](https://github.com/alloy-rs/alloy/issues/2501))

### Features

- Empty MulticallBuilder into dynamic ([#2507](https://github.com/alloy-rs/alloy/issues/2507))

### Miscellaneous Tasks

- Release 1.0.8

## [1.0.7](https://github.com/alloy-rs/alloy/releases/tag/v1.0.7) - 2025-05-24

### Features

- Introducing BlockOverrides support to EthCallParams ([#2493](https://github.com/alloy-rs/alloy/issues/2493))
- Add option to always set input+data in MulticallBuilder ([#2491](https://github.com/alloy-rs/alloy/issues/2491))

### Miscellaneous Tasks

- Release 1.0.7

## [1.0.6](https://github.com/alloy-rs/alloy/releases/tag/v1.0.6) - 2025-05-21

### Bug Fixes

- Correctly handle websocket subscription to new blocks ([#2482](https://github.com/alloy-rs/alloy/issues/2482))

### Miscellaneous Tasks

- Release 1.0.6

## [1.0.5](https://github.com/alloy-rs/alloy/releases/tag/v1.0.5) - 2025-05-20

### Bug Fixes

- [`provider`] Introduce `new_with_network` constructor ([#2479](https://github.com/alloy-rs/alloy/issues/2479))

### Miscellaneous Tasks

- Release 1.0.5

## [1.0.4](https://github.com/alloy-rs/alloy/releases/tag/v1.0.4) - 2025-05-19

### Miscellaneous Tasks

- Release 1.0.4
- Warn missing-const-for-fn ([#2418](https://github.com/alloy-rs/alloy/issues/2418))
- Rm leftover recovery impl ([#2467](https://github.com/alloy-rs/alloy/issues/2467))

## [1.0.3](https://github.com/alloy-rs/alloy/releases/tag/v1.0.3) - 2025-05-15

### Miscellaneous Tasks

- Release 1.0.3 ([#2460](https://github.com/alloy-rs/alloy/issues/2460))
- Release 1.0.2

## [1.0.1](https://github.com/alloy-rs/alloy/releases/tag/v1.0.1) - 2025-05-13

### Miscellaneous Tasks

- Release 1.0.1

### Other

- Revert "feat(`provider`)!: `Fillers` tuple ([#2261](https://github.com/alloy-rs/alloy/issues/2261))" ([#2443](https://github.com/alloy-rs/alloy/issues/2443))

## [1.0.0](https://github.com/alloy-rs/alloy/releases/tag/v1.0.0) - 2025-05-13

### Dependencies

- Bump jsonrpsee ([#2437](https://github.com/alloy-rs/alloy/issues/2437))

### Documentation

- Update alloy-provider README with links and usage example ([#2319](https://github.com/alloy-rs/alloy/issues/2319))
- [provider] Add usage examples to provider README ([#2313](https://github.com/alloy-rs/alloy/issues/2313))

### Features

- [`provider`] `Fillers` tuple ([#2261](https://github.com/alloy-rs/alloy/issues/2261))

### Miscellaneous Tasks

- Release 1.0.0
- Fix warnings ([#2441](https://github.com/alloy-rs/alloy/issues/2441))

## [0.15.11](https://github.com/alloy-rs/alloy/releases/tag/v0.15.11) - 2025-05-12

### Features

- Add fn `fill_envelope` ([#2411](https://github.com/alloy-rs/alloy/issues/2411))

### Miscellaneous Tasks

- Release 0.15.11

### Other

- Added  anvil_send_impersonated_transaction ([#2417](https://github.com/alloy-rs/alloy/issues/2417))

## [0.15.10](https://github.com/alloy-rs/alloy/releases/tag/v0.15.10) - 2025-05-07

### Documentation

- Fix deprecated note ([#2403](https://github.com/alloy-rs/alloy/issues/2403))

### Features

- Add PendingTransactionBuilder::inspect ([#2405](https://github.com/alloy-rs/alloy/issues/2405))

### Miscellaneous Tasks

- Release 0.15.10

### Styling

- Introducing eth_getAccountInfo ([#2402](https://github.com/alloy-rs/alloy/issues/2402))
- Chore : fix typos ([#2398](https://github.com/alloy-rs/alloy/issues/2398))

## [0.15.9](https://github.com/alloy-rs/alloy/releases/tag/v0.15.9) - 2025-05-05

### Documentation

- Fix typos in documentation comments ([#2360](https://github.com/alloy-rs/alloy/issues/2360))

### Miscellaneous Tasks

- Release 0.15.9

## [0.15.8](https://github.com/alloy-rs/alloy/releases/tag/v0.15.8) - 2025-05-02

### Miscellaneous Tasks

- Release 0.15.8

## [0.15.7](https://github.com/alloy-rs/alloy/releases/tag/v0.15.7) - 2025-04-30

### Bug Fixes

- Send eth_unsubscribe with id ([#2369](https://github.com/alloy-rs/alloy/issues/2369))

### Miscellaneous Tasks

- Release 0.15.7
- Clippy happy ([#2370](https://github.com/alloy-rs/alloy/issues/2370))

## [0.15.6](https://github.com/alloy-rs/alloy/releases/tag/v0.15.6) - 2025-04-24

### Miscellaneous Tasks

- Release 0.15.6

## [0.15.5](https://github.com/alloy-rs/alloy/releases/tag/v0.15.5) - 2025-04-24

### Miscellaneous Tasks

- Release 0.15.5
- Release 0.15.4

## [0.15.3](https://github.com/alloy-rs/alloy/releases/tag/v0.15.3) - 2025-04-24

### Miscellaneous Tasks

- Release 0.15.3

## [0.15.2](https://github.com/alloy-rs/alloy/releases/tag/v0.15.2) - 2025-04-23

### Miscellaneous Tasks

- Release 0.15.2

## [0.15.1](https://github.com/alloy-rs/alloy/releases/tag/v0.15.1) - 2025-04-23

### Miscellaneous Tasks

- Release 0.15.1

## [0.15.0](https://github.com/alloy-rs/alloy/releases/tag/v0.15.0) - 2025-04-23

### Bug Fixes

- Fix grammar typos in documentation ([#2333](https://github.com/alloy-rs/alloy/issues/2333))
- Fix typos in comments and string literals ([#2329](https://github.com/alloy-rs/alloy/issues/2329))
- Fix Typos in Documentation Comments ([#2325](https://github.com/alloy-rs/alloy/issues/2325))
- [`transport`] Enable hyper-tls via hyper feature ([#2320](https://github.com/alloy-rs/alloy/issues/2320))

### Features

- [`multicall`] Add `CallItem` to dynamic builder ([#2307](https://github.com/alloy-rs/alloy/issues/2307))

### Miscellaneous Tasks

- Release 0.15.0
- Fix unused warnings ([#2334](https://github.com/alloy-rs/alloy/issues/2334))
- Misc heartbeat ([#2302](https://github.com/alloy-rs/alloy/issues/2302))

### Styling

- [`provider`] Rename `on_*` to `connect_*` ([#2225](https://github.com/alloy-rs/alloy/issues/2225))

## [0.14.0](https://github.com/alloy-rs/alloy/releases/tag/v0.14.0) - 2025-04-09

### Dependencies

- [deps] Core 1.0 ([#2184](https://github.com/alloy-rs/alloy/issues/2184))
- Bump msrv to 1.82 ([#2293](https://github.com/alloy-rs/alloy/issues/2293))

### Features

- Relax ProviderBuilder bounds ([#2276](https://github.com/alloy-rs/alloy/issues/2276))
- Make CachedNonceManager default ([#2289](https://github.com/alloy-rs/alloy/issues/2289))
- Add eth get transaction by sender and nonce ([#2285](https://github.com/alloy-rs/alloy/issues/2285))
- [`provider`] Nonce filler helpers ([#2280](https://github.com/alloy-rs/alloy/issues/2280))
- Add `From<TxHash>` for `PendingTxConfig` ([#2282](https://github.com/alloy-rs/alloy/issues/2282))

### Miscellaneous Tasks

- Release 0.14.0
- Use target_family instead of arch for wasm cfg ([#2288](https://github.com/alloy-rs/alloy/issues/2288))

### Styling

- Skip flaky bsc err resp ([#2279](https://github.com/alloy-rs/alloy/issues/2279))

## [0.13.0](https://github.com/alloy-rs/alloy/releases/tag/v0.13.0) - 2025-03-28

### Bug Fixes

- [`pubsub`] Fix race condition in ActiveSub ([#2222](https://github.com/alloy-rs/alloy/issues/2222))

### Documentation

- Update reference to MetaMask gas estimation ([#2232](https://github.com/alloy-rs/alloy/issues/2232))

### Features

- [`provider`] Watch_full_blocks ([#2194](https://github.com/alloy-rs/alloy/issues/2194))
- [`signers`] `Web3Signer` ([#2238](https://github.com/alloy-rs/alloy/issues/2238))
- [`provider`] Subscribe_full_blocks ([#2215](https://github.com/alloy-rs/alloy/issues/2215))
- [`provider`] Eth_signTransaction ([#2236](https://github.com/alloy-rs/alloy/issues/2236))
- [`provider`] Apply `GetSubscription` to trait ([#2220](https://github.com/alloy-rs/alloy/issues/2220))
- [`provider`] `DebugApi` generic over `Network` ([#2211](https://github.com/alloy-rs/alloy/issues/2211))

### Miscellaneous Tasks

- Release 0.13.0
- Expect instead of allow ([#2228](https://github.com/alloy-rs/alloy/issues/2228))
- [`provider`] Use `WeakClient` in `GetSubscription` ([#2219](https://github.com/alloy-rs/alloy/issues/2219))

## [0.12.6](https://github.com/alloy-rs/alloy/releases/tag/v0.12.6) - 2025-03-18

### Bug Fixes

- Drop geth's stderr handle ([#2104](https://github.com/alloy-rs/alloy/issues/2104))
- Debug_executionWitness call ([#2209](https://github.com/alloy-rs/alloy/issues/2209))

### Features

- Define subscription type ([#2203](https://github.com/alloy-rs/alloy/issues/2203))
- [providers] Add multicall batch layer ([#2174](https://github.com/alloy-rs/alloy/issues/2174))
- Remove poller task indirection ([#2197](https://github.com/alloy-rs/alloy/issues/2197))
- Add `ThrottleLayer` to Transport layers ([#2154](https://github.com/alloy-rs/alloy/issues/2154))

### Miscellaneous Tasks

- Release 0.12.6
- [provider] Remove 'latest' channel from heartbeat ([#2198](https://github.com/alloy-rs/alloy/issues/2198))
- Export * from provider ([#2195](https://github.com/alloy-rs/alloy/issues/2195))

## [0.12.5](https://github.com/alloy-rs/alloy/releases/tag/v0.12.5) - 2025-03-12

### Features

- Mock transport instead of provider ([#2173](https://github.com/alloy-rs/alloy/issues/2173))

### Miscellaneous Tasks

- Release 0.12.5

## [0.12.4](https://github.com/alloy-rs/alloy/releases/tag/v0.12.4) - 2025-03-07

### Miscellaneous Tasks

- Release 0.12.4

## [0.12.3](https://github.com/alloy-rs/alloy/releases/tag/v0.12.3) - 2025-03-07

### Miscellaneous Tasks

- Release 0.12.3

## [0.12.2](https://github.com/alloy-rs/alloy/releases/tag/v0.12.2) - 2025-03-07

### Miscellaneous Tasks

- Release 0.12.2
- Release 0.12.1

## [0.12.0](https://github.com/alloy-rs/alloy/releases/tag/v0.12.0) - 2025-03-07

### Bug Fixes

- [`provider`] Custom deser for pending blocks ([#2146](https://github.com/alloy-rs/alloy/issues/2146))
- [`provider`] Fill txs on `eth_call` ops ([#2092](https://github.com/alloy-rs/alloy/issues/2092))
- Tokio interval not supported on wasm ([#2053](https://github.com/alloy-rs/alloy/issues/2053))

### Features

- [`provider`] `decode_resp` for `EthCall` ([#2157](https://github.com/alloy-rs/alloy/issues/2157))
- [`provider`] MockProvider ([#2137](https://github.com/alloy-rs/alloy/issues/2137))
- [`provider`] `EthGetBlock` builder type ([#2044](https://github.com/alloy-rs/alloy/issues/2044))
- [`eth-call`] Rm borrowing from provider api ([#2127](https://github.com/alloy-rs/alloy/issues/2127))
- [`provider`] Trace api builder ([#2119](https://github.com/alloy-rs/alloy/issues/2119))
- Add eip1559 estimator type ([#2022](https://github.com/alloy-rs/alloy/issues/2022))
- Introduce `IntoWallet` to pass signer directly to `ProviderBuilder` ([#2120](https://github.com/alloy-rs/alloy/issues/2120))
- Add eth_sendRawTransactionConditional ([#2128](https://github.com/alloy-rs/alloy/issues/2128))
- [provider] Improve `DynProvider` discoverability ([#2076](https://github.com/alloy-rs/alloy/issues/2076))
- [provider] Add debug_codeByHash method ([#2075](https://github.com/alloy-rs/alloy/issues/2075))

### Miscellaneous Tasks

- Release 0.12.0
- [`provider`] Fix `mocked` ret type ([#2156](https://github.com/alloy-rs/alloy/issues/2156))
- Use impl Into StateOverride ([#2145](https://github.com/alloy-rs/alloy/issues/2145))
- [`provider`] Use quicknode ([#2121](https://github.com/alloy-rs/alloy/issues/2121))
- Rename `on_builtin` to `connect` ([#2078](https://github.com/alloy-rs/alloy/issues/2078))
- Update url ([#2071](https://github.com/alloy-rs/alloy/issues/2071))

### Styling

- Delegate provider fns in fill provider ([#2099](https://github.com/alloy-rs/alloy/issues/2099))

### Testing

- Add a test for cloning CachedNonceManager ([#2129](https://github.com/alloy-rs/alloy/issues/2129))
- Enable more tests on windows ([#2126](https://github.com/alloy-rs/alloy/issues/2126))

## [0.11.1](https://github.com/alloy-rs/alloy/releases/tag/v0.11.1) - 2025-02-12

### Bug Fixes

- Make `ChainLayer` network agnostic ([#2045](https://github.com/alloy-rs/alloy/issues/2045))
- [`multicall`] Impl Error for `Failure` +  clear returns `Empty` builder. ([#2043](https://github.com/alloy-rs/alloy/issues/2043))
- [docs] Update outdated Provider doc comment ([#1991](https://github.com/alloy-rs/alloy/issues/1991))
- Opt-in to keep stdout ([#1985](https://github.com/alloy-rs/alloy/issues/1985))

### Features

- [`provider`] Multicall ([#2010](https://github.com/alloy-rs/alloy/issues/2010))
- Add helpers for account overrides ([#2040](https://github.com/alloy-rs/alloy/issues/2040))
- [filler] Add prepare_call method ([#2011](https://github.com/alloy-rs/alloy/issues/2011))
- [provider] DynProvider added as a helper on provider ([#2008](https://github.com/alloy-rs/alloy/issues/2008))
- [provider] Expose inner `AnvilInstance` from `AnvilProvider` ([#2037](https://github.com/alloy-rs/alloy/issues/2037))
- Add helper fn to unwrap Sendable ([#2001](https://github.com/alloy-rs/alloy/issues/2001))
- [`node-bindings`] Expose anvil wallet ([#1994](https://github.com/alloy-rs/alloy/issues/1994))

### Miscellaneous Tasks

- Release 0.11.1
- Silence unused warnings ([#2031](https://github.com/alloy-rs/alloy/issues/2031))
- Add serde support for Eip1559Estimation ([#2012](https://github.com/alloy-rs/alloy/issues/2012))
- [provider] Default to `Ethereum` network in `FillProvider` ([#1995](https://github.com/alloy-rs/alloy/issues/1995))

## [0.11.0](https://github.com/alloy-rs/alloy/releases/tag/v0.11.0) - 2025-01-31

### Bug Fixes

- Store pubsubfrontend clone in rpcinner ([#1977](https://github.com/alloy-rs/alloy/issues/1977))
- Map txcount resp ([#1968](https://github.com/alloy-rs/alloy/issues/1968))
- [`node-bindings`] Reset `child.stdout` in `AnvilInstance` ([#1920](https://github.com/alloy-rs/alloy/issues/1920))
- [`transport`] Use `HttpsConnector` in `HyperTransport` ([#1899](https://github.com/alloy-rs/alloy/issues/1899))

### Dependencies

- [deps] Breaking bumps ([#1957](https://github.com/alloy-rs/alloy/issues/1957))

### Documentation

- Enable some useful rustdoc features on docs.rs ([#1890](https://github.com/alloy-rs/alloy/issues/1890))

### Features

- [`provider`] `eth_callMany` builder ([#1944](https://github.com/alloy-rs/alloy/issues/1944))
- [`provider`] Instantiate recommended fillers by default ([#1901](https://github.com/alloy-rs/alloy/issues/1901))
- Remove T: Transport from public APIs ([#1859](https://github.com/alloy-rs/alloy/issues/1859))

### Miscellaneous Tasks

- Release 0.11.0
- Rm passthrough txcount request ([#1970](https://github.com/alloy-rs/alloy/issues/1970))
- Release 0.10.0

### Other

- Added anvil_rollback to anvil API provider ([#1971](https://github.com/alloy-rs/alloy/issues/1971))
- [Feature] Keep Anvil in Provider have same types as the rest of the project ([#1876](https://github.com/alloy-rs/alloy/issues/1876))

### Refactor

- Change json-rpc trait names, relax bounds ([#1921](https://github.com/alloy-rs/alloy/issues/1921))
- Use the params struct in more places ([#1892](https://github.com/alloy-rs/alloy/issues/1892))

### Testing

- Fix warnings on windows ([#1895](https://github.com/alloy-rs/alloy/issues/1895))

## [0.9.2](https://github.com/alloy-rs/alloy/releases/tag/v0.9.2) - 2025-01-03

### Miscellaneous Tasks

- Release 0.9.2

## [0.9.1](https://github.com/alloy-rs/alloy/releases/tag/v0.9.1) - 2024-12-30

### Miscellaneous Tasks

- Release 0.9.1

## [0.9.0](https://github.com/alloy-rs/alloy/releases/tag/v0.9.0) - 2024-12-30

### Bug Fixes

- Use u64 for all gas values ([#1848](https://github.com/alloy-rs/alloy/issues/1848))

### Miscellaneous Tasks

- Release 0.9.0

## [0.8.3](https://github.com/alloy-rs/alloy/releases/tag/v0.8.3) - 2024-12-20

### Miscellaneous Tasks

- Release 0.8.3

## [0.8.2](https://github.com/alloy-rs/alloy/releases/tag/v0.8.2) - 2024-12-19

### Miscellaneous Tasks

- Release 0.8.2
- Misc clippy ([#1812](https://github.com/alloy-rs/alloy/issues/1812))

## [0.8.1](https://github.com/alloy-rs/alloy/releases/tag/v0.8.1) - 2024-12-16

### Bug Fixes

- [`transport`] Allow `RetryPolicy` to be set via layer ([#1790](https://github.com/alloy-rs/alloy/issues/1790))

### Miscellaneous Tasks

- Release 0.8.1

## [0.8.0](https://github.com/alloy-rs/alloy/releases/tag/v0.8.0) - 2024-12-10

### Bug Fixes

- Use `feeHistory` when estimating blob fee ([#1764](https://github.com/alloy-rs/alloy/issues/1764))

### Miscellaneous Tasks

- Release 0.8.0 ([#1778](https://github.com/alloy-rs/alloy/issues/1778))

## [0.7.3](https://github.com/alloy-rs/alloy/releases/tag/v0.7.3) - 2024-12-05

### Bug Fixes

- Wrong func sig ([#1742](https://github.com/alloy-rs/alloy/issues/1742))

### Features

- Specialized geth tracer ([#1739](https://github.com/alloy-rs/alloy/issues/1739))

### Miscellaneous Tasks

- Release 0.7.3
- Release 0.7.2 ([#1729](https://github.com/alloy-rs/alloy/issues/1729))
- Use encoded2718 ([#1702](https://github.com/alloy-rs/alloy/issues/1702))

### Other

- Specialized geth tracer for debug trace call ([#1741](https://github.com/alloy-rs/alloy/issues/1741))

## [0.7.0](https://github.com/alloy-rs/alloy/releases/tag/v0.7.0) - 2024-11-28

### Bug Fixes

- [provider] Use `BoxTransport` in `on_anvil_*` ([#1693](https://github.com/alloy-rs/alloy/issues/1693))

### Features

- EIP-7742 ([#1600](https://github.com/alloy-rs/alloy/issues/1600))
- Uninstall_filter in Provider trait ([#1685](https://github.com/alloy-rs/alloy/issues/1685))
- Get_block_transaction_count_by_number in Provider trait ([#1688](https://github.com/alloy-rs/alloy/issues/1688))
- Get_block_transaction_count_by_hash in Provider trait ([#1686](https://github.com/alloy-rs/alloy/issues/1686))
- Get_filter_logs in Provider trait ([#1684](https://github.com/alloy-rs/alloy/issues/1684))
- [debug] Add debug_executionWitness to debug api ([#1649](https://github.com/alloy-rs/alloy/issues/1649))

### Miscellaneous Tasks

- Release 0.7.0
- Release 0.7.0
- Release 0.7.0

## [0.6.4](https://github.com/alloy-rs/alloy/releases/tag/v0.6.4) - 2024-11-12

### Miscellaneous Tasks

- Release 0.6.4

## [0.6.3](https://github.com/alloy-rs/alloy/releases/tag/v0.6.3) - 2024-11-12

### Features

- [`network`] `AnyNetworkWallet` ([#1631](https://github.com/alloy-rs/alloy/issues/1631))

### Miscellaneous Tasks

- Release 0.6.3
- Release 0.6.2 ([#1632](https://github.com/alloy-rs/alloy/issues/1632))

## [0.6.1](https://github.com/alloy-rs/alloy/releases/tag/v0.6.1) - 2024-11-06

### Miscellaneous Tasks

- Release 0.6.1

## [0.6.0](https://github.com/alloy-rs/alloy/releases/tag/v0.6.0) - 2024-11-06

### Bug Fixes

- Wrap dashmap in Arc ([#1624](https://github.com/alloy-rs/alloy/issues/1624))
- [`provider`] Make `Caller` `EthCall` specific ([#1620](https://github.com/alloy-rs/alloy/issues/1620))
- Fix typo in RecommendedFillers associated type ([#1536](https://github.com/alloy-rs/alloy/issues/1536))
- [`provider`] Return `Subscription<N::HeaderResponse>` ([#1586](https://github.com/alloy-rs/alloy/issues/1586))
- [alloy-provider] `get_block_by_number` arg ([#1582](https://github.com/alloy-rs/alloy/issues/1582))

### Features

- Embed consensus header into RPC ([#1573](https://github.com/alloy-rs/alloy/issues/1573))
- Introduce `anvil_reorg` and related types. ([#1576](https://github.com/alloy-rs/alloy/issues/1576))
- Make eth_call and eth_estimateGas default to using Pending block ([#1568](https://github.com/alloy-rs/alloy/issues/1568))

### Miscellaneous Tasks

- Release 0.6.0

### Other

- Embed TxEnvelope into `rpc-types-eth::Transaction` ([#1460](https://github.com/alloy-rs/alloy/issues/1460))
- Add `BadBlock` type to `debug_getbadblocks` return type ([#1566](https://github.com/alloy-rs/alloy/issues/1566))

### Testing

- Fix tests ([#1583](https://github.com/alloy-rs/alloy/issues/1583))

## [0.5.4](https://github.com/alloy-rs/alloy/releases/tag/v0.5.4) - 2024-10-23

### Miscellaneous Tasks

- Release 0.5.4

## [0.5.3](https://github.com/alloy-rs/alloy/releases/tag/v0.5.3) - 2024-10-22

### Documentation

- [prestate] Comment prestate more clear ([#1527](https://github.com/alloy-rs/alloy/issues/1527))

### Miscellaneous Tasks

- Release 0.5.3

### Testing

- Fix more ci only ([#1402](https://github.com/alloy-rs/alloy/issues/1402))

## [0.5.2](https://github.com/alloy-rs/alloy/releases/tag/v0.5.2) - 2024-10-18

### Miscellaneous Tasks

- Release 0.5.2

## [0.5.1](https://github.com/alloy-rs/alloy/releases/tag/v0.5.1) - 2024-10-18

### Miscellaneous Tasks

- Release 0.5.1

## [0.5.0](https://github.com/alloy-rs/alloy/releases/tag/v0.5.0) - 2024-10-18

### Bug Fixes

- Change bound in RecommendedFillers to TxFiller<Self> ([#1466](https://github.com/alloy-rs/alloy/issues/1466))
- Make RecommendedFillers generic over Network ([#1458](https://github.com/alloy-rs/alloy/issues/1458))
- [provider] Use wasmtimer for wasm32 target ([#1426](https://github.com/alloy-rs/alloy/issues/1426))
- Set chain id for eth signer ([#1425](https://github.com/alloy-rs/alloy/issues/1425))

### Features

- Make Pending transaction own the provider ([#1500](https://github.com/alloy-rs/alloy/issues/1500))
- Add missing eth_getTransaction methods ([#1457](https://github.com/alloy-rs/alloy/issues/1457))
- [provider] LRUCache Layer ([#954](https://github.com/alloy-rs/alloy/issues/954))

### Miscellaneous Tasks

- Release 0.5.0
- Flatten eip-7685 requests into a single opaque list ([#1383](https://github.com/alloy-rs/alloy/issues/1383))
- Refactor some match with same arms ([#1463](https://github.com/alloy-rs/alloy/issues/1463))
- More simplifications ([#1469](https://github.com/alloy-rs/alloy/issues/1469))
- Some lifetime simplifications ([#1467](https://github.com/alloy-rs/alloy/issues/1467))
- Some small improvements ([#1461](https://github.com/alloy-rs/alloy/issues/1461))
- Use pending for next initial nonce ([#1455](https://github.com/alloy-rs/alloy/issues/1455))

## [0.4.2](https://github.com/alloy-rs/alloy/releases/tag/v0.4.2) - 2024-10-01

### Miscellaneous Tasks

- Release 0.4.2

## [0.4.1](https://github.com/alloy-rs/alloy/releases/tag/v0.4.1) - 2024-10-01

### Miscellaneous Tasks

- Release 0.4.1

## [0.4.0](https://github.com/alloy-rs/alloy/releases/tag/v0.4.0) - 2024-09-30

### Bug Fixes

- Ensure `max_fee_per_blob_gas` field handles `Some(0)` gracefully ([#1389](https://github.com/alloy-rs/alloy/issues/1389))
- [`rpc-client`] Add test for BuiltInConnString.connect_boxed ([#1331](https://github.com/alloy-rs/alloy/issues/1331))
- RecommendedFillers typo ([#1311](https://github.com/alloy-rs/alloy/issues/1311))

### Features

- Replace std/hashbrown with alloy_primitives::map ([#1384](https://github.com/alloy-rs/alloy/issues/1384))
- [transport-http] JWT auth layer ([#1314](https://github.com/alloy-rs/alloy/issues/1314))
- [provider] Subscribe to new blocks if possible in heartbeat ([#1321](https://github.com/alloy-rs/alloy/issues/1321))
- Add eth_simulateV1 ([#1323](https://github.com/alloy-rs/alloy/issues/1323))

### Miscellaneous Tasks

- Release 0.4.0
- Move type def to where it belongs ([#1391](https://github.com/alloy-rs/alloy/issues/1391))
- Fix some warnings ([#1320](https://github.com/alloy-rs/alloy/issues/1320))

### Other

- Make `gas_limit` u64 for transactions ([#1382](https://github.com/alloy-rs/alloy/issues/1382))
- Make `Header` blob fees u64 ([#1377](https://github.com/alloy-rs/alloy/issues/1377))
- Make `Header` `base_fee_per_gas` u64 ([#1375](https://github.com/alloy-rs/alloy/issues/1375))
- Make `Header` gas limit u64 ([#1333](https://github.com/alloy-rs/alloy/issues/1333))

## [0.3.6](https://github.com/alloy-rs/alloy/releases/tag/v0.3.6) - 2024-09-18

### Features

- ProviderCall ([#788](https://github.com/alloy-rs/alloy/issues/788))
- [transport-http] Layer client ([#1227](https://github.com/alloy-rs/alloy/issues/1227))

### Miscellaneous Tasks

- Release 0.3.6
- Release 0.3.5

### Refactor

- Separate transaction builders for tx types ([#1259](https://github.com/alloy-rs/alloy/issues/1259))

## [0.3.4](https://github.com/alloy-rs/alloy/releases/tag/v0.3.4) - 2024-09-13

### Bug Fixes

- `debug_traceCallMany` and `trace_callMany` ([#1278](https://github.com/alloy-rs/alloy/issues/1278))
- Serde for `eth_simulateV1` ([#1273](https://github.com/alloy-rs/alloy/issues/1273))

### Features

- [engine] Optional Serde ([#1283](https://github.com/alloy-rs/alloy/issues/1283))
- [alloy-rpc-types-eth] Optional serde ([#1276](https://github.com/alloy-rs/alloy/issues/1276))
- Improve node bindings ([#1279](https://github.com/alloy-rs/alloy/issues/1279))

### Miscellaneous Tasks

- Release 0.3.4

## [0.3.3](https://github.com/alloy-rs/alloy/releases/tag/v0.3.3) - 2024-09-10

### Miscellaneous Tasks

- Release 0.3.3

## [0.3.2](https://github.com/alloy-rs/alloy/releases/tag/v0.3.2) - 2024-09-09

### Miscellaneous Tasks

- Release 0.3.2

## [0.3.1](https://github.com/alloy-rs/alloy/releases/tag/v0.3.1) - 2024-09-02

### Features

- [alloy-provider] Add abstraction for `NonceFiller` behavior ([#1108](https://github.com/alloy-rs/alloy/issues/1108))

### Miscellaneous Tasks

- Release 0.3.1

## [0.3.0](https://github.com/alloy-rs/alloy/releases/tag/v0.3.0) - 2024-08-28

### Bug Fixes

- Make `Block::hash` required ([#1205](https://github.com/alloy-rs/alloy/issues/1205))
- [provider] Serialize no parameters as `[]` instead of `null` ([#1193](https://github.com/alloy-rs/alloy/issues/1193))
- Use `server_id` when unsubscribing ([#1182](https://github.com/alloy-rs/alloy/issues/1182))
- Return more user-friendly error on tx timeout ([#1145](https://github.com/alloy-rs/alloy/issues/1145))
- Use `BlockId` superset over `BlockNumberOrTag` where applicable  ([#1135](https://github.com/alloy-rs/alloy/issues/1135))
- [provider] Prevent panic from having 0 keys when calling `on_anvil_with_wallet_and_config` ([#1055](https://github.com/alloy-rs/alloy/issues/1055))
- [provider] Do not overflow LRU cache capacity in ChainStreamPoller ([#1052](https://github.com/alloy-rs/alloy/issues/1052))
- [admin] Id in NodeInfo is string instead of B256 ([#1038](https://github.com/alloy-rs/alloy/issues/1038))

### Dependencies

- [deps] Bump some deps ([#1141](https://github.com/alloy-rs/alloy/issues/1141))
- Revert "chore(deps): bump some deps"
- [deps] Bump some deps

### Features

- Add erc4337 endpoint methods to provider ([#1176](https://github.com/alloy-rs/alloy/issues/1176))
- Add block and transaction generics to otterscan and txpool types ([#1183](https://github.com/alloy-rs/alloy/issues/1183))
- Network-parameterized block responses ([#1106](https://github.com/alloy-rs/alloy/issues/1106))
- Add get raw transaction by hash ([#1168](https://github.com/alloy-rs/alloy/issues/1168))
- Add rpc namespace ([#994](https://github.com/alloy-rs/alloy/issues/994))

### Miscellaneous Tasks

- Release 0.3.0
- Clippy für docs ([#1194](https://github.com/alloy-rs/alloy/issues/1194))
- Release 0.2.1
- Correctly cfg unused type ([#1117](https://github.com/alloy-rs/alloy/issues/1117))
- Release 0.2.0
- Fix unnameable types ([#1029](https://github.com/alloy-rs/alloy/issues/1029))

### Other

- Add `AccessListResult` type (EIP-2930) ([#1110](https://github.com/alloy-rs/alloy/issues/1110))
- Removing async get account ([#1080](https://github.com/alloy-rs/alloy/issues/1080))

### Refactor

- Add network-primitives ([#1101](https://github.com/alloy-rs/alloy/issues/1101))

## [0.1.4](https://github.com/alloy-rs/alloy/releases/tag/v0.1.4) - 2024-07-08

### Bug Fixes

- Fix watching already mined transactions ([#997](https://github.com/alloy-rs/alloy/issues/997))
- Enable tls12 in rustls ([#952](https://github.com/alloy-rs/alloy/issues/952))

### Features

- Add missing admin_* methods ([#991](https://github.com/alloy-rs/alloy/issues/991))
- Support web3_sha3 provider function ([#996](https://github.com/alloy-rs/alloy/issues/996))
- Add trace_get ([#987](https://github.com/alloy-rs/alloy/issues/987))
- Add net rpc namespace ([#989](https://github.com/alloy-rs/alloy/issues/989))
- Add missing debug_* rpc methods ([#986](https://github.com/alloy-rs/alloy/issues/986))
- Add trace_filter method ([#946](https://github.com/alloy-rs/alloy/issues/946))

### Miscellaneous Tasks

- Release 0.1.4
- [provider] Simplify nonce filler ([#976](https://github.com/alloy-rs/alloy/issues/976))
- Release 0.1.3
- Nightly clippy ([#947](https://github.com/alloy-rs/alloy/issues/947))

### Testing

- Fix flaky anvil test ([#992](https://github.com/alloy-rs/alloy/issues/992))

## [0.1.2](https://github.com/alloy-rs/alloy/releases/tag/v0.1.2) - 2024-06-19

### Bug Fixes

- Downgrade tokio-tungstenite ([#881](https://github.com/alloy-rs/alloy/issues/881))
- Set minimal priority fee to 1 wei ([#808](https://github.com/alloy-rs/alloy/issues/808))
- Use envelopes in get_payload API ([#807](https://github.com/alloy-rs/alloy/issues/807))
- Return ExecutionPayloadV3 from get_payload_v3 ([#803](https://github.com/alloy-rs/alloy/issues/803))
- Correctly serialize eth_call params ([#778](https://github.com/alloy-rs/alloy/issues/778))
- Debug_trace arguments ([#730](https://github.com/alloy-rs/alloy/issues/730))
- Use U64 for feeHistory blocknumber ([#694](https://github.com/alloy-rs/alloy/issues/694))
- [provider] Map to primitive u128 ([#678](https://github.com/alloy-rs/alloy/issues/678))
- More abstraction for block transactions ([#666](https://github.com/alloy-rs/alloy/issues/666))
- Signer filler now propagates missing keys from builder ([#637](https://github.com/alloy-rs/alloy/issues/637))
- Better tx receipt mitigation ([#614](https://github.com/alloy-rs/alloy/issues/614))
- [provider] Uncle methods for block hash ([#587](https://github.com/alloy-rs/alloy/issues/587))
- [provider/debug] Arg type in debug_trace_call ([#585](https://github.com/alloy-rs/alloy/issues/585))
- Signer fills from if unset ([#555](https://github.com/alloy-rs/alloy/issues/555))
- Tmp fix for PendingTransactionBuilder::get_receipt ([#558](https://github.com/alloy-rs/alloy/issues/558))
- Conflict between to change and debug tests ([#550](https://github.com/alloy-rs/alloy/issues/550))
- Dont use fuse::select_next_some ([#532](https://github.com/alloy-rs/alloy/issues/532))
- Eip1559 estimator ([#509](https://github.com/alloy-rs/alloy/issues/509))
- Correctly treat `confirmation` for `watch_pending_transaction` ([#381](https://github.com/alloy-rs/alloy/issues/381))
- Remove app-layer usage of transport error ([#363](https://github.com/alloy-rs/alloy/issues/363))
- [provider] 0x prefix in sendRawTransaction ([#369](https://github.com/alloy-rs/alloy/issues/369))
- Change nonce from `U64` to `u64`  ([#341](https://github.com/alloy-rs/alloy/issues/341))
- Make `TransactionReceipt::transaction_hash` field mandatory ([#337](https://github.com/alloy-rs/alloy/issues/337))
- Fix subscribe blocks ([#330](https://github.com/alloy-rs/alloy/issues/330))

### Documentation

- Update get_balance docs ([#938](https://github.com/alloy-rs/alloy/issues/938))
- Touch up docs, TODOs ([#918](https://github.com/alloy-rs/alloy/issues/918))
- Add per-crate changelogs ([#914](https://github.com/alloy-rs/alloy/issues/914))
- [provider] Add examples to `raw_request{,dyn}` ([#486](https://github.com/alloy-rs/alloy/issues/486))
- Add aliases to `get_transaction_count` ([#420](https://github.com/alloy-rs/alloy/issues/420))
- More docs in `alloy-providers` ([#281](https://github.com/alloy-rs/alloy/issues/281))
- Add readmes

### Features

- Add trace_raw_transaction and trace_replay_block_transactions ([#925](https://github.com/alloy-rs/alloy/issues/925))
- [provider] Support ethCall optional blockId serialization ([#900](https://github.com/alloy-rs/alloy/issues/900))
- Add trace_replay_transaction ([#908](https://github.com/alloy-rs/alloy/issues/908))
- Move `{,With}OtherFields` to serde crate ([#892](https://github.com/alloy-rs/alloy/issues/892))
- [alloy] Add `"full"` feature flag ([#877](https://github.com/alloy-rs/alloy/issues/877))
- [provider] Expose `ProviderBuilder` via `fn builder()` ([#858](https://github.com/alloy-rs/alloy/issues/858))
- [rpc] Split off `eth` namespace in `alloy-rpc-types` to `alloy-rpc-types-eth` ([#847](https://github.com/alloy-rs/alloy/issues/847))
- Add engine API v4 methods ([#853](https://github.com/alloy-rs/alloy/issues/853))
- Send_envelope ([#851](https://github.com/alloy-rs/alloy/issues/851))
- [rpc] Add remaining anvil rpc methods to provider ([#831](https://github.com/alloy-rs/alloy/issues/831))
- [rpc] Use `BlockTransactionsKind` enum instead of bool for full arguments ([#840](https://github.com/alloy-rs/alloy/issues/840))
- Full block ambiguity ([#832](https://github.com/alloy-rs/alloy/issues/832))
- Method on `Provider` to make a new `N::TransactionRequest` ([#812](https://github.com/alloy-rs/alloy/issues/812))
- Add overrides to eth_estimateGas ([#802](https://github.com/alloy-rs/alloy/issues/802))
- [`provider`] `eth_getAccount` support ([#760](https://github.com/alloy-rs/alloy/issues/760))
- Set poll interval based on connected chain ([#767](https://github.com/alloy-rs/alloy/issues/767))
- Block id convenience functions ([#757](https://github.com/alloy-rs/alloy/issues/757))
- Add `EngineApi` extension trait ([#676](https://github.com/alloy-rs/alloy/issues/676))
- Eth_call builder  ([#645](https://github.com/alloy-rs/alloy/issues/645))
- AnvilProvider ([#611](https://github.com/alloy-rs/alloy/issues/611))
- Allow to only fill a transaction request ([#590](https://github.com/alloy-rs/alloy/issues/590))
- WalletProvider ([#569](https://github.com/alloy-rs/alloy/issues/569))
- Refactor request builder workflow ([#431](https://github.com/alloy-rs/alloy/issues/431))
- [provider] `debug_*` methods ([#548](https://github.com/alloy-rs/alloy/issues/548))
- [provider] Geth `txpool_*` methods ([#546](https://github.com/alloy-rs/alloy/issues/546))
- [provider] Get_uncle_count ([#524](https://github.com/alloy-rs/alloy/issues/524))
- Joinable transaction fillers ([#426](https://github.com/alloy-rs/alloy/issues/426))
- `std` feature flag for `alloy-consensus` ([#461](https://github.com/alloy-rs/alloy/issues/461))
- Rename alloy-rpc-*-types to alloy-rpc-types-* ([#435](https://github.com/alloy-rs/alloy/issues/435))
- Improve and complete `alloy` prelude crate feature flag compatiblity ([#421](https://github.com/alloy-rs/alloy/issues/421))
- Default to Ethereum network in `alloy-provider` and `alloy-contract` ([#356](https://github.com/alloy-rs/alloy/issues/356))
- Embed primitives Log in rpc Log and consensus Receipt in rpc Receipt ([#396](https://github.com/alloy-rs/alloy/issues/396))
- Make HTTP provider optional ([#379](https://github.com/alloy-rs/alloy/issues/379))
- Implement `admin_trait`  ([#405](https://github.com/alloy-rs/alloy/issues/405))
- Handle 4844 fee ([#412](https://github.com/alloy-rs/alloy/issues/412))
- [providers] Connect_boxed api ([#342](https://github.com/alloy-rs/alloy/issues/342))
- Convenience functions for nonce and gas on `ProviderBuilder` ([#378](https://github.com/alloy-rs/alloy/issues/378))
- Add eth_blobBaseFee and eth_maxPriorityFeePerGas ([#380](https://github.com/alloy-rs/alloy/issues/380))
- `Provider::subscribe_logs` ([#339](https://github.com/alloy-rs/alloy/issues/339))
- [layers] GasEstimationLayer ([#326](https://github.com/alloy-rs/alloy/issues/326))
- [json-rpc] Use `Cow` instead of `&'static str` for method names ([#319](https://github.com/alloy-rs/alloy/issues/319))
- Update priority fee estimator ([#316](https://github.com/alloy-rs/alloy/issues/316))
- Move local signers to a separate crate, fix wasm ([#306](https://github.com/alloy-rs/alloy/issues/306))
- Default to Ethereum network in `ProviderBuilder` ([#304](https://github.com/alloy-rs/alloy/issues/304))
- Merge Provider traits into one ([#297](https://github.com/alloy-rs/alloy/issues/297))
- [providers] Event, polling and streaming methods ([#274](https://github.com/alloy-rs/alloy/issues/274))
- Nonce filling layer ([#276](https://github.com/alloy-rs/alloy/issues/276))
- `trace_call` and `trace_callMany` ([#277](https://github.com/alloy-rs/alloy/issues/277))

### Miscellaneous Tasks

- Release 0.1.2
- Update changelogs for v0.1.1 ([#922](https://github.com/alloy-rs/alloy/issues/922))
- Add docs.rs metadata to all manifests ([#917](https://github.com/alloy-rs/alloy/issues/917))
- [clippy] Apply lint suggestions ([#903](https://github.com/alloy-rs/alloy/issues/903))
- [other] Use type aliases where possible to improve clarity  ([#859](https://github.com/alloy-rs/alloy/issues/859))
- [provider] Reorder methods in `Provider` trait ([#863](https://github.com/alloy-rs/alloy/issues/863))
- [provider] Document privileged status of EIP-1559 ([#850](https://github.com/alloy-rs/alloy/issues/850))
- [docs] Crate completeness and fix typos ([#861](https://github.com/alloy-rs/alloy/issues/861))
- [docs] Add doc aliases ([#843](https://github.com/alloy-rs/alloy/issues/843))
- Move trace to extension trait ([#818](https://github.com/alloy-rs/alloy/issues/818))
- Fix remaining warnings, add TODO for proptest-derive ([#819](https://github.com/alloy-rs/alloy/issues/819))
- Get_transaction_by_hash returns Option<Transaction> ([#714](https://github.com/alloy-rs/alloy/issues/714))
- [general] Add CI workflow for Windows + fix IPC test ([#642](https://github.com/alloy-rs/alloy/issues/642))
- Add Default to GasEstimatorLayer ([#410](https://github.com/alloy-rs/alloy/issues/410))
- Rename `RpcClient::prepare` to `request` ([#299](https://github.com/alloy-rs/alloy/issues/299))

### Other

- [feat] Synchronous filling ([#841](https://github.com/alloy-rs/alloy/issues/841))
- RecommendFiller -> RecommendedFiller, move to fillers ([#825](https://github.com/alloy-rs/alloy/issues/825))
- Add clippy at workspace level ([#766](https://github.com/alloy-rs/alloy/issues/766))
- Update clippy warnings ([#765](https://github.com/alloy-rs/alloy/issues/765))
- RpcWithBlock ([#674](https://github.com/alloy-rs/alloy/issues/674))
- Use Self when possible ([#711](https://github.com/alloy-rs/alloy/issues/711))
- Small refactor ([#652](https://github.com/alloy-rs/alloy/issues/652))
- Use `From<Address>` for `TxKind` ([#651](https://github.com/alloy-rs/alloy/issues/651))
- [Refactor] Move Provider into its own module ([#644](https://github.com/alloy-rs/alloy/issues/644))
- [Refactor] Delete the internal-test-utils crate ([#632](https://github.com/alloy-rs/alloy/issues/632))
- Expose SendableTx in providers ([#601](https://github.com/alloy-rs/alloy/issues/601))
- Temp get_uncle fix ([#589](https://github.com/alloy-rs/alloy/issues/589))
- Revert "chore: remove outdated license ([#510](https://github.com/alloy-rs/alloy/issues/510))" ([#513](https://github.com/alloy-rs/alloy/issues/513))
- Enable default-tls for alloy-provider/reqwest feature ([#483](https://github.com/alloy-rs/alloy/issues/483))
- Extension ([#474](https://github.com/alloy-rs/alloy/issues/474))
- Removed reqwest prefix ([#462](https://github.com/alloy-rs/alloy/issues/462))
- Numeric type audit: network, consensus, provider, rpc-types ([#454](https://github.com/alloy-rs/alloy/issues/454))
- Adds `check -Zcheck-cfg ` job ([#419](https://github.com/alloy-rs/alloy/issues/419))
- Use latest stable
- Rename `alloy-providers` to `alloy-provider` ([#278](https://github.com/alloy-rs/alloy/issues/278))
- Merge pull request [#3](https://github.com/alloy-rs/alloy/issues/3) from alloy-rs/prestwich/readme-and-cleanup
- Merge pull request [#2](https://github.com/alloy-rs/alloy/issues/2) from alloy-rs/prestwich/transports
- Rename middleware to provider

### Performance

- Remove getBlock request in feeHistory ([#414](https://github.com/alloy-rs/alloy/issues/414))

### Refactor

- [rpc] Extract `admin` and `txpool` into their respective crate ([#898](https://github.com/alloy-rs/alloy/issues/898))
- [signers] Use `signer` for single credentials and `wallet` for credential stores  ([#883](https://github.com/alloy-rs/alloy/issues/883))
- Improve eth_call internals ([#763](https://github.com/alloy-rs/alloy/issues/763))
- Change u64 to Duration ([#636](https://github.com/alloy-rs/alloy/issues/636))
- Make optional BlockId params required in provider functions ([#516](https://github.com/alloy-rs/alloy/issues/516))
- Rename to reqd_confs ([#353](https://github.com/alloy-rs/alloy/issues/353))

### Styling

- [Blocked] Update TransactionRequest's `to` field to TxKind ([#553](https://github.com/alloy-rs/alloy/issues/553))
- Remove outdated license ([#510](https://github.com/alloy-rs/alloy/issues/510))
- Sort derives ([#499](https://github.com/alloy-rs/alloy/issues/499))
- Rename `ManagedNonceLayer` to `NonceManagerLayer` ([#415](https://github.com/alloy-rs/alloy/issues/415))
- Eip1559Estimation return type ([#352](https://github.com/alloy-rs/alloy/issues/352))

### Testing

- Add rand feature in providers ([#910](https://github.com/alloy-rs/alloy/issues/910))

[`alloy`]: https://crates.io/crates/alloy
[alloy]: https://crates.io/crates/alloy
[`alloy-core`]: https://crates.io/crates/alloy-core
[alloy-core]: https://crates.io/crates/alloy-core
[`alloy-consensus`]: https://crates.io/crates/alloy-consensus
[alloy-consensus]: https://crates.io/crates/alloy-consensus
[`alloy-contract`]: https://crates.io/crates/alloy-contract
[alloy-contract]: https://crates.io/crates/alloy-contract
[`alloy-eips`]: https://crates.io/crates/alloy-eips
[alloy-eips]: https://crates.io/crates/alloy-eips
[`alloy-genesis`]: https://crates.io/crates/alloy-genesis
[alloy-genesis]: https://crates.io/crates/alloy-genesis
[`alloy-json-rpc`]: https://crates.io/crates/alloy-json-rpc
[alloy-json-rpc]: https://crates.io/crates/alloy-json-rpc
[`alloy-network`]: https://crates.io/crates/alloy-network
[alloy-network]: https://crates.io/crates/alloy-network
[`alloy-node-bindings`]: https://crates.io/crates/alloy-node-bindings
[alloy-node-bindings]: https://crates.io/crates/alloy-node-bindings
[`alloy-provider`]: https://crates.io/crates/alloy-provider
[alloy-provider]: https://crates.io/crates/alloy-provider
[`alloy-pubsub`]: https://crates.io/crates/alloy-pubsub
[alloy-pubsub]: https://crates.io/crates/alloy-pubsub
[`alloy-rpc-client`]: https://crates.io/crates/alloy-rpc-client
[alloy-rpc-client]: https://crates.io/crates/alloy-rpc-client
[`alloy-rpc-types`]: https://crates.io/crates/alloy-rpc-types
[alloy-rpc-types]: https://crates.io/crates/alloy-rpc-types
[`alloy-rpc-types-anvil`]: https://crates.io/crates/alloy-rpc-types-anvil
[alloy-rpc-types-anvil]: https://crates.io/crates/alloy-rpc-types-anvil
[`alloy-rpc-types-beacon`]: https://crates.io/crates/alloy-rpc-types-beacon
[alloy-rpc-types-beacon]: https://crates.io/crates/alloy-rpc-types-beacon
[`alloy-rpc-types-engine`]: https://crates.io/crates/alloy-rpc-types-engine
[alloy-rpc-types-engine]: https://crates.io/crates/alloy-rpc-types-engine
[`alloy-rpc-types-eth`]: https://crates.io/crates/alloy-rpc-types-eth
[alloy-rpc-types-eth]: https://crates.io/crates/alloy-rpc-types-eth
[`alloy-rpc-types-trace`]: https://crates.io/crates/alloy-rpc-types-trace
[alloy-rpc-types-trace]: https://crates.io/crates/alloy-rpc-types-trace
[`alloy-serde`]: https://crates.io/crates/alloy-serde
[alloy-serde]: https://crates.io/crates/alloy-serde
[`alloy-signer`]: https://crates.io/crates/alloy-signer
[alloy-signer]: https://crates.io/crates/alloy-signer
[`alloy-signer-aws`]: https://crates.io/crates/alloy-signer-aws
[alloy-signer-aws]: https://crates.io/crates/alloy-signer-aws
[`alloy-signer-gcp`]: https://crates.io/crates/alloy-signer-gcp
[alloy-signer-gcp]: https://crates.io/crates/alloy-signer-gcp
[`alloy-signer-ledger`]: https://crates.io/crates/alloy-signer-ledger
[alloy-signer-ledger]: https://crates.io/crates/alloy-signer-ledger
[`alloy-signer-local`]: https://crates.io/crates/alloy-signer-local
[alloy-signer-local]: https://crates.io/crates/alloy-signer-local
[`alloy-signer-trezor`]: https://crates.io/crates/alloy-signer-trezor
[alloy-signer-trezor]: https://crates.io/crates/alloy-signer-trezor
[`alloy-signer-wallet`]: https://crates.io/crates/alloy-signer-wallet
[alloy-signer-wallet]: https://crates.io/crates/alloy-signer-wallet
[`alloy-transport`]: https://crates.io/crates/alloy-transport
[alloy-transport]: https://crates.io/crates/alloy-transport
[`alloy-transport-http`]: https://crates.io/crates/alloy-transport-http
[alloy-transport-http]: https://crates.io/crates/alloy-transport-http
[`alloy-transport-ipc`]: https://crates.io/crates/alloy-transport-ipc
[alloy-transport-ipc]: https://crates.io/crates/alloy-transport-ipc
[`alloy-transport-ws`]: https://crates.io/crates/alloy-transport-ws
[alloy-transport-ws]: https://crates.io/crates/alloy-transport-ws

<!-- generated by git-cliff -->
