# AMZN 3d OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_795_rows-blue)](https://getdata.finance/datasets/amzn) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amzn)

### -> [**Download the full AMZN dataset on getdata.finance**](https://getdata.finance/datasets/amzn)

**AMZN 3d OHLCV stocks historical data** — ultra high-quality 3d OHLCV for **Amazon**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3d OHLCV** for **Amazon** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/amzn) · **1,795** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `AMZN_3d.csv` (68 rows, `2026-02-09` -> `2026-09-01`, 4.12 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/amzn)** — **1,795** `3d` rows (full `1m`: 637,283), **11 timeframes**, `2010-03-29` -> `2026-09-01`.

## Download sample

**[AMZN_3d.csv](https://github.com/getdata-finance/amzn-3d-ohlcv-stocks-historical-data/blob/main/AMZN_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amzn-3d-ohlcv-stocks-historical-data/main/AMZN_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/amzn-3d-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/amzn-3d-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/amzn-3d-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/amzn](https://getdata.finance/datasets/amzn)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amzn))** |
|---|--:|---|
| Instrument | Amazon · US stocks | Amazon · US stocks |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 68 | **1,795** |
| Size | 4.12 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/amzn) |
| Period | `2026-02-09` -> `2026-09-01` | `2010-03-29` -> `2026-09-01` |
| File | `AMZN_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amzn) |
| Coverage report | — | [AMZN coverage](https://getdata.finance/coverage/amzn) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amzn)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/amzn) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AMZN_3d.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-09T00:00:00+00:00 | 210.1 | 212.66 | 202.37 | 204.08 | 313017 |
| 2026-02-12T00:00:00+00:00 | 204.08 | 204.08 | 197.15 | 198.66 | 387818 |
| 2026-02-15T00:00:00+00:00 | 198.66 | 201.61 | 196 | 201.1 | 148009 |
| 2026-02-18T00:00:00+00:00 | 201.1 | 211.05 | 201.1 | 210.08 | 516472 |
| 2026-02-21T00:00:00+00:00 | 210.08 | 210.08 | 202.98 | 205.08 | 100801 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 265.65 | 265.65 | 256.9 | 258.38 | 71270 |
| 2026-08-23T00:00:00+00:00 | 258.38 | 263.59 | 257.93 | 260.3 | 70705 |
| 2026-08-26T00:00:00+00:00 | 260.97 | 267.4 | 255.45 | 266.3 | 70644 |
| 2026-08-29T00:00:00+00:00 | 266.3 | 266.3 | 256.99 | 259.96 | 36607 |
| 2026-09-01T00:00:00+00:00 | 259.96 | 259.96 | 251.82 | 254.82 | 35635 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AMZN_3d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AMZN_3d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AMZN_3d.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **AMZN** archive on **[getdata.finance](https://getdata.finance/datasets/amzn)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,795** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full AMZN dataset on getdata.finance](https://getdata.finance/datasets/amzn)**

---
*GetData · AMZN 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/amzn)*
