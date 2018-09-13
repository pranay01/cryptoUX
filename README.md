# cryptoUX
Repository for improving user experience for crypto - primarily focusing on private key management and onboarding

## Private Key Management

### Why is private key management tough?
 Cyber security is mentally taxing. Though physical security is also mentally taxing, that’s why we have locks, frisking, etc , but we have learned to accept them and they are part of our day to day lives.
 * Fingerprint based office entry solutions 
 * Frisking by guards before entering
 * Security guards in apartments 
 
 We are just not used to threat in cyber realm and don’t want the pain to secure it. This is at odds with the current practice of increasing amount of value and wealth in cyber domain. Most of us spend large number of waking hours in the cyber space - working on laptops, talking on mobile, chatting, etc. Large part of our wealth currently is secured in banks/funds which we interact digitally using websites/apps. With the increasing adoption of crypto, we will now also be responsible for securing our wealth. Hence, learning about cyber security is fundamental for the times to come.

 Also, as engineers and product designers we should strive to make this shift in need for cyber-security frictionless, so that more and more people can transition to this new paradigm.

 ### Projects
 Some projects which are working in the same space:
* [Gnosis Safe](https://safe.gnosis.io)
* [WalletConnect](https://walletconnect.org/) - It’s an open-source project that enables desktop Dapps to interact with mobile Wallets.
* Shamir's Secret - Sharded private keys with friends which enables authentication only when n-out of-m  keys are available

### Alternative Mechanisms
* [Project at ETHBerlin](https://devpost.com/software/ethstonia-identity) - Using private key enabled Govt ID (Estonia Govt ID) for login?   
* [Proposal](https://github.com/ethereum/EIPs/pull/1078) by Alex van de Sande - Login with ENS subdomains - [Code](https://github.com/status-im/contracts/blob/73-economic-abstraction/contracts/identity/IdentityGasRelay.sol)
* [Tenzorum](https://tenzorum.org/) - Key Management protocol for decentralised web

### Identity/Biometric based mechanisms
What are the issues with tying private keys with Identity?
* [Based on Identity contracts](https://github.com/EthWorks/EthereumIdentitySDK)
* [Biometric based using fuzzy extractor](https://www.notion.so/Design-Spec-fa2b4e36d1b74d56bfca7a5062aa5faf) - Biometric based methods though suffer from privacy issues (biometrics can be extracted from public sources) and also are more amenable to rubber hose attack (using coercion to obtain biometrics) 
* [Using Iris scan to generate private key](https://www.ncbi.nlm.nih.gov/pubmed/18784013) 

### Software Wallets
* [MyCrypto](https://mycrypto.com/) - Web and Desktop based wallet App
* [TrustWallet](https://github.com/TrustWallet)
* [Edge](https://edge.app/) - Android/iOS based wallet
* [Parity Signer](https://play.google.com/store/apps/details?id=com.nativesigner&hl=en_IN) - Still unreleased (Sept 11, 2018). App last updated on July 2017 | 
  [Github Repo](https://github.com/paritytech/parity-signer) - In active development

### Hardware wallets
* Paper wallets
* Crypto Steel
* Trezor/Ledger Nano
* [Ethercards](https://ether.cards/) - Physical Ether gift cards

Can U2F keys be used as crypto private key hardware wallets? What are the security issues involved?

### Instructive Videos
* [Login, Identity and Wallets session at Berlin - July'18](https://view.ly/v/ZICBx62MbHdh)

* [Universal Login for Ethereum by Alex van de Sande - May'18](https://www.youtube.com/watch?v=qF2lhJzngto) 

* [Dapp UX and Adoption - Council of Berlin](https://view.ly/v/tWsj3yLPeUR8)
  + Represents learning from different teams on UX adoption
  + Summary - Keep it simple. Relevant. Give value before asking for email etc.

* [Nik Page on Experience Design for Crypto adoption](https://www.youtube.com/watch?v=pMZ0FHtgXho)

   ####Summary
   1. Very similar to Internet in 1990s (only 2.7 mn people on Internet)
   2. Current dApp designs primarily for dev/geeks. Scares away normal people
   3. Users can't be expected to secure private keys/ mnemonic phases when they are going on with their lives. All these complexities need to be abstracted aways
   4. Design for experience and emotion - important if 

* [Building UX @Status - Early lessons from the field](https://www.youtube.com/watch?v=1Si7QmNOb_8)


### Working Groups
* [ Identity Foundation working groups](http://identity.foundation/working-groups)
* [ UX Ring at Fellowship of Ethereum Magicians](https://ethereum-magicians.org/c/working-groups/User-Experience)

### Instructive Blogs and Posts
* [ Understanding decentralised identity - Sept'18](https://thecontrol.co/understanding-decentralized-identity-433abb343279)
* [Twitter post by @CharlieShrem on crypto mass adoption](https://twitter.com/CharlieShrem/status/1009046658661994496)


