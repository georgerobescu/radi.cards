<h1 align="center">Radi.Cards</h1>

<div align="center">
NFT eCards for greater fun and greater good. All income goes to charities working to promote Internet freedom and environmental rights. 
</div>

<br/>

<div align="center">
  <a href="https://www.ethereum.org/" target="_blank"><img src="https://img.shields.io/badge/platform-Ethereum-brightgreen.svg?style=flat-square" alt="Ethereum" /></a>
  <a href="http://erc721.org/" target="_blank"><img src="https://img.shields.io/badge/token-ERC721-ff69b4.svg?style=flat-square" alt="Token ERC721" /> </a>
  <img src="https://img.shields.io/badge/contributions-welcome-orange.svg?style=flat-square" alt="Contributions Welcome" />
  <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="MIT License" />  
</div>

# Authors

* D1Labs
* KnownOrigin.io

# Features

* **Full ERC-721 Compatibility** - Smart Contract is fully ERC-721 compliant
* **Full ERC-721 Metadata Compatibility** - Each ERC-721 token uses latest standards for ERC-721 metadata
* **Full ERC-165 Compatibility** - Smart Contract is fully ERC-165 compliant
* **IPFS Support** - Internally IPFS is used for storing asset files and metadata


# Setup

Add a local `mnemonic.js` at the root with your testnet mnemonic (used for deployments)

The `mnemonic.js` should be like so:
```javascript
module.exports = 'dog alley hunt pen away brew matter frog rural salad educate kebab';
```

Install dependencies:

`npm install`

Start VueJs Front End:

`npm run start`

Run Smart Contract tests:

`npm run test`

# Firebase Deployment

* Ensure you have access to the firebase project `radi-cards`

* Install firebase tools `npm install -g firebase-tools`

* You may need to login and authenticate yourself if you have not done this before 
  * Run this `firebase login` and follow the instructions

* Run the script `./firebase_deploy.sh` - this will push your current working project to live so **be careful**

* Firebase deployment configuration can be found in `./firebase.json`

# License

[MIT](https://opensource.org/licenses/MIT)
