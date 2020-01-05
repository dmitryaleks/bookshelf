# Notes on "Advances in Financial Machine Learning" (De Prado, 2018)

## Market Microstructure

### Round-sized trades frequency

There is a tendency for round-sized trades to happen disproportionally more often than non-round-sized trades of a similar size. This phenomenon is believed to be associated with human traders using GUI for trading.

One hypothesis is that if proportion of round-sized trades raises in comparative terms for a given instrument, there is a chance that there is a long-term sentiment in the market (as human traders trade based on fundamentals) that can affect the price trend, while if the trading is dominated by "silicon" traders that generally have no long-term sentiment and price is more likely to trend sideways (horizontal trend).

### Irregularly dense trading activity during first seconds of a minute and first minutes of an hour

Some low-frequency trading algorithms that split a large order over a prolonged period of time may be putting slices on the market in a fashion that results in a predictable pattern that could be exploited for purposes of getting a better execution price by other market participants.
