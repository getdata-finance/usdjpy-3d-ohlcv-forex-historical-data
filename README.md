# USDJPY 3d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_013_rows-blue)](https://getdata.finance/datasets/usdjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdjpy)

### -> [**Download the full USDJPY dataset on getdata.finance**](https://getdata.finance/datasets/usdjpy)

**USDJPY 3d OHLCV forex historical data** — ultra high-quality 3d OHLCV for **US Dollar / Japanese Yen**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **US Dollar / Japanese Yen** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdjpy) · **3,013** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `USDJPY_3d.csv` (244 rows, `2024-09-02` -> `2026-09-01`, 28.05 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdjpy)** — **3,013** `3d` rows (full `1m`: 9,184,987), **11 timeframes**, `2001-11-26` -> `2026-09-01`.

## Download sample

**[USDJPY_3d.csv](https://github.com/getdata-finance/usdjpy-3d-ohlcv-forex-historical-data/blob/main/USDJPY_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdjpy-3d-ohlcv-forex-historical-data/main/USDJPY_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdjpy-3d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdjpy-3d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdjpy-3d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdjpy](https://getdata.finance/datasets/usdjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdjpy))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **3,013** |
| Size | 28.05 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Period | `2024-09-02` -> `2026-09-01` | `2001-11-26` -> `2026-09-01` |
| File | `USDJPY_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Coverage report | — | [USDJPY coverage](https://getdata.finance/coverage/usdjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdjpy)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/usdjpy) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDJPY_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-02T00:00:00+00:00 | 146.437 | 147.264 | 143.173 | 143.327 | 1563561.61698 |
| 2024-09-05T00:00:00+00:00 | 143.327 | 144.221 | 141.785 | 142.258 | 1473582.75588 |
| 2024-09-08T00:00:00+00:00 | 142.258 | 143.981 | 142.125 | 142.255 | 1039851.62327 |
| 2024-09-11T00:00:00+00:00 | 142.255 | 143.062 | 140.284 | 140.779 | 2085252.30371 |
| 2024-09-14T00:00:00+00:00 | 140.779 | 141.403 | 139.696 | 140.955 | 530460.36356 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 159.474 | 160.392 | 159.374 | 160.187 | 493183.1638 |
| 2026-08-23T00:00:00+00:00 | 158.971 | 159.491 | 158.551 | 159.216 | 490145 |
| 2026-08-26T00:00:00+00:00 | 159.216 | 160.203 | 158.882 | 160.079 | 686736 |
| 2026-08-29T00:00:00+00:00 | 160.018 | 160.199 | 159.48 | 159.748 | 274619 |
| 2026-09-01T00:00:00+00:00 | 159.748 | 160.392 | 159.634 | 160.378 | 259814 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDJPY_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDJPY_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('USDJPY_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **USDJPY** archive on **[getdata.finance](https://getdata.finance/datasets/usdjpy)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **3,013** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full USDJPY dataset on getdata.finance](https://getdata.finance/datasets/usdjpy)**

---
*GetData · USDJPY 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdjpy)*
