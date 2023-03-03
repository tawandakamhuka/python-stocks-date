# Using Python to find the best day to buy stocks

For this project, the famous "Weekend effect" is put to the test. The weekend effect is a theory created by financial investors stating Monday's are the best days to buy stocks as the value is at the lowest and they are most likely to perform the best.

#### Two methods were used during this project:
##### Method 1: Average dip value
- Found the average of the difference between opening values for consecutive days. This metric became the average dip value for each day. 

##### Method 2: Backtester
- Created a function which simulated a trade with any given value for each day of the week, and returned the total returns by weekday. 

Dataset: https://finance.yahoo.com/quote/VOO/history?p=VOO

#### Contributing
If you find any bugs or issues with this script, please feel free to open an issue or submit a pull request.
