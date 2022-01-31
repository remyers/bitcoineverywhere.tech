---
title: "Existing Technology"
---

We summarize below existing Bitcoin technology, how it is relevant for our target audience and offer suggestions for how it could be improved.

* Bitcoin Wallets
* Samourai wallet: a true free and open-source Bitcoin wallet that puts privacy first. Available on Android, Samourai Wallet features a CoinJoin implementation called Whirlpool that breaks deterministic links to prior on-chain activity. Additionally, there are a variety of post-mix spending tools to help the user maintain anonymity. All communications in Samourai Wallet are carried out over Tor and the mobile wallet can be connected to the user’s own RoninDojo full node. Samourai wallet can be used in offline mode, transactions will broadcast after wifi or cell service is restored. https://samouraiwallet.com/
*
* Sparrow Wallet: a desktop Bitcoin wallet that is free and open source. Sparrow Wallet features an intuitive user interface and is easy for beginners to start understanding the basics but also has many advanced features for more technical users. Sparrow Wallet also implemented Whirlpool CoinJoin. Users in countries hostile to bitcoin can use Sparrow coincontrol and coinjoin to ensure that they won't be tracked by bad actors, such as local police and chainalysis companies. https://www.sparrowwallet.com/ 
* 
* Lightning Wallets
* 
* Bluewallet
* Muun wallet
* 
* Secure Chat Apps
* Serval Mesh project: Allows you to communicate privately anytime and anywhere. Users can keep using their existing phone number on mesh, which is key in a disaster situation when people are trying quickly contact each other. http://www.servalproject.org/ 
* Briar messenger: Unlike traditional messaging apps, Briar is a peer-to-peer encrypted messenger with no central server to relay info or store users’ messages. Messages are stored on the devices of the sender and receiver only. Briar uses the Tor network to send and receive messages and all communications are free of metadata. https://briarproject.org/index.html
* Bridgefy: is an offline messaging app that doesn’t require internet access. Users can communicate through Bluetooth. It is available for both Android and iOS. https://apps.apple.com/us/app/bridgefy/id975776347
* The 3 ways Bridgefy works: Person to Person Mode (turn on your Bluetooth and chat privately with people that are within 330 feet of you), Mesh Mode (Chat with people more than 330 feet from you by connecting through other Bridgefy users found in the middle), Broadcast Mode (Go into the Broadcast section and send messages to every Bridgefy user around you at the same time, even if you don’t have them on your contacts list).
* Vojer: an encrypted messenger that supports photo sharing, texting, and voice messages. Users can connect without 3G/4G or Wi-Fi coverage. Vojer doesn’t have intermediate servers or websites. Vojer doesn’t request extra permissions except those required to operate – WiFi, Bluetooth, and Microphone. This application is for iOS only. https://apps.apple.com/us/app/vojer-be-connected-conference-or-in-roaming-be-intouch/id913585553
* Manyverse: peer-to-peer social networking on mobile; no servers or internet required https://www.manyver.se/ 
* 
* Full Nodes
* Running a bitcoin node gives a user increased privacy over their funds without trusting their wallet provider’s nodes. Users can run nodes with dedicated hardware and install node software (Umbrel,RoninDojo, MyNode, RaspiBlitz). Dedicated node hardware may be hard to source in developing or third world countries. It is probably more feasible for people living in these areas to run bitcoin core on an old laptop.
* Basic set up for a bitcoin core node: laptop, 1TB SSD, and Bitcoin Core downloaded from https://bitcoin.org/en/full-node
* Onion Routing
* Tor: Tor use is also referred to as “the onion router”. Tor is an anonymizing computer network designed to help people in countries where Internet access may be censored or monitored. When a user connects to Tor, their internet activity is sent through the Tor network, anonymizing their internet activity to prevent snooping, and allow them to access websites that may be blocked in certain jurisdictions.
* Orbot: is an internet proxy that routes user traffic through the Tor network and offers a built-in VPN feature that cannot be blocked by as easily as other VPN use because it will keep bouncing from system to system until a connection is established. Also, unlike other VPN apps, Orbot doesn’t render any advertisements in its interface. Orbot users trade fast browsing speed for assurance that their activity isn’t logged, however, because Tor routing significantly reduces internet routing speeds. 

