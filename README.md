# Introducing the Most Protocol

Is a decentralized central bank possible? We love Basis and Ampleforth's original vision of creating an adaptive monetary system on the blockchain. The Most protocol aims to achieve this challenge and bring the algorithmic-stable token into the crypto world in a fully trustless manner.

According to the Quantity Theory of Money, high prices that are constantly rising mean that people are too willing to spend money. To restore prices, we could restrict people from having less money. Similarly, the opposite applies to deflation, which makes people unwilling to spend money.

This theory clearly shows that Ampleforth implements exactly the opposite rule, making it unable to stabilize the price. In contrast, the Most protocol works in the reverse way of Ampleforth, aka deflating supply when the price is above `$1`, and inflating supply when the price is below `$1`.

Our mechanism might sound counter-intuitive; it aligns with the economic principles and addresses the Ampleforth's system design flaw. On the one hand, when the price is above `$1`, that means MOST tokens are highly demanded in the market. The total supply of MOST tokens will deflate across all MOST holders. This deflation mechanism will incentivize MOST holders to sell tokens to people who need them. On the other hand, when the price is below `$1`, it indicates that MOST tokens are over circulated in the market. The total supply of MOST tokens will inflate across all MOST holders. This inflation mechanism will encourage people to buy and hold MOST tokens, which contracts the money supply circulated in the market. Overall, the Most protocol is programmed to seek a stable stage so that the MOST token price will stay at `$1`, where DEFI products can safely use the MOST token without worrying about its price volatility.

## Initial Token Supply

The Most Protocol will be launched with an initial supply of `1 million` MOST tokens. `5%` of team allocation is locked in a TimeLock contract for one year. `95%` of MOST tokens will be added into Uniswap MOST/USDC trading pair for purchase gradually. We will also lock the Uniswap LP tokens in a TimeLock contract for one year.

## Permissionless Money

No token sale, small team allocation, let MOST be permissionless money that nobody controls. We do our best to ensure that this is a fully decentralized and non-stoppable monetary system since the protocol launch.

## Native Oracle

For price feed, the Most Protocol utilizes native Uniswap `MOST/USDC` trading pair price information as an oracle. The Most protocol is thus self-contained without relying on any external third-party oracle, making the Most protocol an autonomous protocol.

## Supply Change Stages

**Stable Supply Stage**: When the oracle rate is between `$1.06 - $0.96`, there is no rebase, thus no change in supply.

**Inflation Supply Stage**: When the oracle rate is below `$0.96`, there is a positive rebase, thus supply increases. The inflation rate is: `(1 - oracle_rate) / 10` (Maximum `10%` inflation rate).

**Deflation Supply Stage**: When the oracle rate is above `$1.06`, there is a negative rebase, thus supply goes down. The deflation rate is: `(oracle_rate - 1) / (oracle_rate * 10)` (Minimum `-10%` deflation rate).

## Channels
Please join our community for more information about the following protocol launch.
- [Official Website](https://mostprotocol.org)
- [Twitter](https://twitter.com/MostProtocol)
- [Telegram](https://t.me/MostProtocol)
- [Blog](https://medium.com/@mostprotocol)
- [Github](https://github.com/MostProtocol)
