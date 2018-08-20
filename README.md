# Crypto-Bot
Cryptocurrency Bot that arbitrages profitable price discrepancies  

We will start with Binance as our first exchange

Binance API documentation: https://github.com/binance-exchange/binance-official-api-docs

Since cryptoprices are extremely volatile, we will only use trading pairs that involve USDT (a "cryptocurrency" pegged to the dollar)

Example: USDT-BTC ask price (very temporarily and at a small volume) may be $6400 and bid price may be $6350, our bot will make those two trades instantaneously. Though, our bot will also have to account for the trading fee because the volume of those prices may only be $0.20 and potentially not worth executing.

@Deip - if I am misunderstanding the idea or you just want to build out this README further, please feel free
