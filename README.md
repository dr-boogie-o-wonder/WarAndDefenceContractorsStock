# WarAndDefenceContractorsStock

This is a Python program that displays a visual correlation between defence contractor's stock and mentions of war on the subreddit r/news. It then saves the charts as .html files for later use.

Using Yahoo Finance API, this program retrieves stock data given the tickers of the US's Top Five Largest Defence Contractors who recieve over 65% of their revenue from weapon's sales. It then creates a direct index from these companies and charts their closing price for each day. The program also uses PushShift API to scans the subreddit r/news for any posts which contain the title word "War" or "Wars." It then charts its findings in hopes of the user being able to find some visual correlation between the two charts. All charts are saved as .html files.
