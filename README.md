# INTC 1h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-21_780_rows-blue)](https://getdata.finance/datasets/intc) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/intc)

### -> [**Download the full INTC dataset on getdata.finance**](https://getdata.finance/datasets/intc)

**INTC 1h OHLCV stocks historical data** — ultra high-quality 1h OHLCV for **Intel**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **Intel** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/intc) · **21,780** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `INTC_1h.csv` (876 rows, `2026-03-10` -> `2026-09-08`, 86.93 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/intc)** — **21,780** `1h` rows (full `1m`: 634,759), **11 timeframes**, `2011-05-09` -> `2026-09-08`.

## Download sample

**[INTC_1h.csv](https://github.com/getdata-finance/intc-1h-ohlcv-stocks-historical-data/blob/main/INTC_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/intc-1h-ohlcv-stocks-historical-data/main/INTC_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/intc-1h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/intc-1h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/intc-1h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/intc](https://getdata.finance/datasets/intc)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/intc))** |
|---|--:|---|
| Instrument | Intel · US stocks | Intel · US stocks |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 876 | **21,780** |
| Size | 86.93 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Period | `2026-03-10` -> `2026-09-08` | `2011-05-09` -> `2026-09-08` |
| File | `INTC_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Coverage report | — | [INTC coverage](https://getdata.finance/coverage/intc) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/intc)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/intc) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`INTC_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 46.49 | 46.67 | 46.22 | 46.43 | 10734 |
| 2026-03-11T13:00:00+00:00 | 46.43 | 47.73 | 46.21 | 47.72 | 6449 |
| 2026-03-11T14:00:00+00:00 | 47.72 | 48.38 | 47.55 | 47.92 | 12601 |
| 2026-03-11T15:00:00+00:00 | 47.92 | 48.2 | 47.55 | 47.72 | 9883 |
| 2026-03-11T16:00:00+00:00 | 47.72 | 47.81 | 47.37 | 47.59 | 8219 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T15:00:00+00:00 | 103.56 | 104.89 | 103.06 | 104.62 | 16358 |
| 2026-09-08T16:00:00+00:00 | 104.62 | 105.92 | 104.23 | 105.08 | 16079 |
| 2026-09-08T17:00:00+00:00 | 105.08 | 106.02 | 104.94 | 104.98 | 14085 |
| 2026-09-08T18:00:00+00:00 | 104.98 | 105.44 | 104.53 | 105.39 | 16134 |
| 2026-09-08T19:00:00+00:00 | 105.39 | 105.64 | 103.97 | 104.5 | 16228 |

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

df = pd.read_csv('INTC_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('INTC_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('INTC_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **INTC** archive on **[getdata.finance](https://getdata.finance/datasets/intc)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **21,780** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full INTC dataset on getdata.finance](https://getdata.finance/datasets/intc)**

---
*GetData · INTC 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/intc)*
