# KaseiCoin


![joint_savings_hero](images/KASEI.jpg)

KaseiCoin the currency of the new monetary system for the new Mars colony, will be a fungible token that is ERC-20 compliant. and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

The crowdsale contract will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KSEI, or KaseiCoin tokens. the contract will mint the tokens automatically and distribute them to buyers in one transaction. Crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.






---

## Technologies

* [Solidity](https://docs.soliditylang.org/en/v0.8.11/) 

* [Remix](https://remix.ethereum.org/) 

* [OpenZeppelin](https://openzeppelin.com/)

---

##Imports

import "./KaseiCoinToken.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/Crowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/emission/MintedCrowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/validation/CappedCrowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/validation/TimedCrowdsale.sol";
import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v2.5.0/contracts/crowdsale/distribution/RefundablePostDeliveryCrowdsale.sol";

---

## Usage

This is a Crowdsale smart contract setup that allows the use of the implemented functions such as  Buy, transfer, Balance, Total Supply check, also the use of OpenZeppelin allowed to extend the functionality of the crowdsale contract by adding time restrictions, refund capabilities, and a cap for the number of tokens that may be created. The following images and video recording demonstrates an example of the mentioned ERC Token functions 

---

## Evaluation Evidence:
Successful compile of KaseiCoinToken contract

![KaseiCoinToken](images/KaseiCoinToken.jpg)

Successful compile of KaseiCoinCrowdsale contract

![KaseiCoinToken](images/KaseiCoinCrowdsale.jpg)

## Kasei video recording
[KaseiCoinToken](https://youtu.be/K5aZZ8FO1CY)

## Added functionality visible tokens at MetaMask
![KaseiCoinToken](images/MM_KSEI.jpg)

---

## Contributors


Israel Fernandez -- codan81@gmail.com

---
## License
MIT License

Copyright (c) 2021  

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
