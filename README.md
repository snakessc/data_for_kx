# Sample Data

## Cleaning instruction:
### 1. Align Timestamps format and sort
### 2. Align Columns fields
### 3. Delete duplications
### 4. Deal with Timezone


## Asset Classes:
1. FX
2. Equity
3. Future
4. Bond

## FX Schema in TICK folder
| ticker     | Date     | tick                               | 
|------------|----------|------------------------------------|
| ABC Curncy | yyyymmdd | timestamp, bid, ask, trade, volume |  
| DEF Index  |          |                                    |  
| GHI Govt   |          |                                    | 

## Equity Schema in TICK folder

| ticker            | Date     | tick                               | static                                      | 
|-------------------|----------|------------------------------------|---------------------------------------------|
| AB Country Equity | yyyymmdd | timestamp, bid, ask, trade, volume | px_adjustment_factor, <br/>vol_adjustment_factor |

## Future Schema in TICK folder

| ticker    | Date     | Contract    |tick                               | static                                                               | 
|-----------|----------|-------------|-----------------------------------|----------------------------------------------------------------------|
| AB Comdty | yyyymmdd | ABZ1 Comdty |timestamp, bid, ask, trade, volume | PX_Open,PX_High,PX_Low,Last_Price,Volume,<br/>FUT_CUR_GEN_TICKER,OPEN_INT |

## Bond Schema in TICK folder

| ticker    | Date     | ohlc                                                                                                          | 
|-----------|----------|---------------------------------------------------------------------------------------------------------------|
| ABC Corp  | yyyymmdd | PX_BID,PX_MID,PX_ASK,PX_DIRTY_BID,PX_DIRTY_MID,PX_DIRTY_ASK,PX_LAST, <br/>YLD_YTM_BID,YLD_YTM_MID,YLD_YTM_ASK |


## FX/Index 1m, 1h, 1d data in BAR folder

| ticker           | Date     | ohlc  | 
|------------------|----------|-------|
| OANDA_EURUSD.csv | yyyymmdd | OHLCV |



Note:
* Word in capital letters are fields in BBG 


