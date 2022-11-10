# CryptoLedger


Given no parameters, returns the latest portfolio value per token in USD
Given a token, returns the latest portfolio value for that token in USD
Given a date, returns the portfolio value per token in USD on that date
Given a date and a token, returns the portfolio value of that token in USD on that date
The CSV file has the following columns

timestamp: Integer number of seconds since the Epoch
transaction_type: Either a DEPOSIT or a WITHDRAWAL
token: The token symbol
amount: The amount transacted