* Coinjoin/Mixing'
* Transaction histories on all public blockchains are easily auditable. Coinjoining, or mixing, is a simple way for miners to protect their financial privacy by obscuring the history of their holdings. Sometimes referred to as “cleaning” by privacy advocates, the mixing process prevents blockchain data watchers from following where coins originated and accessing their full transaction history. Users should note that mixing is often used interchangeably with "tumbling" and "coinjoin." "Tumbling" is an older technique where users give up custody of their coins and hopefully receive coins with a different history. In this article, we will use the term "mixing" in reference to "coinjoin" transactions.
* A coinjoin is a multi-party transaction where several senders contribute coins to a mix and receive the same amount of bitcoin to complete the transaction. After a mix has completed, a blockchain watcher cannot know which transaction output is linked to an input. Coinjoin transactions are non-custodial and do not require trust or handing over keys like tumbling.
For optimal privacy, consistent and multiple remixes are ideal. Why does this matter? One round of coinjoin breaks deterministic links (separates the coins from its history), but, remixes increase a user’s anonymity (anon) set. 
* It is also possible to mix directly into cold storage. Please see the Sparrow guide linked above, or if you prefer using the full Samourai stack, please see this guide written by @Diverter_noKYC.
* Coinjoining is not risk-free. Past transaction histories are not erased per se; only forward-looking privacy is achieved for mixed coins. Similarly, mixing does not undo a KYC event, meaning that an owner’s name is still recorded as belonging to past transaction history from when coins were used or purchased or spent. But mixing provides a sort of clean slate for users wishing to disconnect future use from past transaction histories. 
* Centralized cryptocurrency exchanges also represent another barrier for using mixed coins. Most exchanges flag deposits made from external addresses with mixed transaction outputs that can occur during mixing. Transferring or selling coins through peer-to-peer markets or other KYC-free platforms, however, is rarely restricted. Setting aside some amount of non-mixed bitcoins is a good practice to have the option of using services that reject mixed coins if necessary.

* Tools for Coinjoining

* Samourai's Whirlpool: A full zerolink coinjoin implementation. Users pay a fee to use the service. For optimal privacy, users should run their own Dojo or RoninDojo with Whirlpool.  Sparrow wallet also offers an implementation of Whirlpool. https://www.samouraiwallet.com/whirlpool https://bitcoiner.guide/whirlpool/
*
* Joinmarket: This implementation is structured as a maker/taker approach, by creating a marketplace for coinjoins. The takers pay for coinjoins because they require them on demand. The makers provide the coinjoin liquidity and are compensated with a fee. Takers construct a mix and get to see the relationship between inputs and outputs, unlike the blinded whirlpool coordinator. This offers the takers an added layer of privacy. https://github.com/JoinMarket-Org/joinmarket-clientserver https://www.keepitsimplebitcoin.com/joinmarket/ 
*
* Off-grid Communication

* GoTenna mesh: a consumer ready solution that users can use to create mesh networks with the goTenna devices and their smartphones. This can be done anywhere. Users can exchange messages with eachother in the event of an internet outage https://gotennamesh.com/
* GoTenna mesh can also be used with the TxTenna app to broadcast bitcoin transactions without internet access. 
* Equipment: goTenna app, txTenna app – download from github, goTenna mesh devices (min 2), and Samourai wallet installed on sender and receiver’s phones.
* Step 1 - mesh set up in goTenna app: Install goTenna app and follow instructions to set up your goTenna mesh device , watch for indicator light on the goTenna mesh to pulse (this means it’s ready for pairing), close this app and make sure the mesh device is not paired to it. Finally, switch to txTenna app.
* Step 2 - Download txTenna & build a transaction (txn)
* Download Txtenna (on mobile): open this link https://github.com/remyers/txTenna/releases, click on ‘Beta 0.96’ -> assets -> app production APK, once that APK is downloaded just click on it to install
* Step 3 - Open and set up txTenna app: click on dots symbol -> settings -> geographical region (both phones pairing w/ goTenna need to be set to the same region). To pair w/ mesh: power on -> click wifi symbol -> pair device. When paired you will see a green dot, click on it, if goTenna device blinks you’re good
* Step 4 - Building a transaction with offline phone: open samourai -> settings -> transactions -> uncheck ‘broadcast transactions’, send a txn: click ‘+’ -> send -> fill info -> click show QR code -> copy to clipboard, open txTenna -> click ‘+’ -> goTenna mesh, paste hex from clipboard
* In the txTenna app, you’ll see the txn status pop up and change from ‘relayed via goTenna mesh network’ to ‘broadcast to bitcoin network’. To check Txn status: click ‘explore’ or use http://mempool.space via Tor and search by txid. The receiver will have the ‘explore’ option
*
* How to download maps in GoTenna for offline use: download goTenna app from app store, search by city or zip, under topographic maps at the bottom, hit the download button, and adjust the area on the map that you would like to download. To access downloaded maps: click dots menu -> my maps
* Using goTenna mesh devices with Txtenna is a great way to transact in a censorship resistant way. This isn't practical for day to day txns but it would work well in emergency situations or smaller towns. 



### Summary
* People residing in low bandwidth areas can use the above technologies to communicate with each other in the event of an internet outage. They should also utilize the above tools when using bitcoin if their country's government, local political groups or legacy finance system are unfriendly towards the cryptocurrency.
