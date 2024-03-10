# 🤖 Autocompunding

Autocompounding

### The basics of liquidity provisioning <a href="#the-basics" id="the-basics"></a>

LP positions in Uniswap V3 earn fees while swaps happen within their selected price ranges. However, these fees do not accumulate inside the pool, but in a separate balance for each position. One consequence of this is that fees are not compounded automatically as liquidity back into the position.

If a liquidity provider wants to compound accrued fees back into their position, they need to collect these fees, possibly swap them to the correct ratio given the position range and current pool tick, and add these possibly swapped amounts back into the position.

The Yield Protocol AutoYield revolutionizes new features for LPs and allows them to automate the compounding of the accrued fees in exchange for a fixed percentage of the compounded fees. This serves to incentivize a maximum number of compounds at optimal times with regards to gas costs.

Depending on the fee APR and size of your position this can significantly improve your returns.

![](https://images.unsplash.com/photo-1555774698-0b77e0d5fac6?crop=entropy\&cs=tinysrgb\&fm=jpg\&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHwyfHxhcHB8ZW58MHx8fHwxNjYwNTgzMzQz\&ixlib=rb-1.2.1\&q=80)
