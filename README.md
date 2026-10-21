# For-a-Few-Dollars-More.-Liquidity-Provision-in-Dynamic-Fee-AMMs.
This repository examines whether volatility-responsive dynamic fees reduce
liquidity withdrawals during market stress. It compares the behaviour of
liquidity providers in dynamic-fee and static-fee Uniswap v4 pools trading
the same asset pairs.

## Contents
- `Uniswap_v4_Pool_Fetcher.ipynb` – retrieves pool initialization events.
- `Uniswap_v4_Swap_Fetcher.ipynb` – retrieves swap events.
- `Uniswap_v4_Mint_Burn_Fetcher.ipynb` – retrieves liquidity additions and removals.
- `Dynamic_Fee_Hook_Filter.ipynb` – identifies dynamic-fee hooks and matches them with static-fee pools on the same pair.
- `Matlab_VolSigPlot_ReVol/` – volatility signature plots for choosing the sampling frequency.
- `Realized_Volatility` – computes realized volatility for each pool.
- `Liquidity_Providers_Static_Dynamic` – analyses how liquidity providers respond during periods of high volatility in static-fee and dynamic-fee pools.
- `data/` – pool, swap, liquidity event and matched-pair datasets.

Work in progress.
