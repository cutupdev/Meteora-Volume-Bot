
# Updated Meteora Volume Bot

This is volume bot on meteora that designed to boost volume on meteora pool to give basic understanding about volume bot on meteora, automate the distribution of SOL to multiple wallets and execute endless buy / sell / swap transactions. It leverages Solana's blockchain technology to perform these operations efficiently. To get advanced full version, feel free to contact with me [Whatsapp: https://wa.me/13137423660, Telegram: https://t.me/DevCutup, X: https://X.com/januscutup]


## Features
- **Automated SOL Distribution**: Distributes SOL to new wallets.
- **Endless Buy and Sell Swaps**: Performs simultaneous buy and sell transactions.
- **Swap with Jupiter V6**: Swap is performed with Jupiter V6 swap aggregator.
- **Configurable Parameters**: Allows customization of buy amounts, intervals, distribution settings, and more.

## Improvements
- **Transferring SOL to new wallet**: After buying and selling in one wallet, it transfers SOL to a newly created wallet and continues buying and selling there.
- **Maker increase**: New wallets are created every round of buying and selling, increasing the number of makers.
- **Sell before gather**: When gathering, if there are tokens left in the wallet, it sells the tokens first and gathers only SOL (the token account rent of 0.00203 SOL is reclaimed).
- **More buys than sells**: It randomly buys twice with SOL in the wallet and sells all tokens after some time, making the number of buys twice as many as sells, thus creating more buy pressure.