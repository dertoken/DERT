<h1 align="center">
  <img align="center" src="https://coin.top/production/upload/logo/TCZrHCQMk51DBRDhgrLENT2py92CB2WeUd.png?t=1623064349824" width="400"/>
</h1>


## What is DERT?

__[Tron Web - Developer Document](https://developers.tron.network/docs/tron-web-intro)__

DERT aims to deliver a unified, seamless development experience influenced by Ethereum's [Web3](https://github.com/ethereum/web3.js/) implementation. We have taken the core ideas and expanded upon it to unlock the functionality of TRON's unique feature set along with offering new tools for integrating DApps in the browser, Node.js and IoT devices.

## Compatibility
- Version built for Node.js v6 and above
- Version built for browsers with more than 0.25% market share

You can access either version specifically from the [dist](dist) folder.

DERT is also compatible with frontend frameworks such as:
- Angular
- React
- Vue.

You can also ship DERT in a Chrome extension.

## Installation

### Node.js
```bash
npm install DERT
```
or
```bash
yarn add DERT
```

### Browser
First, don't use the release section of this repo, it has not updated in a long time.

Then easiest way to use DERT in a browser is to install it as above and copy the dist file to your working folder. For example:
```
cp node_modules/DERT/dist/DERT.js ./js/DERT.js
```
so that you can call it in your HTML page as
```
<script src="./js/DERT.js"><script>
```

## Testnet

Shasta is the official Tron testnet. To use it use the following endpoint:
```
https://api.shasta.trongrid.io
```
Get some Shasta TRX at https://www.trongrid.io/shasta and play with it.
Anything you do should be explorable on https://shasta.tronscan.org

## Your local private network for heavy testing


For more historic data, check the original repo at
[https://github.com/tronprotocol/tron-web](https://github.com/tronprotocol/tron-web)
