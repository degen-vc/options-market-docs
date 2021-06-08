# AV Older Version 1

### Introduction to Liquid Vault

Before going into the mechanics of the Accelerator Vault \(AV as it will now be known\), it's important to understand what the DegenVC Liquid Vault \(LV\) technology entails. The LV is fully described in this [**Medium article**](https://medium.com/degen-vc/liquid-vault-248779b58cfe), and below are the sections that relate to the AV.

![](../.gitbook/assets/image%20%283%29.png)

The idea of the LV is ground breaking primarily because Liquidity Pool tokens are essentially offered at a **maximum 50% discount.** This smart contract has 3 economic levers \("levers"\) that can be set in order to create certain conditions of a token's trade:

1. Charge an ETH fee thus reducing the 50% discount. This ETH could then be used for other purposes;
2. Lock the LP tokens created by pooling on Uniswap project tokens with a buyer’s ETH for a period before the buyer could claim them;
3. Permanently lock some LP tokens while still giving the buyer LP at a discount.

_**With this background, let's explore the AV.**_

### Accelerator Vault v1

Leading on from the Liquid Vault, the AV creates the conditions for rapid expansion of the liquidity pool, using the 3 levers described above - here is how:

1. The **ETH Fee charged will be 30%** - this means that for every 1 ETH you send into the AV, 0.3 is deducted and 0.7 is pooled with the equivalent value of tokens. This translates into a 20% discount on LP - but what is this 30% fee used for?  _**In AV, this ETH Fee is used to automatically-buy the $OSM token from the Uniswap market, creating embedded buy-pressure on the token as a consequence of a user receiving a 20% discounted LP!**_ 
2. The LP tokens will be locked for a period of 7-days on the Web UI. Once this time is up, the user will be able to claim their LP from the Web UI and do with their LP what they want. They could:

   1. Unpool and sell the $OSM and keep the ETH, or reinvest it in the LP for another 20% discount;
   2. Retain the LP to add value to overall $OSM liquidity; or
   3. A combination of the above. 

  
   _**In AV, this lock period remain static.**_  

3. There will be no permanent lock on LP tokens.  _**In AV, no permanent lock period will be used.**_

### Summary

The AV is designed to incentivise people to claim a discount while having their LP locked for a very short period of time, while the smart contract auto-buys $OSM creating upward price pressure on the token. This is but one uses of the LV technology and will be a common sight in all future DegenVC project implementations.  

The AV will be seeded with 10% of total supply - 10MM tokens, on March 19th, 2021. It will then be up to users to decide if the 20% discount is worth the short 7-day lock  period. It will be a fascinating time.

