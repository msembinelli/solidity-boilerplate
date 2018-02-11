# solidity-boilerplate
Basic boilerplate for writing Ethereum smart contracts in Solidity.

## Install
Install with necessary modules with `npm install`.

For windows, also run the script to install build tools `./install_windows_build_tools.sh`.

## Running tests with mocha & ganache
The tests run a deploy and run the contract on a local simulated ethereum network.

`npm run tests`

## Deploying contract to a public ethereum network
Please copy/rename `config.template.yml` to `config.yml` and populate with your HDWalletProvider settings.

A url + token can be provided by https://infura.io/.

You can deploy with `node deploy.js`.
