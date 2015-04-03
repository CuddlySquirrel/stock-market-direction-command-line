This is a ruby application.
It is executed at the command line and displays the general stock market direction according to the CAN SLIM algorithm using a market index (defaults to NASDAQ, SNP is used if first arg is "1").

It connects to finance.yahoo.com and grabs the general market index data (closing price and volume) as a CSV file, which is parsed and loaded into MongoDB.  Calculations are performed and a report is displayed.

The code was written in an evening and it works.  It's not meant to conform to any methodologies or best practices.  It's meant to be written in an evening and work forever.  It's worked for years and has never required any modification.




