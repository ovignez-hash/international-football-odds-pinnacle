# FREE SAMPLE - 20 matches

This sample is an exact copy of the full product: same files, same columns, same formats. Only the number of matches differs: the latest final of each of the 18 competitions, plus 2 matches whose kickoff time in the source is wrong (the pre-match market is cut at the real start).

| Match_ID | Code | Edition | Stage | Kickoff_UTC (date) | Match | Result |
|---|---|---|---|---|---|---|
| 9558178 | UEFA_CL | 2024/25 | Round of 16 | 2025-03-13 | Atletico Madrid - Real Madrid | 1-0 · 1-0 aet · 2-4 pens · agg 2-2 |
| 11854567 | UEFA_CL | 2025/26 | Final | 2026-05-30 | PSG - Arsenal | 1-1 · 1-1 aet · 4-3 pens |
| 11858974 | UEFA_EL | 2025/26 | Final | 2026-05-20 | SC Freiburg - Aston Villa | 0-3 |
| 10583630 | UEFA_ECL | 2025/26 | League Phase | 2025-10-24 | HNK Rijeka - Sparta Prague | 1-0 |
| 11858975 | UEFA_ECL | 2025/26 | Final | 2026-05-27 | Crystal Palace - Rayo Vallecano | 1-0 |
| 10058940 | UEFA_NL | 2024/25 | Final | 2025-06-08 | Portugal - Spain | 2-2 · 2-2 aet · 5-3 pens |
| 3741451 | EURO_2020 | 2020 | Final | 2021-07-11 | Italy - England | 1-1 · 1-1 aet · 3-2 pens |
| 8481075 | EURO_2024 | 2024 | Final | 2024-07-14 | Spain - England | 2-1 |
| 828218 | WC_2018 | 2018 | Final | 2018-07-15 | France - Croatia | 4-2 |
| 6025486 | WC_2022 | 2022 | Final | 2022-12-18 | Argentina - France | 2-2 · 3-3 aet · 4-2 pens |
| 12236232 | WC_2026 | 2026 | Final | 2026-07-19 | Spain - Argentina | 0-0 · 1-0 aet |
| 10253281 | FIFA_CWC | 2025 | Final | 2025-07-13 | Chelsea - PSG | 3-0 |
| 10915678 | LIBERTA | 2025 | Final | 2025-11-29 | Palmeiras - Flamengo | 0-1 |
| 10915168 | SUDAM | 2025 | Final | 2025-11-22 | Lanus - Atletico Mineiro | 0-0 · 0-0 aet · 5-4 pens |
| 8481775 | COPA_AM | 2024 | Final | 2024-07-15 | Argentina - Colombia | 0-0 · 1-0 aet |
| 11856713 | CONCACAF | 2026 | Final | 2026-05-31 | Toluca - Tigres UANL | 0-0 · 1-1 aet · 6-5 pens |
| 11781079 | AFC_CL | 2025/26 | Final | 2026-04-25 | Al Ahli Jeddah - Machida Zelvia | 0-0 · 1-0 aet |
| 7802429 | AFC_ASIA | 2023 | Final | 2024-02-10 | Jordan - Qatar | 1-3 |
| 11797845 | CAF_CL | 2025/26 | Final | 2026-05-24 | FAR Rabat - Mamelodi Sundowns | 1-1 · agg 1-2 |
| 11271497 | CAF_AFCON | 2025 | Final | 2026-01-18 | Senegal - Morocco | 0-0 · 1-0 aet |

Full product (all 11,118 matches): https://sportsdataolivier.gumroad.com/l/hethzg?utm_source=sample_readme&utm_medium=readme&utm_campaign=intl_premium&utm_content=sample_readme

Questions: contact@oliviersportsdata.com

---

# International Football Premium - Club & National Team Competitions: Odds, In-Play Ticks & Full Match Layer (2016-2026)

11,118 finished matches from 18 international competitions (9,644 club matches, 1,474
national-team matches), 2016-08-31 to 2026-09-29: UEFA Champions League, Europa League, Conference League and
Nations League, the European Championship, three World Cups, the Club World Cup, Copa Libertadores, Copa
Sudamericana, Copa America, the CONCACAF Champions Cup, the AFC Champions League, the Asian Cup, the CAF Champions
League and the Africa Cup of Nations. Every recorded price update from 5 named bookmakers, pre-match and in-play,
with the score and the match clock given by the bookmaker on in-play quotes; opening and closing prices with the
exact time of each; dated snapshots from more bookmakers. Edition, stage, matchday and leg on every match, extra time,
penalty shoot-outs and neutral venues. Match sheet, team statistics, lineups, events and minute-by-minute
statistics. All tables join on `Match_ID`.

## At a glance

|  |  |
|---|---|
| Matches | 11,118 (206 with extra time, 270 with a penalty shoot-out) |
| Competitions | 18 (6 confederations) |
| Period | 2016-08-31 to 2026-09-29 (data up to 2026-09-30) |
| Bookmakers (full history) | Bet365, Pinnacle, Unibet, Betfair (Sportsbook), Betsson - always named, never aggregated |
| Markets | FT 1X2, FT Asian handicap, FT total goals, FT total corners, HT 1X2, HT Asian handicap, HT total goals, HT total corners |
| Timestamped price updates | 28,943,376 |
| Other bookmakers' snapshots | 661,507 |
| Events | 365,177 |
| Lineup rows | 401,511 |
| Minute-by-minute statistics | 3,037,116 |

## Files

