# Block Number — Spam Database

Community-reported spam number database used by the [Block Number](https://github.com/tareknahas85-star/block-number-android) Android app to identify and block unwanted calls.

## Files

- `spamdb.csv` — the spam number dataset. Each row is a reported number with its category and community vote counts.
- `version.txt` — last update date of the dataset, used by the app to check for new data.

## CSV format

```
number,category,negative,positive,neutral,name
```

- `number` — phone number in E.164 format (e.g. +963999000001)
- `category` — telemarketing, scam, debt-collector, or similar
- `negative` / `positive` / `neutral` — community vote counts on how the number is perceived
- `name` — reported caller name, if known

## How it's used

The Block Number app periodically checks `version.txt` and downloads the latest `spamdb.csv` to keep its local call-screening database up to date, without needing an app update.
