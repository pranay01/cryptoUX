# cryptoUX
Repository for improving user experience for crypto - primarily focusing on private key management and onboarding

## Private Key Management
Some projects which are working in the same space:
* [Gnosis Safe](https://safe.gnosis.io)
* [WalletConnect](https://walletconnect.org/) - It’s an open-source project that enables desktop Dapps to interact with mobile Wallets.
* Shamir's Secret - Sharded private keys with friends which enables authentication only when n-out of-m  keys are available

### Alternative Mechanisms
* [Project at ETHBerlin](https://devpost.com/software/ethstonia-identity) - Using private key enabled Govt ID (Estonia Govt ID) for login?   
* [Proposal](https://github.com/ethereum/EIPs/pull/1078) by Alex van de Sande - Login with ENS subdomains
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

Can U2F keys be used as crypto private key hardware wallets? What are the security issues involved?