| File | Rows | One row per | Format |
|---|---|---|---|
| Intl_Matches.csv / .xlsx | 11,118 | match | CSV + XLSX |
| Intl_Opening_Closing_Odds.csv / .xlsx | 11,118 | match (opening and closing price + time, per bookmaker and market) | CSV + XLSX |
| Intl_Team_Stats.csv / .xlsx | 22,236 | match x team | CSV + XLSX |
| odds_timestamped/Intl_Odds_Timestamped_<CODE>.csv.gz | 28,943,376 | price update (bookmaker x market x time) | 18 gzip CSV |
| bookmaker_snapshots/Intl_Bookmaker_Snapshots_<CODE>.csv.gz | 661,507 | snapshot of another bookmaker (match x book x market x snapshot) | 18 gzip CSV |
| events/Intl_Events_<CODE>.csv.gz | 365,177 | match event | 18 gzip CSV |
| lineups/Intl_Lineups_<CODE>.csv.gz | 401,511 | player in a match squad | 18 gzip CSV |
| minute_stats/Intl_Minute_Stats_<CODE>.csv.gz | 3,037,116 | statistic x team x minute | 18 gzip CSV |

Load in pandas: `pd.read_csv("Intl_Matches.csv", dtype={"Edition": str})` and
`pd.read_csv("events/Intl_Events_UEFA_CL.csv.gz")` (gzip is read directly). Comma-separated, UTF-8 with BOM,
"." decimals. The XLSX workbooks are typed: text stays text, numbers are numbers, header frozen, filters on.

## Competitions and coverage

| Code | Competition | Confed. | Teams | Matches | Editions | Lineups | Minute stats | Events |
|---|---|---|---|---|---|---|---|---|
| UEFA_CL | UEFA Champions League | UEFA | Club | 1,390 | 2016/17 to 2026/27 (11) | 99.4 % | 78.8 % | 99.4 % |
| UEFA_EL | UEFA Europa League | UEFA | Club | 1,833 | 2016/17 to 2026/27 (11) | 99.6 % | 73.0 % | 99.1 % |
| UEFA_ECL | UEFA Conference League | UEFA | Club | 729 | 2021/22 to 2025/26 (5) | 87.7 % | 99.9 % | 99.9 % |
| UEFA_NL | UEFA Nations League | UEFA | National | 712 | 2018/19 to 2026/27 (5) | 90.9 % | 80.1 % | 100.0 % |
| EURO_2020 | UEFA European Championship | UEFA | National | 51 | 2020 | 100.0 % | 100.0 % | 100.0 % |
| EURO_2024 | UEFA European Championship | UEFA | National | 51 | 2024 | 100.0 % | 100.0 % | 100.0 % |
| WC_2018 | FIFA World Cup | FIFA | National | 64 | 2018 | 100.0 % | 0.0 % | 100.0 % |
| WC_2022 | FIFA World Cup | FIFA | National | 64 | 2022 | 100.0 % | 100.0 % | 100.0 % |
| WC_2026 | FIFA World Cup | FIFA | National | 104 | 2026 | 100.0 % | 57.7 % | 100.0 % |
| FIFA_CWC | FIFA Club World Cup | FIFA | Club | 125 | 2016 to 2025 (9) | 100.0 % | 87.2 % | 97.6 % |
| LIBERTA | Copa Libertadores | CONMEBOL | Club | 1,246 | 2017 to 2026 (10) | 99.6 % | 71.9 % | 98.9 % |
| SUDAM | Copa Sudamericana | CONMEBOL | Club | 1,401 | 2016 to 2026 (11) | 98.7 % | 78.4 % | 99.9 % |
| COPA_AM | Copa America | CONMEBOL | National | 86 | 2019 to 2024 (3) | 98.8 % | 69.8 % | 100.0 % |
| CONCACAF | CONCACAF Champions Cup | CONCACAF | Club | 364 | 2016/17 to 2026 (10) | 85.7 % | 73.1 % | 98.6 % |
| AFC_CL | AFC Champions League | AFC | Club | 1,142 | 2016 to 2026/27 (11) | 99.9 % | 68.3 % | 99.6 % |
| AFC_ASIA | AFC Asian Cup | AFC | National | 102 | 2019 to 2023 (2) | 98.0 % | 50.0 % | 100.0 % |
| CAF_CL | CAF Champions League | CAF | Club | 1,414 | 2016 to 2026/27 (12) | 0.1 % | 52.5 % | 74.0 % |
| CAF_AFCON | Africa Cup of Nations | CAF | National | 240 | 2017 to 2025 (5) | 99.2 % | 65.0 % | 99.6 % |
| **Total** |  |  |  | **11,118** |  | 85.0 % | 73.0 % | 96.2 % |

Lineups = both starting elevens present. Minute stats = at least one minute-by-minute statistic.
Events = at least one event in the source timeline.

### Coverage by bookmaker (FT 1X2 closing price present)

| Bookmaker | Matches with a FT 1X2 close | Coverage | Markets (closing prices present) |
|---|---|---|---|
| Bet365 | 10,786 | 97.0 % | FT_1X2, FT_Total_Goals, FT_Asian_Handicap, HT_Total_Goals, HT_1X2, HT_Total_Corners, FT_Total_Corners, HT_Asian_Handicap |
| Pinnacle | 8,243 | 74.1 % | FT_Total_Goals, FT_1X2, FT_Asian_Handicap |
| Unibet | 9,757 | 87.8 % | FT_Total_Goals, FT_1X2 |
| Betfair (Sportsbook) | 2,491 | 22.4 % | FT_1X2 |
| Betsson | 4,218 | 37.9 % | FT_1X2, FT_Total_Goals |

### Coverage by competition (share of matches with a FT 1X2 closing price)

