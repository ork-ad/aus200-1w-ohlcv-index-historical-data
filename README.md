# AUS200 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-104_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full AUS200 dataset on ork.ad**](https://ork.ad/)

**AUS200 1w OHLCV Stock index historical data** — ultra high-quality 1w OHLCV for **Australia 200 Index**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **Australia 200 Index** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **104** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `AUS200_1w.csv` (105 rows, `2024-07-01` → `2026-06-29`). **Full archive on [ork.ad](https://ork.ad/)** — **104** `1w` rows (~0.01 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2024-07-08` → `2026-06-29`.

## Download sample

**[AUS200_1w.csv](https://github.com/ork-ad/aus200-1w-ohlcv-index-historical-data/blob/main/AUS200_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/aus200-1w-ohlcv-index-historical-data/main/AUS200_1w.csv)) · [GitHub Releases](https://github.com/ork-ad/aus200-1w-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/aus200-1w-ohlcv-index-historical-data/](https://ork-ad.github.io/aus200-1w-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Australia 200 Index · Stock index | Australia 200 Index · Stock index |
| Timeframes | `1w` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1w rows | 105 | **104** |
| Size | 0.01 MB | ~0.01 MB |
| Period | `2024-07-01` → `2026-06-29` | `2024-07-08` → `2026-06-29` |
| File | `AUS200_1w.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1w` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1w` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_1w.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-07-01T00:00:00Z | 7731.037 | 7855.539 | 7682.477 | 7821.878 | 67283.0 |
| 2024-07-08T00:00:00Z | 7821.878 | 8054.121 | 7771.778 | 8037.7 | 74326.0 |
| 2024-07-15T00:00:00Z | 8037.7 | 8104.351 | 7898.309 | 7928.409 | 100949.0 |
| 2024-07-22T00:00:00Z | 7928.409 | 8021.43 | 7838.388 | 7993.19 | 114536.0 |
| 2024-07-29T00:00:00Z | 7993.19 | 8171.352 | 7748.837 | 7793.198 | 153311.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-01T00:00:00Z | 8707.237 | 8813.228 | 8484.965 | 8494.455 | 130261.0 |
| 2026-06-08T00:00:00Z | 8494.455 | 8889.599 | 8490.525 | 8879.589 | 308625.0 |
| 2026-06-15T00:00:00Z | 8879.589 | 8984.65 | 8768.578 | 8802.268 | 124554.0 |
| 2026-06-22T00:00:00Z | 8802.268 | 8874.289 | 8714.107 | 8786.46 | 215184.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUS200_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1D').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_1w.csv', parse_dates=['time'])
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

df = pd.read_csv('AUS200_1w.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **104** rows at `1w`, plus all other timeframes in the same ZIP.

**[→ Get the full AUS200 dataset on ork.ad](https://ork.ad/)**

---
*GetData · AUS200 1w OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-03 UTC*