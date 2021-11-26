# stock-price-prediction
predict stock price by using LSTM and ARIMA    

## data source: tushare package of python     
1) related codes:     
import tushare as ts    
ts.get_k_data(code='sh', ktype='D', autype='qfq', start='xxxx-xx-xx', end='xxxx-xx-xx')     