| Competition | Matches | Bet365 | Pinnacle | Unibet | Betfair | Betsson |
|---|---|---|---|---|---|---|
| UEFA_CL | 1,390 | 100 % | 74 % | 91 % | 24 % | 44 % |
| UEFA_EL | 1,833 | 100 % | 71 % | 89 % | 18 % | 35 % |
| UEFA_ECL | 729 | 100 % | 89 % | 100 % | 36 % | 77 % |
| UEFA_NL | 712 | 99 % | 93 % | 99 % | 22 % | 33 % |
| EURO_2020 | 51 | 100 % | 100 % | 100 % | not collected | not collected |
| EURO_2024 | 51 | 100 % | 100 % | 100 % | 100 % | 100 % |
| WC_2018 | 64 | 100 % | not collected | 98 % | not collected | not collected |
| WC_2022 | 64 | 100 % | 100 % | 100 % | not collected | 100 % |
| WC_2026 | 104 | 100 % | 69 % | 58 % | 58 % | 24 % |
| FIFA_CWC | 125 | 100 % | 87 % | 92 % | 6 % | 58 % |
| LIBERTA | 1,246 | 99 % | 79 % | 96 % | 19 % | 39 % |
| SUDAM | 1,401 | 100 % | 80 % | 92 % | 21 % | 42 % |
| COPA_AM | 86 | 100 % | 98 % | 100 % | 37 % | 37 % |
| CONCACAF | 364 | 100 % | 80 % | 87 % | 28 % | 42 % |
| AFC_CL | 1,142 | 100 % | 66 % | 87 % | 21 % | 29 % |
| AFC_ASIA | 102 | 100 % | 100 % | 100 % | 50 % | 48 % |
| CAF_CL | 1,414 | 78 % | 51 % | 58 % | 16 % | 15 % |
| CAF_AFCON | 240 | 100 % | 86 % | 87 % | 43 % | 43 % |

## Editions and stages

Stages are listed in the order they are played. A two-legged round has `Leg` 1 and 2; a single match has none.

### UEFA Champions League (UEFA_CL)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016/17 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2017/18 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2018/19 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2019/20 | 119 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2020/21 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2021/22 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022/23 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023/24 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024/25 | 189 | League Phase > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025/26 | 189 | League Phase > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2026/27 | 18 | League Phase | in progress, data up to 2026-09-30 |

### UEFA Europa League (UEFA_EL)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016/17 | 205 | Group Stage > Round of 32 > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2017/18 | 205 | Group Stage > Round of 32 > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2018/19 | 205 | Group Stage > Round of 32 > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2019/20 | 197 | Group Stage > Round of 32 > Round of 16 > Quarter-finals > Semi-finals > Final | 2 ties of a two-legged round played as a single match |
| 2020/21 | 204 | Group Stage > Round of 32 > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2021/22 | 139 | Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022/23 | 141 | Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023/24 | 141 | Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024/25 | 189 | League Phase > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025/26 | 189 | League Phase > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2026/27 | 18 | League Phase | in progress, data up to 2026-09-30 |

### UEFA Conference League (UEFA_ECL)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2021/22 | 141 | Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022/23 | 141 | Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023/24 | 141 | Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024/25 | 153 | League Phase > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025/26 | 153 | League Phase > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |

### UEFA Nations League (UEFA_NL)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2018/19 | 142 | League Phase > Semi-finals > Third Place > Final |  |
| 2020/21 | 168 | League Phase > Semi-finals > Third Place > Final > Relegation Play-outs |  |
| 2022/23 | 162 | League Phase > Semi-finals > Third Place > Final > Relegation Play-outs |  |
| 2024/25 | 188 | League Phase > Quarter-finals > Promotion/Relegation Play-offs > Semi-finals > Third Place > Final |  |
| 2026/27 | 52 | League Phase | in progress, data up to 2026-09-30 |

### UEFA European Championship (EURO_2020)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2020 | 51 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |

### UEFA European Championship (EURO_2024)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2024 | 51 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |

### FIFA World Cup (WC_2018)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2018 | 64 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |

### FIFA World Cup (WC_2022)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2022 | 64 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |

### FIFA World Cup (WC_2026)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2026 | 104 | Group Stage > Round of 32 > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |

### FIFA Club World Cup (FIFA_CWC)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016 | 8 | Play-off for Quarter-finals > Quarter-finals > Fifth Place > Semi-finals > Third Place > Final |  |
| 2017 | 8 | Play-off for Quarter-finals > Quarter-finals > Fifth Place > Semi-finals > Third Place > Final |  |
| 2018 | 8 | Play-off for Quarter-finals > Quarter-finals > Fifth Place > Semi-finals > Third Place > Final |  |
| 2019 | 8 | Play-off for Quarter-finals > Quarter-finals > Fifth Place > Semi-finals > Third Place > Final |  |
| 2020 | 7 | Quarter-finals > Fifth Place > Semi-finals > Third Place > Final |  |
| 2021 | 8 | Play-off for Quarter-finals > Quarter-finals > Semi-finals > Fifth Place > Third Place > Final |  |
| 2022 | 7 | Play-off for Quarter-finals > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2023 | 7 | Play-off for Quarter-finals > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2025 | 64 | Play-in > Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final | includes the play-in match Los Angeles FC - Club America played just before the tournament |

### Copa Libertadores (LIBERTA)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2017 | 126 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2018 | 126 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2019 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2020 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2021 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025 | 125 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2026 | 119 | Group Stage > Round of 16 > Quarter-finals | in progress, data up to 2026-09-30 |

