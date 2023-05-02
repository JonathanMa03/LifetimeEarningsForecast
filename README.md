# Lifetime Earnings Forecast
## Jonathan Ma, RUC School of Business
## Optimisation and Spreadsheet Modelling
Python program that uses the Holt-Winters Exponential Smoothing method to forecast lifetime earnings for the next "n" periods given previous 10 periods of data, utilising NumPy, Pandas, and statmodels. Tested using the PyCharm IDE
## 
When feeding the model nine years worth of income data (65000, 66500, 67000, 67000, 67200, 67500, 67500, 68000, 70000), the output gives 40 years of output data:
|Lifetime Earnings (n=40)| | | | |
|---------------|---------------|---------------|---------------|---------------| 
| Year 1: 68852 | Year 2: 68913 | Year 3: 69409 | Year 4: 69807 | Year 5: 70173 |
| Year 6: 70234 | Year 7: 70729 | Year 8: 71128 | Year 9: 71494 | Year 10: 71554 |
| Year 11: 72050 | Year 12: 72449 | Year 13: 72815 |Year 14: 72875 |Year 15: 73371|
| Year 16: 73769| Year 17: 74136| Year 18: 74196| Year 19: 74692| Year 20: 75090 |
| Year 21: 75457| Year 22: 75517| Year 23: 76013| Year 24: 76411| Year 25: 76777 |
| Year 26: 76838| Year 27: 77334| Year 28: 77732| Year 29: 78098| Year 30: 78159|
| Year 31: 78654| Year 32: 79053| Year 33: 79419| Year 34: 79479| Year 35: 79975|
| Year 36: 80374| Year 37: 80740| Year 38: 80800| Year 39: 81296| Year 40: 81694|
## Total Lifetime Earnings: $84728312
