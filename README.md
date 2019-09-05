|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

Whaleex public api endpoint
Endpoint 1 : https://www.whaleex.com/BUSINESS/api/v2/public/assets
|S/N	|Field Name	|Example(s)	|Status|
|----|----|----|----|
|1	  |<key>	    |BTC, ETH	  | Mandatory|
|2	  |	lastUpdateTimestamp	|2019-06-14T16:46:10.000Z	|Mandatory|
|3	  |	name	|Bitcoin, Ethereum	|Mandatory  | 
|4	  |	id    |1	                |Recommended|
|5	  |	canWithdraw|	True/False	|Recommended|
|6	  |	canDeposit |	True/False	|Recommended|
|7	  |	minWithdrawal |	0.01	    |Recommended|


Endpoint 2: https://www.whaleex.com/BUSINESS/api/v2/public/ticker
S/N	Field Name	Example(s)	Status
1	lastUpdateTimestamp	2019-06-14T16:46:10.000Z	Mandatory
2	tradingPairs (base_quote format)	ETH_BTC	Mandatory
3	LastPrice	0.01	Mandatory
4	lowestAsk	0.01	Mandatory
5	highestBid	0.01	Mandatory
6	baseVolume24h	10000	Mandatory
7	quoteVolume24h	100	Mandatory
8	tradesEnabled	True/False	Mandatory

 
Endpoint 3: https://www.whaleex.com/BUSINESS/api/v2/public/trades/IQ_EOS
S/N	Field Name	Example(s)	Status
1	<Market Pair>	ETH_BTC	Mandatory
2	tradeID (generated by exchange)	28457	Mandatory
3	price	0.01	Mandatory
4	baseVolume 	50	Mandatory
5	quoteVolume 	1.2	Mandatory
6	time	2019-06-14T16:46:10.000Z	Mandatory
7	isBuyerMaker	True/False	Mandatory



Endpoint 4: https://www.whaleex.com/BUSINESS/api/v2/public/depth/IQ_EOS
S/N	Field Name	Example(s)	Status
1	lastUpdateTimestamp	2019-06-14T16:46:10.000Z	Mandatory
2	bids: [PRICE]	4.00000000	Mandatory
3	bids: [QTY]	431.00000000	Mandatory
4	asks: [PRICE]	4.00000200	Mandatory
5	asks: [QTY]	12.00000000	Mandatory

