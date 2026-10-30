# MetalsAlpha open data

Daily premium, buyback and ranking data for UK bullion dealers, collected by
MetalsAlpha from dealers' own published prices. Licence: CC BY 4.0. Please
attribute "MetalsAlpha (metalsalpha.com)".

Method and definitions: https://www.metalsalpha.com/how-we-measure

Files:
- daily-product-stats.csv: per product per day, cheapest dealer, premium, best buyback, headline round trip
- dealer-rankings.csv: daily dealer ranking with normalised factor scores and applied weights
- spot-hourly.csv: hourly average spot in GBP and USD per troy ounce, our own readings
- spot-monthly-history.csv: monthly average spot since 1975 for gold, silver and platinum, from World Bank Commodity Price Data (CC BY 4.0) converted at Bank of England monthly rates; stored separately from our readings
- dealer-readings-last-7-days.csv: every validated dealer reading from the last 7 days (the full history is in this repository's commit history)

Premiums and round trips are fractions (0.026 = 2.6%). Times are UTC.
Exported 2026-10-30T19:45:23.309Z.
