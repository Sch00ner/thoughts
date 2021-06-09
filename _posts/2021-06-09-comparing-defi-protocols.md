---
title: "Comparing DeFi Projects"
excerpt: "A rundown of the key features, advantages and disadvantages of Aave, Uniswap and MakerDAO."
toc: true
toc_sticky: true
date: 2021-06-09 20:14:00 +0530
categories: crypto tech
tags: defi aave uniswap makerdao
---
DeFi is an exciting space right now. It's also a very nascent space. There are so many things to explore, but so little time. That's why I'm writing down my quick impressions of some of the biggest projects in the DeFi ecosystem.

## [Aave](https://aave.com/)
Aave can be thought of as essentially, a bank that operates on the Ethereum blockchain. Like any bank it allows you to deposit your money to earn interest on the sum and allows loans to be taken out based on the deposited liquidity available.

### Key Features
- Decentralised and based on open source smart contracts.
- Loans are obtained from a pool, instead of two parties being matched individually.
- Interest rates are algorithmically ascertained based on how much a pool is utilised, i.e, if borrowers take out loans nearing the liquidity cap it, leads to higher interest rates and vice versa.
- Borrowers can take loans in a different cryptocurrency than the one they have deposited in a pool.
- All loans are typically overcollateralised on Aave. This means to borrow $100, one would have to deposit assets of a larger corresponding value.
- Aave secures loans by an automatic liquidation process that will sell off the collateral, if the value of the collateral drops below the mandated threshold.
- Flash loans are available without any collateral and are concluded within one block of transactions.

### Advantages
- AAVE holders can vote on changes through the Aave Improvement Proposals, making it quite democratic. One AAVE equals one vote.
- Loans being overcollateralised, instead of fractional reserve lending, acts as a backstop against a debt market crash.
- Reduced counterparty risk because a lender is not dependent on the borrower paying back the loan, as it is done automatically.

### Disadvantages
- AAVE holders act as insurance agents for lenders, securing their deposits by liquidating AAVE tokens in the Safety Module to cover the costs if the loan is not repaid.
- Loans being overcollateralised means Aave is a capital inefficient system.
- Dependent on smart contracts being bug free, the Achilles’ heel of any DeFi protocol.

## [Uniswap](https://uniswap.org/)
Uniswap is a decentralised exchange that operates on the Ethereum blockchain. The closest real life analogue would be a clearing house for trades, with sellers and buyers swapping tokens through an open source protocol and accessible to anyone with compatible ERC-20 tokens and wallets.

### Key Features
- Decentralised and based on open source smart contracts.
- Runs on an automated liquidity protocol instead of an order book system.
- Token swaps are conducted against a liquidity pairing of two tokens.
- Liquidity providers earn a fee for depositing tokens in a pool. Conversely, traders pay a fee to the pool which is distributed to liquidity providers.
- The price of a token in a pool is inversely proportional to the amount of it in the pool. Thus, if there is an ETH/DAI pool, the more DAI is withdrawn from the pool, the higher its price.
- Users receive LP tokens corresponding to their contribution to a pool which can be redeemed if they ever decide to exit.
- Allows a wide range of tokens to be swapped on the platform.

### Advantages
- Users control their funds because they hold the private key, unlike centralised exchanges. This ensures that even in the case of a hack, funds are not compromised.
- UNI holders can vote on any new developments with respect to distribution of new tokens and fee changes.
- Tokens can be listed for free, unlike centralised exchanges, only requiring that a liquidity pairing be initiated.
- Trustless token swapping empowers users to engage without fear of being scammed.

### Disadvantages
- Due to its liquidity pool based swapping, slippage can become very high with large transactions.
- Its model is capital inefficient, as most funds are sitting unused in pools.
- Liquidity providers may suffer from impermanent loss, a condition where HODLing is more profitable than depositing funds in a liquidity pool.
- High gas fees on Ethereum restrict the ability of small traders to make trades that they otherwise may have profited from.

## [MakerDAO](https://makerdao.com/en/)
MakerDAO was one of the first projects in the DeFI space. They are well known for being a decentralised lending platform and issuing the stablecoin DAI. Much like Aave, they also issue loans. But, their loans are in the form of DAI which users can mint by locking up ETH or other crypto in smart contracts, which serves as collateral.

### Key Features
- Based on the Maker protocol for decentralised governance by a DAO or decentralised autonomous organisation.
- MKR is the governance token of MakerDAO.
- Issuer of the popular DAI stablecoin.
- All DAI issued is overcollateralised by ETH or other crypto deposited with MakerDAO.

### Advantages
- Protects against the volatility of cryptocurrency markets by serving as a reference against fiat currency.
- Enables a stable and predictable financial market for issuing loans.
- MKR holders can vote on any new developments with respect to addition of  new tokens as collateral and setting associated risk parameters.

### Disadvantages
- Capital inefficient as all DAI is overcollateralised.
- MKR holders act as insurance agents for MakerDAO by acting as buyers of last resort for loans that are unfulfilled. MakerDAO will need to issue new MKR tokens and auction them to cover the shortfall, as well as draw from the Maker Buffer, a pool consisting of fees paid for collateral withdrawals.