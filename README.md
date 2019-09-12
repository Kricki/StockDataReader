# StockDataReader
Read historic stock data

## Installation
StockDataReader can be installed from PyPi:
````
pip install stockdatatareader
````

Alternatively, clone or download the repository and install the package with the same command.

## Example
Read the stock values from Alphabet (ISIN US02079K1079) from January 1, 2018 to September 15, 2018.
````python
from stockdatareader import StockDataReader

sdr = StockDataReader()
isin = 'US02079K1079'
start_date = '2018-01-01'
end_date = '2018-09-15'
stock_data = sdr.read_data(isin, start_date, end_date)
````
