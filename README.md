# Comparative Analysis of Social Media Sentiment and Stock Price Correlation: NextEra (NEE), Palantir (PLTR), Procter and Gamble (PG), Nvidia (NVDA), and Tesla (TSLA)
An in-depth exploration of the intricate relationship between social media sentiment and stock price movements.

This study investigates the intricate relationship between social media sentiment, specifically on the StockTwits platform, and the fluctuations in stock prices for five prominent companies: Procter & Gamble (PG), NextEra (NEE), Nvidia Corporation (NVDA), Palantir (PLTR), and Tesla Inc (TSLA). Using statisti-cal tools like the Spearman Correlation Coefficient and P-Values, the analysis quantifies these connec-tions over a substantial period from June 1, 2020, to June 30, 2023, encompassing a dataset of 4,160,867 tweets pertaining to these corporations. The research unveils distinct correlation patterns among these entities, shedding light on their varying susceptibilities to social media sentiment fluctua-tions. Procter & Gamble and NextEra exhibit "Very Weak" correlations, suggesting minimal impact of social media sentiment on their stock prices. In contrast, Nvidia Corporation shows a "Weak" correlation, implying sentiment's role alongside other factors in shaping stock prices. Palantir demonstrates a "Mod-erate" correlation, indicating a noticeable influence of social media sentiment, while Tesla Inc stands out with a "Moderate to Strong" correlation, underscoring significant sentiment impact on its market perfor-mance. These findings provide valuable insights for investors and financial analysts, highlighting the importance of comprehending varying degrees of susceptibility among these companies to social media sentiment fluctuations. Companies with weaker correlations may continue relying on conventional mar-ket drivers, while those with stronger correlations, like Tesla Inc, emphasize the need for vigilant moni-toring of online discussions and public perception. In conclusion, this research underscores the multifac-eted relationship between social media sentiment and stock price movements among leading compa-nies, stressing the significance of considering sentiment in financial analysis alongside other critical market drivers, within the ever-evolving financial landscape.

## Methodology Flowchart
![Thesis_Methodology](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/0adac11e-eb70-4f76-93f5-c0863ea5fab5)

 
The research process is visually represented in the above Figure through the Methodology Flowchart.
## Social Media Data – StockTwits

The following table demonstrates that the number of collected tweets varies for each company. In total I gathered 4,160,867 tweets. Notably data collection for Palantir began on October 1st, 2020, due to its IPO on September 30th (Levy, 2020). Among these selected companies is NextEra (NEE) with the tweet count of 13,585 tweets while Tesla (TSLA) leads with a count of discussion on the StockTwits platform, with a total of 2,911410 tweets.

![Tweet_count](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/67e667cc-8744-4557-8fc8-33f430d18bcb)

## NextEra (NEE)

To sum it up when looking at NextEra we can observe a very weak positive correlation, between daily sentiment scores and daily stock price changes. This means that as sentiment increases there is a mi-nor tendency for stock prices to show some positive movement. The presence of the associated regres-sion line, which has a slightly upward slope further supports the idea of a noticeable yet relatively weak positive connection, between daily sentiment scores and daily stock price changes.
![NEE_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/3ba5faff-a3c8-46e3-990c-dd3a3391b258)

## Palantir (PLTR)
To summarize based on a Spearman correlation coefficient of 0.4786 and a low p value of 0.000000 for Palantir (PLTR) we can conclude that there is a significant and moderate positive correlation, between daily sentiment scores and daily stock price changes. The data indicates that when there is a rise, in sentiment expressed in social media conversations it is likely that Palantir's stock prices will also show a trend. Additionally the presence of a regression line with a slope supports the idea that there is a moder-ate positive connection between daily sentiment scores and daily changes, in stock prices.
![PLTR_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/63d378d8-b43e-499e-994a-5db1841dea69)

## Procter and Gamble (PG)
To summarize the Spearman correlation coefficient of 0.1062, along with the p value of 0.003077 for Procter and Gamble (PG) indicates a significant but relatively weak positive correlation between daily sentiment scores and daily stock price changes. Moreover the presence of a regression line with an slope further supports the notion of this apparent yet somewhat modest positive association, between daily sentiment scores and daily stock price changes.
![PG_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/17c97188-9b20-4895-bba8-d71f6520c111)

## Tesla (TSLA)
To summarize the Spearman correlation coefficient of 0.4991 along with the p value of 0.00000 for Tesla Inc (TSLA) indicates a statistically significant and moderately strong positive correlation between daily sentiment scores and daily changes in stock prices. This correlation suggests that as sentiments in so-cial media discussions increase with positive sentiment there is a tendency for Tesla stock prices to move in a positive direction. Additionally the presence of a sloping regression line further supports this relationship shedding light on the significant impact of social media sentiment, on Tesla stock price dy-namics and market behavior.
![TSLA_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/39313288-567b-4aa7-a2a5-4ac24671f59d)

## Nvidia (NVDA)
To sum it up when we look at the Spearman correlation coefficient of 0.3018 and the p value of 0.00000, for NVIDIA Corporation (NVDA) it suggests that there is a statistically significant but somewhat weak positive relationship between daily sentiment scores and daily stock price changes. This means that as positive sentiment in social media discussions goes up we might see a slight inclination, for NVIDIAs stock prices to move in a direction although the connection is not particularly strong.
![NVDA_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/5c4beb8b-5474-4426-942d-7e06aabc1ec0)





