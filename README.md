# UFN public briefing data

Generated educational financial briefing data. The private UFN repository contains all Python, Swift and GitHub Actions implementation code. Its scheduled workflow aggregates official sources at :07 and :37 each hour and publishes a rolling snapshot here.

[Current JSON briefing](https://raw.githubusercontent.com/truedichotomy/UFNdata/data/feed.json)

The `data` branch is generated and disposable: each update replaces its sole commit. Ordinary headlines follow a rolling ten-NYSE-trading-day window, including intervening weekend and holiday developments. Selected historical policy, macro and structural context has explicit longer review/expiry horizons. Treasury history retains up to one year; configured BLS monthly series retain up to two years. Initial backfill uses available official feed history and Fed archives; coverage metadata identifies gaps and does not guarantee completeness. GitHub caches and unreachable objects may persist. Source timestamps and source health are included; failures can leave older observations in place. Delivery is not real time or guaranteed. Third-party material is not offered under a blanket open-data license: follow links and check original source terms.

Educational information only. Not investment advice. Data may be delayed, incomplete or incorrect. Do not base investment decisions on this dataset or AI interpretations.
