# futures arbitrage scanner

real-time crypto futures arbitrage scanner, built in go and plain javascript. connect to multiple exchanges right at the websocket layer. shows live price gaps and where the spread hides.


- connect to 5 spot/futures exchanges (binance, bybit, hyperliquid, okx, gate.io) over websockets
- live arbitrage matrix: highlights when the price difference is big enough
- watch multiple pairs: btcusdt, ethusdt, xrpusdt, solusdt
- auto adjusts decimals by asset/price
- live uplot charts
- spot and alert on inefficient price gaps, in real time


