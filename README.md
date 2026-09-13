# DestinationEconomics Data — Cambodia & Ethiopia Tourism Intelligence

Public, machine-readable data from the **DestinationEconomics** destination intelligence program.

**Live dashboards:**
- Cambodia Sentiment: https://data.destinationeconomics.com/cambodia-sentiment.html
- Cambodia Airlift: https://data.destinationeconomics.com/airlines-cambodia.html
- Ethiopia Sentiment: https://data.destinationeconomics.com/ethiopia/sentiment.html
- Ethiopia Airlift: https://data.destinationeconomics.com/ethiopia/airlift.html

## What this is

Weekly destination intelligence series, machine-readable for research, citation, and AI-agent consumption:

- **Cambodia Tourism Sentiment Index** — weekly category scores (safety, value, temples/culture, service, visa friction, food & culinary). Scale 1–10 (1–4 negative, 5–7 mixed, 8–10 positive). Signals from news, social media, forums, and reviews.
- **Cambodia Airlift** — weekly international route counts by airport (Phnom Penh KTI, Siem Reap SAI, Sihanoukville KOS) + operating carriers, from schedule data.
- **Ethiopia TSI-8 Sentiment** — weekly TSI-8 category scores (Culture & History, Access, Outdoor, Food, Amenities, Destination Services, Relaxation, Safety), 1–10.
- **Ethiopia Airlift** — weekly Addis Ababa (ADD) network snapshot: departures, arrivals, unique routes.

## Files

| File | Contents |
|---|---|
| `data/cambodia-sentiment-index.csv` | Cambodia weekly sentiment scores, oldest → newest |
| `data/cambodia-airlift.csv` | Cambodia weekly route/carrier counts by airport |
| `data/ethiopia-sentiment-tsi8.csv` | Ethiopia weekly TSI-8 category scores |
| `data/ethiopia-airlift.csv` | Ethiopia weekly ADD network snapshots |
| `data/source-markets.csv` | Cambodia source markets, trend and sentiment direction |

## How to cite

DestinationEconomics (2026). *Cambodia & Ethiopia Tourism Intelligence — Sentiment & Airlift*. https://data.destinationeconomics.com/

## License

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — attribution to DestinationEconomics appreciated.