### Copa Sudamericana (SUDAM)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016 | 43 | Second Stage > Round of 16 > Quarter-finals > Semi-finals | data starts at the second stage (its second legs: the first legs were played before the data starts); no final (the 2016 final was not played after the Chapecoense air disaster); 15 two-legged ties have only one leg in the source |
| 2017 | 106 | First Stage > Second Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2018 | 106 | First Stage > Second Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2019 | 105 | First Stage > Second Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2020 | 105 | First Stage > Second Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2021 | 157 | First Stage > Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022 | 157 | First Stage > Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023 | 157 | First Stage > Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024 | 157 | First Stage > Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025 | 156 | First Stage > Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals > Semi-finals > Final | 1 two-legged tie has only one leg in the source |
| 2026 | 152 | First Stage > Group Stage > Knockout Round Play-offs > Round of 16 > Quarter-finals | in progress, data up to 2026-09-30 |

### Copa America (COPA_AM)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2019 | 26 | Group Stage > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2021 | 28 | Group Stage > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2024 | 32 | Group Stage > Quarter-finals > Semi-finals > Third Place > Final |  |

### CONCACAF Champions Cup (CONCACAF)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016/17 | 38 | Group Stage > Quarter-finals > Semi-finals > Final | group stage matchdays 4 to 6 only (data starts in September 2016) |
| 2018 | 30 | Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2019 | 30 | Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2020 | 26 | Round of 16 > Quarter-finals > Semi-finals > Final | 1 tie of a two-legged round played as a single match |
| 2021 | 29 | Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022 | 28 | Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023 | 30 | Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024 | 51 | Round One > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025 | 51 | Round One > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2026 | 51 | Round One > Round of 16 > Quarter-finals > Semi-finals > Final |  |

### AFC Champions League (AFC_CL)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016 | 4 | Semi-finals > Final | semi-final second legs and final only (data starts in October 2016 for this competition); 2 two-legged ties have only one leg in the source |
| 2017 | 126 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2018 | 126 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2019 | 126 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2020 | 97 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2021 | 135 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2022 | 130 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023/24 | 149 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2024/25 | 118 | League Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2025/26 | 115 | League Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2026/27 | 16 | League Stage | in progress, data up to 2026-09-30 |

### AFC Asian Cup (AFC_ASIA)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2019 | 51 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |
| 2023 | 51 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Final |  |

### CAF Champions League (CAF_CL)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2016 | 6 | Semi-finals > Final | semi-finals and final only (data starts in September 2016) |
| 2017 | 105 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 11 two-legged ties have only one leg in the source |
| 2018 | 121 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 15 two-legged ties have only one leg in the source |
| 2018/19 | 141 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 1 two-legged tie has only one leg in the source |
| 2019/20 | 149 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final |  |
| 2020/21 | 128 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 3 two-legged ties have only one leg in the source |
| 2021/22 | 136 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 1 two-legged tie has only one leg in the source |
| 2022/23 | 142 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 2 two-legged ties have only one leg in the source |
| 2023/24 | 134 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final |  |
| 2024/25 | 146 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final | 2 two-legged ties have only one leg in the source |
| 2025/26 | 154 | Preliminary Round > First Round > Group Stage > Quarter-finals > Semi-finals > Final |  |
| 2026/27 | 52 | Preliminary Round | in progress, data up to 2026-09-30 |

### Africa Cup of Nations (CAF_AFCON)

| Edition | Matches | Stages | Note |
|---|---|---|---|
| 2017 | 32 | Group Stage > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2019 | 52 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2021 | 52 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2023 | 52 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |
| 2025 | 52 | Group Stage > Round of 16 > Quarter-finals > Semi-finals > Third Place > Final |  |

## Other bookmakers: snapshots, not closing prices

`Intl_Bookmaker_Snapshots_<CODE>` adds 37 more bookmakers (661,507 rows,
10,486 matches, 14.8 bookmakers per match on average). The source keeps only three snapshots per bookmaker and market
(the first price, one around kickoff, the last one): this table delivers the first price when it is pre-match (`Open`)
and the latest snapshot that is still pre-match (`Last_Pre_Match`: no score, no match clock, taken before the
scheduled kickoff). **It is a dated snapshot, not a closing price**: check `Minutes_Before_Kickoff` before comparing.

| Market | Last_Pre_Match rows | Median minutes before kickoff | Within 60 minutes | More than 24 hours before |
|---|---|---|---|---|
| FT_1X2 | 152,223 | 74 | 48 % | 29 % |
| FT_Asian_Handicap | 71,845 | 291 | 45 % | 36 % |
| FT_Total_Goals | 106,759 | 100 | 47 % | 31 % |

The 5 bookmakers of the main tables are not repeated here (their full histories are in `Odds_Timestamped`).
Prediction markets that the source lists with probabilities instead of odds (Polymarket, Kalshi) are left out.

## Column dictionary

