### Flow Bitcoin Wallet

I discontinued this project because Sparrow has all the features I was after. Although I don't like the Sparrow UI, I can't compete with the robustness of the application. Additonally, Sparrow supports far more hardware wallets than I can host without rewriting HWI in native Rust code. In any case, I decided to publish the code as a personal reference and proof of knowledge. The wallet was designed to:
- Store any number of hardware wallet details (fingerprint, xpub)
- Cache and fetch the most recently (un)used change and recieve addresses
- Cache and fetch a transaction history
- Generate and download partially signed bitcoin transactions (PSBT) by file 
- Broadcast a signed PSBT to the network with an Electrum server
- Fetch mempool and fiat price data
