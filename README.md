# data_for_kx
## Asset Classes:
1. FX
2. Equity
3. Future
4. Bond

## FX Schema
| ticker     | Date     | tick                               | 
|------------|----------|------------------------------------|
| ABC Curncy | yyyymmdd | timestamp, bid, ask, trade, volume |  
| DEF Index  |          |                                    |  
| GHI Govt   |          |                                    | 

## Equity Schema

| ticker            | Date     | tick                               | static                                      | 
|-------------------|----------|------------------------------------|---------------------------------------------|
| AB Country Equity | yyyymmdd | timestamp, bid, ask, trade, volume | px_adjustment_factor, <br/>vol_adjustment_factor |

## Future Schema

| ticker    | Date     | tick                               | static                                                               | 
|-----------|----------|------------------------------------|----------------------------------------------------------------------|
| AB Comdty | yyyymmdd | timestamp, bid, ask, trade, volume | PX_Open,PX_High,PX_Low,Last_Price,Volume,<br/>FUT_CUR_GEN_TICKER,OPEN_INT |

## Bond Schema

| ticker    | Date     | ohlc                                                                                                          | 
|-----------|----------|---------------------------------------------------------------------------------------------------------------|
| ABC Corp  | yyyymmdd | PX_BID,PX_MID,PX_ASK,PX_DIRTY_BID,PX_DIRTY_MID,PX_DIRTY_ASK,PX_LAST, <br/>YLD_YTM_BID,YLD_YTM_MID,YLD_YTM_ASK |