### Intl_Matches

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). The key shared by every table. |
| `Competition_Code` | UEFA_CL, UEFA_EL, UEFA_ECL, UEFA_NL, EURO_2020, EURO_2024, WC_2018, WC_2022, WC_2026, FIFA_CWC, LIBERTA, SUDAM, COPA_AM, CONCACAF, AFC_CL, AFC_ASIA, CAF_CL, CAF_AFCON. |
| `Confederation / Competition / Team_Type` | UEFA, FIFA, CONMEBOL, CONCACAF, AFC or CAF; competition name; Club or National (national teams). |
| `Edition` | Edition of the competition: 2016/17 form for seasons across two years (stays text in Excel), a single year otherwise (2019). The official edition, not the calendar year: the 2021 Africa Cup of Nations played in January 2022 is edition 2021. |
| `Stage` | Group Stage, League Phase (UEFA 2024/25 on, Nations League), League Stage (AFC Champions League Elite), preliminary rounds, Round of 32, Knockout Round Play-offs, Round of 16, Quarter-finals, Semi-finals, Third Place, Fifth Place, Final, Nations League play-offs and play-outs. |
| `Round` | Matchday number in a group or league stage; empty in knockout rounds. |
| `Leg` | 1 or 2 in a two-legged tie; empty for a single match and in group or league stages. |
| `Kickoff_UTC / Kickoff_Epoch` | Scheduled kickoff, ISO 8601 UTC and Unix seconds. |
| `Home_Team_ID / Home_Team / Home_Team_Country (Away_...)` | Source team id (text), team name, team country as the source's 2-letter code. |
| `Home_Goals_HT / Away_Goals_HT` | Half-time score. |
| `Home_Goals_90 / Away_Goals_90` | Score after 90 minutes plus added time: the score 1X2, handicap and total markets settle on. |
| `Result_90` | H, D or A after 90 minutes. |
| `Extra_Time / Home_Goals_AET / Away_Goals_AET` | 1 when extra time was played; then the score after extra time (cumulative). |
| `Penalty_Shootout / Home_Penalties / Away_Penalties` | 1 when the match ended with a penalty shoot-out; then the shoot-out score. |
| `Home_Aggregate / Away_Aggregate` | Aggregate score of a two-legged tie, when the source gives it. |
| `Home_Table_Position / Away_Table_Position` | Positions in the competition table given by the source for the match (group or league stage). |
| `Home_Formation / Away_Formation` | Formation as digits: 4231 = 4-2-3-1, 442 = 4-4-2. |
| `Home_Manager / Away_Manager / Referee / Referee_Country` | Names as given; country as a 2-letter code. |
| `Stadium / Stadium_City / Stadium_Country / Stadium_Capacity` | Venue as given by the source. |
| `Stadium_Latitude / Stadium_Longitude` | Venue coordinates (decimal degrees). |
| `Neutral_Venue` | 1 when the stadium's country is not the home team's country, 0 when it is, empty when one of the two is unknown (rule below). |
| `Has_Lineups / Has_Minute_Stats / Has_Match_Stats` | 1 when the table holds both starting elevens / minute-by-minute statistics / team statistics. |

### Intl_Opening_Closing_Odds

| Column | Meaning |
|---|---|
| `Match_ID ... Neutral_Venue` | Identity and result of the match, copied from Intl_Matches so the file stands alone. |
| `{Book}_{Market}_Open_*` | Opening: first valid pre-match quote of that bookmaker and market (no suspended, empty, out-of-range or unreadable price; valid line for handicaps and totals). |
| `{Book}_{Market}_Close_*` | Closing: last valid pre-match quote. Never an in-play quote. |
| `*_Home / *_Draw / *_Away` | 1X2: home win, draw, away win. Asian handicap: home side and away side. |
| `*_Line` | Handicap line of the HOME team, or total line, as a decimal; split lines averaged (0.0,-0.5 -> -0.25). |
| `*_Over / *_Under` | Over and Under the line. |
| `*_Open_Time / *_Close_Time` | Time of the opening / closing quote, ISO 8601 UTC. |
| `Empty cells` | No valid pre-match quote for that bookmaker and market on that match. |

### Intl_Team_Stats

| Column | Meaning |
|---|---|
| `Match_ID / Side / Team_ID / Team` | Two rows per match: Home and Away. |
| `Goals ... Action_Areas` | Full-match totals as given by the source (29 statistics, including Possession_Pct, Shots_On_Target, Dangerous_Attacks, Corners, Corners_HT, Yellow_Cards, Red_Cards, xG). Empty when the source does not give that statistic for the match. After extra time the totals include it (Goals = score after extra time; shoot-outs excluded). |

### Intl_Odds_Timestamped_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). |
| `Book` | Bet365, Pinnacle, Unibet, Betfair (Sportsbook), Betsson. |
| `Market` | FT_1X2, FT_Asian_Handicap, FT_Total_Goals, FT_Total_Corners, HT_1X2, HT_Asian_Handicap, HT_Total_Goals, HT_Total_Corners (HT = first half). |
| `Phase` | Pre-match or In-play (rule below). |
| `Timestamp_UTC / Epoch` | Time the price was recorded, ISO 8601 UTC and Unix seconds. |
| `Minute / Second` | Match clock given by the bookmaker at that quote (integers). Unibet and Betsson give mm:ss; empty pre-match and when the bookmaker gives a non-numeric clock. |
| `Score_Home / Score_Away` | Score at that quote (integers); empty pre-match and when the bookmaker sends a partial score. |
| `Corners_Home / Corners_Away` | Corner count at that quote, corner markets only. |
| `Line` | Handicap line of the HOME team, or total line (decimal). Empty for 1X2. |
| `Price_Home / Price_Draw / Price_Away / Price_Over / Price_Under` | Decimal prices. Empty when suspended, absent, out of range or unreadable. |
| `Suspended` | 1 when the bookmaker showed the market suspended at that quote, else 0. |

