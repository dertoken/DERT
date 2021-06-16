<h1 align="center">
  <img align="center" src="https://coin.top/production/upload/logo/TCZrHCQMk51DBRDhgrLENT2py92CB2WeUd.png?t=1623064349824" width="100"/>
</h1>


## What is DERT?

__[DERT - Developer Document](http://www.hbslys.vip/)__

The open source code of dert (distributed energy resource) allows any developer to build different forms of distributed applications running on the protocol, which ensures the security and simplicity of design.

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
