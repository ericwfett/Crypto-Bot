# Crypto-Bot
Cryptocurrency Bot that arbitrages profitable price discrepancies  

We will start with Binance as our first exchange

Binance API documentation: https://github.com/binance-exchange/binance-official-api-docs

Since cryptoprices are extremely volatile, we will only use trading pairs that involve USDT (a "cryptocurrency" pegged to the dollar)

## What is triangular arbitrage and how will we use it?

Triangular arbitrage (also referred to as cross currency arbitrage or three-point arbitrage) is the act of exploiting an arbitrage opportunity resulting from a pricing discrepancy among three different currencies in the foreign exchange market.

Example: USDT-BTC ask price for one BTC (very temporarily and at a small volume) may be $6400, 1 BTC-ETH may be worth $6500, so we make the second trade into ETH and then convert it back to USDT; therefore we just net $100. Though, our bot will also have to account for the trading fee because the volume of those price disrecpencancies may only be possible at a certain minimum volume.

@Deip - if I am misunderstanding the idea or you just want to build out this README further, please feel free
