# Olympic Games Analysis

An interactive Power BI project exploring Olympic history through medal results, participating countries, athletes, sports, and host cities. The report combines several Olympic datasets into six pages of summary and drill-down views.

## Dashboard

Open [`Olympic Games Dashboards.pbix`](./Olympic%20Games%20Dashboards.pbix) in Microsoft Power BI Desktop to explore the report.

The report includes:

- **Global Medal Overview** - a high-level view of Olympic medal results.
- **Country Insights** - medal performance by country.
- **Athlete Spotlight** - athlete information and achievements.
- **Sport & Event Analysis** - results by sport and event.
- **Host Country Analysis** - Olympic host locations and their medal results.
- **Gender & Demographics** - athlete demographics, including gender.

Use the report's filters and visual interactions to explore results across Olympic editions, countries, athletes, sports, and events.

## Data

The source CSV files are in [`Raw Files/`](./Raw%20Files/). They contain:

| File | Records | Description |
|---|---:|---|
| `Olympics_Country.csv` | 235 | Country names and National Olympic Committee (NOC) codes. |
| `Olympics_Games.csv` | 64 | Olympic editions, including year, host city and country, and event dates. |
| `Olympic_Athlete_Bio.csv` | 155,861 | Athlete biographies and demographic details, including name, sex, country, height, and weight. |
| `Olympic_Athlete_Event_Results.csv` | 316,834 | Athlete event entries and results, including sport, event, country, placing, and medal. |
| `Olympic_Games_Medal_Tally.csv` | 1,807 | Medal counts by Olympic edition and country, split into gold, silver, bronze, and total. |
| `Olympic_Results.csv` | 7,394 | Event-level result details, such as event title, date, location, participants, and descriptions. |

Record counts reflect the CSV files currently included in this repository.

## Opening the project

1. Download or clone this repository.
2. Open `Olympic Games Dashboards.pbix` in Power BI Desktop.
3. If prompted to locate source data when refreshing, point Power BI to the CSV files in `Raw Files/`.

## Tools

- Microsoft Power BI Desktop
- CSV datasets