### Intl_Bookmaker_Snapshots_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID` | Source event id (text). The key shared by every table. |
| `Book` | Bookmaker name exactly as the source spells it (37 books). The product's 5 books (Bet365, Pinnacle, Unibet, Betfair, Betsson) are not repeated here: their full price histories are in Odds_Timestamped. |
| `Market` | FT_1X2, FT_Asian_Handicap, FT_Total_Goals (full time). |
| `Snapshot` | Open = the first price the source kept for that book, when it is pre-match. Last_Pre_Match = the latest of the source's three snapshots (first price, around kickoff, last price) that is still pre-match; it can be the same tick as Open. NOT a guaranteed closing price: see Minutes_Before_Kickoff. |
| `Timestamp_UTC` | Time of the snapshot, ISO 8601 UTC. |
| `Epoch` | Same instant, Unix seconds. |
| `Minutes_Before_Kickoff` | Whole minutes between the snapshot and the scheduled kickoff (always >= 0). |
| `Line` | Handicap (home team's line) or total line, decimal; split lines averaged. Empty for 1X2. |
| `Price_Home` | Decimal price, home win (1X2) or home handicap side (AH). |
| `Price_Draw` | Decimal price of the draw (1X2 only). |
| `Price_Away` | Decimal price, away win (1X2) or away handicap side (AH). |
| `Price_Over` | Decimal price of Over the line (FT_Total_Goals). |
| `Price_Under` | Decimal price of Under the line (FT_Total_Goals). |

### Intl_Events_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Event_Order` | Source event id; position of the event in the source timeline (gaps = summary lines not delivered). |
| `Minute / Added_Time` | Match minute and added time (90+3 -> 90 and 3), integers. |
| `Event_Type` | Goal, Assist, Yellow Card, Red Card, Substitution, Corner, Shot On Target, Shot Off Target, Offside, Race To Corners, Missed Penalty, Penalty Shootout Scored, Penalty Shootout Missed. |
| `Type_Ordinal` | The source's match-wide count for that event type (1st, 2nd...); a team's kick number in a shoot-out. |
| `Team_Side / Team` | Home or Away, and the team name as written in the event. |
| `Player / Player_2` | Substitution: player on / player off. Goal: scorer / assist provider. |
| `Race_Target` | N in 'Race to N corners'. |
| `Detail` | Goal type: Shot, Header, Penalty, Own Goal, Free Kick. |
| `Extra_Time` | 1 when the source tags the event 'ET'. The tag marks extra time, but the source also puts it on some events of second-half added time: use Minute / Added_Time to tell them apart. |

### Intl_Lineups_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Side / Team_ID / Team` | Match and team. |
| `Starter` | 1 = starting eleven, 0 = substitute. |
| `Lineup_Order` | Order in the source's team sheet. |
| `Player_ID / Player / Player_Country` | Source player id (text), name, 2-letter country code. |
| `Shirt_Number` | Shirt number. |
| `Position / Position_Group` | Position as given (Goalkeeper, Defender, Midfielder, Forward and detailed roles) and its group. |

### Intl_Minute_Stats_<CODE>

| Column | Meaning |
|---|---|
| `Match_ID / Side / Stat` | Match, team side and statistic (Attacks, Dangerous_Attacks, Possession_Pct, Shots_On_Target, Corners, Goals...). |
| `Minute / Value` | Match minute and the running value at that minute: cumulative count, or running percentage for Possession_Pct, Passing_Accuracy and Crossing_Accuracy. |
| `Timestamp_UTC / Epoch` | Time the value was recorded. |

## Rules applied to every cell

- **Times** are ISO 8601 UTC with the T and the Z (`2026-09-20T15:30:00Z`), plus a Unix epoch column.
  Excel and LibreOffice keep this form as text: it is never converted into a local date.
- **No cell that a spreadsheet can rewrite.** Scores, minutes and shoot-outs are separate integer columns
  (never "1-0", "90+2" or "73:02"). Formations are digits: `4231` means 4-2-3-1, `442` means 4-4-2
  ("4-4-2" in a cell becomes 04/04/2002 in French Excel). Handicap lines are decimals (`-0.25`, never "0.0,-0.5").
  Editions are `2016/17` or `2019`. Leading "-", "+", "=" or "@" are removed from names.
- Every cell of every file was audited against these Excel conversion patterns at write time: **0 risky cells**.
- **Empty cell = absent from the source.** Nothing is imputed, interpolated or averaged across bookmakers.
- A suspended price ("-") is an empty cell with `Suspended = 1`: kept, not deleted.

## Knockout matches, extra time, penalties and neutral venues

- **Extra time** (206 matches) and **penalty shoot-outs** (270) are recorded only in a deciding
  knockout match (single match or second leg). Extra_Time = 1 needs proof in the source: a goal scored in extra time,
  an event dated from the 106th minute, the source's extra-time score line, or a shoot-out in a competition whose
  rules always play extra time first (UEFA club competitions, European Championship, World Cup).
- 164 shoot-outs came straight after 90 minutes, as CONMEBOL, CAF and CONCACAF two-legged ties and some
  third-place matches do: Extra_Time = 0 there.
- **Neutral_Venue** compares the stadium's country with the home team's country code from the source: 1 = neutral
  (1,190 matches), 0 = home ground country (9,091), empty = unknown (837).
  Finals, tournaments and Covid-era bubbles show as neutral; so do clubs exiled abroad (Ukrainian or Israeli clubs
  in UEFA competitions, Iranian clubs in the AFC). The source gives the same country code (gb) to English, Scottish,
  Welsh and Northern Irish teams; AS Monaco (French code) at home in Monaco and FC Vaduz (Swiss code) at home in
  Liechtenstein count as home.

## Pre-match, in-play and closing

- A quote is **Pre-match** when it carries no score AND was recorded before the kickoff anchor K. Everything
  else is **In-play**.
- **K** is the scheduled kickoff. When Bet365's live clock (tick time minus its minute, minutes 1 to 15) shows
  that the match started before the scheduled time, K is that start minus 2 minutes. Without a Bet365 live clock,
  K is also bounded by the first quote that carries a score, minus 2 minutes. K is never later than the scheduled
  kickoff, so a delayed kickoff closes the market at the scheduled time.
- **Opening** = first valid pre-match quote, **Closing** = last valid pre-match quote, per bookmaker and market,
  each with its own time. A closing price is never an in-play price.
- The source records a quote when the price changes. A `_Close_Time` hours before kickoff therefore means the
  price did not move after that time, or that the bookmaker stopped quoting the market: the data cannot tell the
  two apart. Compare the `_Close_Time` columns before comparing closing prices across books.

## Data integrity: what was corrected, and why

Each decision below is written in the build code with its evidence; the build stops if a new unresolved case appears.

**8 source events removed:**

| Source event | Competition | Reason | Evidence |
|---|---|---|---|
| 44030 | AFC_ASIA | isolated qualifying match (the rest of the qualifiers are not in this source league) | Laos - Maldives, 2016-10-11: Asian Cup 2019 qualifier |
| 8259 | AFC_ASIA | isolated qualifying match (the rest of the qualifiers are not in this source league) | Bangladesh - Bhutan, 2016-09-06: Asian Cup 2019 qualifier |
| 4795405 | AFC_CL | duplicate id of the same match | Al Taawon Buraidah - Pakhtakor, 2022-04-10: same match as 4885056 (same kickoff, same 0-1); kept as 4885056, which carries the Bet365 odds, the events and the statistics |
| 1406572 | AFC_CL | isolated qualifying match (the rest of the qualifiers are not in this source league) | United City - Yangon United, 2019-02-05: single preliminary-round match |
| 680983 | AFC_CL | isolated qualifying match (the rest of the qualifiers are not in this source league) | Bali United - Tampines Rovers, 2018-01-16: single preliminary-round match |
| 53099 | AFC_CL | second id created by the source during the match | El Jaish - Al Ain, 2016-10-18 (AFC semi-final, second leg): id opened at half-time (Bet365 in-play from 45' to 91', no pre-match price); match kept as 46755 (kickoff, pre-match market, first half, lineups) |
| 7365925 | CAF_CL | not a match of this competition | Enyimba - WAC Casablanca, 2023-10-22: African Football League quarter-final, not a CAF Champions League match |
| 1259685 | SUDAM | duplicate id without any match data | Montevideo Wanderers - Zamora (2016 second stage): second id dated 2016-09-14 without events, stats, lineups or odds; match kept as 15070 |

**Team identity.** 2 matches carried a wrong team id in the source and are corrected:

- 252785: Copa Libertadores 2017: the source names River Plate (Argentina) 'CA River Plate' (the Uruguayan club's id); Estadio Monumental and coach Marcelo Gallardo prove it is River Plate (id 1398)
- 4885056: AFC Champions League 2022: the source names the Saudi club Al Taawon Buraidah 'Al Taawon' (a UAE club's id); same match as the duplicate 4795405

**Editions and stages** come from a written table (edition, stage, dates, the source's round codes, expected number of matches) checked match by match: every match is placed by exactly one line, every line has exactly its number of matches, and every two-legged tie has its two legs home and away reversed. 2 matches without a round code are placed one by one with evidence. 53 ties have only one leg in the source; 9 ties have the same club at home on both legs in the source (a home leg given up or moved): `Neutral_Venue` flags a leg played outside the home club's country.

**Results awarded after the match.** Africa Cup of Nations 2025 final, Senegal - Morocco (2026-01-18): the source stores the result CAF awarded on 2026-03-18 (0-3). The tables keep the match as played - 0-0 after 90 minutes, Senegal 1-0 after extra time (94') - which is what the events, the statistics and the odds describe. Copa Libertadores 2018 round of 16, first leg, Independiente - Santos (2018-08-22): the source stores the 3-0 awarded to Independiente after the match (Santos sanctioned). The tables keep the match as played, 0-0 - what the events, the statistics and the odds describe.

**Venues.** 45 matches of 2017-2018 had the stadium name written in the country field (shifted or Cyrillic text): stadium, city and country are restored from a written list (10 venues).

**Half-time scores.** 1 half-time score was higher than the final score (the source counted a goal it later cancelled): left empty rather than wrong.

**Home / away orientation.** A bookmaker sometimes lists a fixture with the two teams the other way round. Every price series is aligned on the match's home and away teams: 1X2 and Asian handicap, full time and half time, with the handicap line and the live score turned with it (134 match-bookmaker series turned: Pinnacle 58, Unibet 54, Betfair 13, Betsson 8, Bet365 1); the other bookmakers' snapshots likewise (1,939 match-bookmaker sets). 1 match was listed by the source with home and away reversed, while almost all bookmakers show the other team at home; each case was checked against the clubs' usual grounds and the home / away balance of the pair in the season. This match is turned around everywhere (teams, goals, lineups, statistics, events, prices); turning a match leaves its venue as it was:

| Source event | League | Date | Home | Away |
|---|---|---|---|---|
| 6054180 | SUDAM | 2023-03-08 | Guabira | Oriente Petrolero |

**32 fixtures are not in the tables** because the source never marked them as finished (21 result decided by the federation; 9 result never confirmed by the source; 1 interrupted; 1 abandoned). They are listed so that a gap in a season is never silent:

| Source event | League | Date | Home | Away | Score shown | Status |
|---|---|---|---|---|---|---|
| 2174489 | AFC_CL | 2020-02-10 | Al Hilal Riyadh | Shahr Khodro | 2-0 | result decided by the federation |
| 2137199 | AFC_CL | 2020-02-17 | Shabab Al Ahli Dubai | Al Hilal Riyadh | 1-2 | result decided by the federation |
| 2614550 | AFC_CL | 2020-09-14 | Al Hilal Riyadh | Pakhtakor Tashkent | 2-1 | result decided by the federation |
| 2614551 | AFC_CL | 2020-09-17 | Pakhtakor Tashkent | Al Hilal Riyadh | 0-0 | result decided by the federation |
| 2614997 | AFC_CL | 2020-09-20 | Shahr Khodro | Al Hilal Riyadh | 0-0 | result decided by the federation |
| 3411411 | AFC_CL | 2021-04-07 | Al-Wehdat | Al Quwa Al Jawiya | 0-0 | result never confirmed by the source |
| 7122750 | AFC_CL | 2023-10-02 | Sepahan | Al Ittihad Jeddah | 0-3 | result decided by the federation |
| 1591487 | CAF_CL | 2019-05-31 | Esperance de Tunis | WAC Casablanca | 1-0 | abandoned |
| 2996332 | CAF_CL | 2020-12-05 | Stade Malien | Ashanti GB | 2-0 | result decided by the federation |
| 3003176 | CAF_CL | 2020-12-06 | Asante Kotoko | FC Nouadhibou | 2-0 | result decided by the federation |
| 3126826 | CAF_CL | 2021-01-05 | El Zamalek | Gazelle FC |  | result decided by the federation |
| 7151447 | CAF_CL | 2023-08-25 | AS GNN | AS Douanes Ouagadougou |  | result decided by the federation |
| 7138372 | CAF_CL | 2023-09-01 | AS Douanes Ouagadougou | AS GNN |  | result decided by the federation |
| 8716860 | CAF_CL | 2024-08-25 | Djoliba AC | Red Star Bangui |  | result decided by the federation |
| 8929260 | CAF_CL | 2024-11-26 | Young Africans | Al Merrikh |  | result never confirmed by the source |
| 8929642 | CAF_CL | 2024-12-06 | Al Merrikh | TP Mazembe |  | result never confirmed by the source |
| 8929286 | CAF_CL | 2024-12-13 | MC Alger | Al Merrikh |  | result never confirmed by the source |
| 8929287 | CAF_CL | 2025-01-03 | Al Merrikh | MC Alger |  | result never confirmed by the source |
| 8929264 | CAF_CL | 2025-01-10 | Al Merrikh | Young Africans |  | result never confirmed by the source |
| 8929643 | CAF_CL | 2025-01-17 | TP Mazembe | Al Merrikh |  | result never confirmed by the source |
| 3033507 | LIBERTA | 2020-12-18 | Nacional De Football | CA River Plate |  | result never confirmed by the source |
| 9684180 | LIBERTA | 2025-04-09 | CA River Plate | Barcelona Guayaquil |  | result never confirmed by the source |
| 11619368 | LIBERTA | 2026-05-08 | Junior | Cerro Porteno | 0-1 | interrupted |
| 10359509 | SUDAM | 2025-08-21 | CA Independiente | Universidad de Chile | - | result decided by the federation |
| 4730880 | UEFA_EL | 2022-03-10 | RB Leipzig | Spartak Moscow |  | result decided by the federation |
| 4730881 | UEFA_EL | 2022-03-17 | Spartak Moscow | RB Leipzig |  | result decided by the federation |
| 2230123 | UEFA_NL | 2020-11-15 | Romania | Norway | 3-0 | result decided by the federation |
| 2231204 | UEFA_NL | 2020-11-17 | Switzerland | Ukraine | 3-0 | result decided by the federation |
| 4459582 | UEFA_NL | 2022-06-02 | Albania | Russia |  | result decided by the federation |
| 4459534 | UEFA_NL | 2022-06-06 | Israel | Russia |  | result decided by the federation |
| 4459584 | UEFA_NL | 2022-06-10 | Russia | Iceland |  | result decided by the federation |
| 4463589 | UEFA_NL | 2022-06-13 | Russia | Albania |  | result decided by the federation |

## Said plainly - known limitations

- **UEFA European Championship 2020**: Betfair and Betsson were not collected for this tournament.
- **FIFA World Cup 2018**: Pinnacle, Betfair and Betsson were not collected for this tournament.
- **FIFA World Cup 2022**: Betfair was not collected for this tournament.
- **Lineups** are almost absent from the source for CAF Champions League (0.1 % of matches).
- **Venue unknown** for 836 matches (7.5 %); with the 1 home team without a country code, `Neutral_Venue` is empty on 837 matches.
- **Kickoff times**: for 2 matches the source's scheduled kickoff is more than 3 hours later than the real start read from Bet365's live clock: Atletico Madrid - Real Madrid, played 2025-03-12 (source kickoff 2025-03-13 05:14 UTC); HNK Rijeka - Sparta Prague, played 2025-10-23 (source kickoff 2025-10-24 14:00 UTC). `Kickoff_UTC` keeps the source's value; the pre-match markets are cut at the real start.
- **Score field of the source**: on 153 of the 270 penalty shoot-outs the source's own final score adds the shoot-out to the goals (a 1-1 decided 4-2 on penalties is stored as 5-3). This product never uses it: goals after 90 minutes, after extra time and in the shoot-out are separate columns.
- **Qualifying rounds** are delivered only where the source files them with the competition (Copa Sudamericana first stage, CAF Champions League preliminary rounds, CONCACAF round one); the other competitions start at their group or league stage.
- **Data starts on 2016-08-31**: editions that began before (Copa Sudamericana 2016, CAF Champions League 2016, CONCACAF Champions Cup 2016/17, AFC Champions League 2016) are partial, as shown in the editions tables. The last editions stop at 2026-09-30.
- **Events** are the source's text timeline: it keeps some events it later cancelled (goals disallowed by VAR,
  rescinded cards; a repeated ordinal marks them). Goals in events match the 90-minute score on
  98.7 % of matches; the match tables carry the match sheet's score.
- **Team statistics**: goals equal the 90-minute score on 100.0 % of rows
  of matches without extra time.
- Odds are UTC and come from one data provider. No cross-provider reconciliation is claimed.

## Format, licence, delivery

- CSV: comma-separated, UTF-8 with BOM, "." decimals. Large tables are gzip CSV, one file per competition.
- Single-user commercial licence: use the data, analyse it, build and sell models on it.
  Do not resell or redistribute the files themselves.
- A question, an invoice or a custom extract: contact@oliviersportsdata.com

Olivier Vignez - Sports Betting Data Engineer - Olivier Sports Data
