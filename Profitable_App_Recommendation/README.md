# Profitable App Recommendation

This project looks into the IOS and Google Play store to analyze which genre shows potential to be a profitable market.

## Cleaning the IOS and Google Play Store

1. The dataset for both IOS and Google Play store contained duplicate which would alter our analyze. Therefore, we cleaned the data for duplicates not randomly but the app with the highest total review.

2. We also removed apps with non-english characters, due to the recommendation being marketed to those who speak english.

3. Since our project is to find a "profitable app", we only took into consideration non-free apps.

## Analyzing the Remaining Dataset

The process of analyzing our datasets was to find:
* A niche market that is not dominated by a small number of competitors 
* High user rate using "average installs" (for Google Play store) and "average number ratings" (for IOS)
