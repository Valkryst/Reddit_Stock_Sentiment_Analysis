This project is a PoC to determine whether Reddit threads could be used to determine future price changes of stocks and mutual funds. From my limited tests with VADER sentiment analysis, this idea does not appear to work, but it may be possible with a more advanced form of analysis.

## Usage

1. Run the `download_data.ipynb` script to download lists of stock and mutual fund symbols.
2. Run each code block in `main.ipynb`, in order, to generate a queryable SQLite database.

## Dependencies

```bash
pip install --upgrade pmaw
pip install --upgrade pymongo
pip install --upgrade vaderSentiment
```

## Misc.

* https://www.nasdaqtrader.com/trader.aspx?id=symboldirdefs