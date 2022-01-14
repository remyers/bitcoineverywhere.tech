---
title: "Use Cases"
---

We define here some our terms for use cases of Bitcoin and explore features that could be uniquely useful in developing countries. 

### Exchanges

A basic and essential use case for Bitcoin is to buy and sell it for local fiat currency. Bitcoin exchanges can be performed in a variety of ways ranging from in person with cash to using an online custodial exchange which operate via bank transfers.

#### In-Person

Bitcoin can be bought or sold in person for cash using various means to settle the transfer. Two parties with mobile bitcoin wallets on their smart phones can perform the transfer by the bitcoin buyer giving their payment address to the seller. The address can be scanned via a QR code, shared via an SMS message or other similar means. Counter parties can find each other and arrange trades using web sites, at organized [trading events](https://www.meetup.com/stockholm-satoshi-square/) or visit a [retail exchange business](https://www.wsj.com/articles/walk-in-cryptocurrency-exchanges-emerge-amid-bitcoin-boom-11633107697) or bitcoin ATM.

Some disadvantages of in-person transfers include: settlement time, theft and convenience. Settlement time for bitcoin transfers is hard to predict. Because of the probabilistic nature of finding blocks even transactions paying high fees might take up to an hour to clear. There is also risks of [assault](https://github.com/jlopp/physical-bitcoin-attacks/blob/master/README.md) when doing in-person transfers involving cash and bitcoin with unknown counter parties. Online trading is more convenient than in-person trading, but only for those who already have access to online banking options.

In person trades could once be coordinated with the popular website [localbitcoin.com](https://localbitcoins.com), but regulatory pressure has forced this option to be [removed](https://bitcoinmagazine.com/culture/localbitcoins-stops-cash-trades-personal-offers-on-platform).

#### Person-to-Person (P2P)

Bitcoin can be bought and sold directly with other people using online web sites or applications. These systems host a bulletin board where users post advertisements to buy or sell bitcoin for various forms of payment. Payment can be in the form of a bank transfer, pre-paid gift cards and other online payment methods.

#### Non-Custodial

P2P trading sites like [Localbitcoins.com](https://localbitcoins.com) and [Paxful.com](https://paxful.com) hold your bitcoin in a wallet in which you do not control the private key that secures your bitcoin. This simplifies trading and security, but means that users do not have ultimate control of their bitcoin waiting to be traded. Non-custodial options like [Hodlhodl.com](https://hodlhodl.com) and [Bisq](https://bisq.network/) only lock bitcoin that is part of a trade into a multisig output. Bitcoin not involved in a trade on these platforms is controlled by keys that are only held by the user. Trades require settlement of both the bitcoin and payment method to be final which can introduce delay. Some payment methods may also be reversible so caution is required when accepting P2P trades offers.

#### Custodial

Custodial trading platforms, like traditional stock trading platforms, host an order book and require users to deposited bitcoin and currencies used for payment. These platforms typically require users submit personally identifying information (PII) to confirm to local regulations. Trades can settle quickly because the platform controls both means of payment. Users must trust custodial platforms to secure their bitcoin and PII from theft. Custodial exchanges can also manipulate their order book using [wash trading](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3362153) and other methods.

#### Over-the-Counter (OTC)

An OTC exchange uses a broker to execute a high value order across various exchanges. Like custodial exchanges an OTC desk will require PII and a deposit in advance of bitcoin to be sold or payment method to be used for a bitcoin purchase.

#### Alt. Coins

Most exchanges also deal in non-bitcoin cryptocurrencies. Used as a payment method, these alternate coins may allow users without traditional means of payment to conduct trades. However, exchanges that trade alt. coins risk misleading new users to assume they hold the same decentralization and value properties as bitcoin.

### Remittances

Perhaps the most significant use of the Bitcoin network is as a way to transfer value from family members in first-world to their family still living in their country of origin. This use case requires Bitcoin exchanges to exist in both countries and tools that are easy enough to use for non-technical users. Many third-world economies depend on remittances, but governments may not always support alternatives to bank based remittance services. Governments may express concern about funds going to illegal groups such as insurgents. Governments also often force unfavorable exchange rates on remittances as a form of taxation on incoming currency flows. Volatility of the Bitcoin exchange rate can be a problem for remittance applications because most users will want to denominate the transfer in the source fiat currency.

### Saving

Many people in developing countries do not have access to traditional banking due to high fees, no local bank branches or lack of official identification. Buyers of Bitcoin can also opt out of saving in devaluing local currencies. Relatively wealthy users that save in Bitcoin can also make purchases of goods and services from abroad or more easily transfer money abroad in places with capital controls.

### Donations

Governments can use the banking system to deny funding to non-profit groups for political reasons. Bitcoin payments can be an alternative source of funding that side-steps restrictions that might exist in either the sending or receiving country. Like remittances, donations received in Bitcoin can also be sent at lower cost from abroad and avoid unfavorable exchange rates set by governments. This use case requires access to unregulated Bitcoin exchanges so that donations can not be censored when they are converted to the local currency.

### Retail Payments

Retail businesses can accept Bitcoin payments directly, though may favor Lightning payments that settle more rapidly. Businesses that accept Bitcoin as payment can operate without bank accounts more safely then dealing only in cash. They can also reduce credit card processing fees and have access to their settled funds faster than from credit cards. Merchants can also access financial services they would normally get from a bank even if they do not have government issued identification, formal business licenses, sufficient capital or revenue to open a bank account. Businesses can also potentially access loans and investment from overseas using Bitcoin based financial services. Informal online side businesses can find domestic customers online and accept payments directly using Bitcoin. An early example of such a business is [Mandrik's Famous Baklava](https://btcbaklava.com/product/baklava/) which sold Baklava via the mail for Bitcoin as early as 2011.

### Online Task Work/Freelance

Online remote workers can more easily be paid in Bitcoin than via bank transfers or credit cards. Bank transfers often charge high fixed fees and are not suitable for frequent small payments. Accepting payments via credit card can also be difficult across borders due to fraud detection algorithms and high percentage based fees. Setting up a bank account or credit card account is cumbersome and often impossible for someone who does not have relatively high earnings from their online work. Paying an informal worker in a new country does not require any additional registration from either the worker or employer if both are already setup to use Bitcoin. An example of a company that facilitate this type of work using Bitcoin is [StakWork](https://customers.stakwork.com/).

### Import/Export

Large scale input/export businesses are usually highly regulated and not as suitable for using Bitcoin unless their country is cut off from the global banking system and have government support to use Bitcoin. Smaller businesses though that ship directly to customers or via  informal networks can benefit from using Bitcoin to directly access foreign markets. These businesses can advertise online to find customers willing to pay in Bitcoin and ship directly to them. A good example of such a business is an Afghan saffron seller [advertising to western customers](../../assets/images/afghan_saffron.png) on Twitter. This use does not require fast settlement, but could still benefit from lower fees by using Lightning. Escrow services such as [Bitrated](https://www.bitrated.com/) can also help mediate disputes using Bitcoin payments. Services that sell gift cards for Bitcoin can also allow people to purchase goods from overseas even when they do not have a credit card accepted by the local merchant.

### Online Services

Customers of online services can access providers that accept Bitcoin but not their local currency. For example, there are many VPN services that accept Bitcoin and payments in major currencies such as [Mullvad.net](https://mullvad.net/en/pricing/). People in non-western countries who cannot not get access to these currencies or payment methods can still use Bitcoin to pay and gain additional protection against censorship and surveillance in their own country.

### Bitcoin Mining

Bitcoin mining offers an alternative to purchasing Bitcoin in places where Bitcoin exchanges do not exist. Mining converts payments for energy and mining hardware to Bitcoin. Mining may be a particularly attractive way to acquire Bitcoin in countries that subsidize power for businesses and/or consumers. Mining is also attractive in places with stranded energy or to bootstrap new energy projects located far from energy markets such as the the [mining project](../../assets/images/virunga_mining.png) in the Virunga wildlife park in the DRC.

### Telecommunication

Purchasing local communication services like prepaid SIM card top ups using Bitcoin offers additional anonymity. For example, the company [Bitrefill](https://bitrefill.com) sells prepaid minutes for mobile networks in countries like Cuba and Russia that are often cut off from wester payment networks. Mobile minutes also provides a convenient way to convert Bitcoin to local currency in places where phone minutes can be used as payment [M-pesa](https://www.vox.com/future-perfect/21420357/kenya-mobile-banking-unbanked-cellphone-money). 

It may also be possible to use Bitcoin to sell access to local community driven telecommunication services such as fixed WiFi mesh networks and small cell CBRS 5G base stations from companies like [Freedomfi](https://freedomfi.com/). Services like Blockstream's [Transmission](https://blockstream.com/satellite-queue/) service demonstrates how Bitcoin can be used to pay for one-off global satellite data broadcasts with out needing to register an account. Applying Blockstream's Lightning based payment system to local WiFi or 5G base stations would allow local entrepreneurs to build out ad-hoc telecommunication infrastructure for their communities.

### Summary

These are some of the most promising use cases for Bitcoin in developing economies, but other use cases certainly exist and new ones will continue to be developed. Local exchanges are key to enabling most other use cases until direct Bitcoin acceptance by merchants becomes ubiquitous. Person-to-person and non-custodial exchanges offer censorship resistance, privacy and security but centralized custodial exchanges often provide an easier user experience and better liquidity. Once exchanges with sufficient buy side liquidity are established, remittances allow people to take advantage of Bitcoin's advantages without being exposed to price volatility or complexity. Retail and savings uses cases are likely to follow based on the level of Bitcoin that flows into a country from remittances, freelance work, mining and trade.