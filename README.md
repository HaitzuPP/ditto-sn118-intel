# Ditto (SN118) Token Intelligence

Live dashboard for Bittensor Subnet 118 (Ditto): price, network rank, emissions,
Bittensor Conviction locks, and the top-25 alpha holders.

- **Overview** (`index.html`) — price, rank vs neighbours, emissions split, conviction, concentration.
- **Wallets** (`wallets.html`) — the 25 largest coldkeys, owner/Const/validator tags, live.

`data.json` is regenerated every 6 hours by `refresh.py` via a GitHub Action
(tao.com Data API + taostats). A Pylon Partners project. Not financial advice.
