digioptions-contracts-web-examples
==================================

[![Version](https://img.shields.io/github/v/tag/berlincode/digioptions-contracts-web-examples.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/digioptions-contracts-web-examples)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/berlincode/digioptions-contracts-web-examples/blob/master/LICENSE)

Browser based interface for creating and settling DigiOptions markets (html / javascript)

This repository contains examples that helps interacting with the ethereum contract from
[https://github.com/berlincode/digioptions-contracts.js](https://github.com/berlincode/digioptions-contracts.js).

 * deploy.html - deploy contracts [click here for the online version](https://berlincode.github.io/digioptions-contracts-web-examples/deploy.html)
 * markets-create.html - create and settle markets [click here for the online version](https://berlincode.github.io/digioptions-contracts-web-examples/market_create.html)
 * marketlister_config.html - read and configure marketLister contracts [click here for the online version](https://berlincode.github.io/digioptions-contracts-web-examples/marketlister_config.html)

Of course you can download the repository and run the files locally. Remember that Metamask does not work on file://...-urls.
So run `npm run serve` to start a server and open your browser on http://localhost:8010

Related packages
----------------

Following packages belong to DigiOptions' ecosystem.

| Package                                                                                                              | Version                                                                                                                                                                                            | Description                                                                                       |
|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| [`digioptions/digioptions-app`](https://github.com/digioptions/digioptions-app)                                      | [![Version](https://img.shields.io/github/v/tag/digioptions/digioptions-app.svg?label=version&sort=semver&logo=github)](https://github.com/digioptions/digioptions-app)                            | Distributed app / web GUI for DigiOptions (html / javascript) |
| [`digioptions/digioptions-viewer`](https://github.com/digioptions/digioptions-viewer)                                | [![Version](https://img.shields.io/github/v/tag/digioptions/digioptions-viewer.svg?label=version&sort=semver&logo=github)](https://github.com/digioptions/digioptions-viewer)                      | Embeddable web widget to view DigiOptions markets and order book (html / javascript) |
| [`berlincode/digioptions-contracts.js`](https://github.com/berlincode/digioptions-contracts.js)                      | [![Version](https://img.shields.io/github/v/tag/berlincode/digioptions-contracts.js.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/digioptions-contracts.js)            | Freedex peer to peer protocol for decentralized markets on DigiOptions (javascript / solidity) |
| [`berlincode/digioptions-contracts-web-examples`](https://github.com/berlincode/digioptions-contracts-web-examples)  | [![Version](https://img.shields.io/github/v/tag/berlincode/digioptions-contracts-web-examples.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/digioptions-contracts-web-examples)  |  Browser based interface for creating and settling DigiOptions markets (html / javascript) |
| [`berlincode/digioptions-trader.js`](https://github.com/berlincode/digioptions-trader.js)                            | [![Version](https://img.shields.io/github/v/tag/berlincode/digioptions-trader.js.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/digioptions-trader.js)                  | Customizable automatic trading system for DigiOptions (javascript) |
| [`berlincode/digioptions-tools.js`](https://github.com/berlincode/digioptions-tools.js)                              | [![Version](https://img.shields.io/github/v/tag/berlincode/digioptions-tools.js.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/digioptions-tools.js)                    | Common base fuctions for building applications for DigiOptions' ecosystem (javascript) |
| [`berlincode/factsigner`](https://github.com/berlincode/factsigner)                                                  | [![Version](https://img.shields.io/github/v/tag/berlincode/factsigner.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/factsigner)                                        | Provable signatures of real life events (javascript / solidity) |
| [`berlincode/factsigner-go`](https://github.com/berlincode/factsigner-go)                                            | [![Version](https://img.shields.io/github/v/tag/berlincode/factsigner-go.svg?label=version&sort=semver&logo=github)](https://github.com/berlincode/factsigner-go)                                  | Provable signatures of real life events (go) |


Public repository
-----------------

https://github.com/berlincode/digioptions-contracts-web-examples

Copyright and license
---------------------

Code and documentation copyright Ulf Bartel. Code is licensed under the
[MIT license](./LICENSE).
