# GenesisHook Evidence Correction

The original investor report used the first swap observed in the CSV
as the beginning of the observation window.

This was incorrect.

Material liquidity was added at:

LP1:
block 46890660
(~€200 liquidity)

LP2:
block 46934575
(~€400 liquidity)

Recomputed windows:

Post LP1:
52 swaps
2.94 days
17.7 swaps/day

Post LP2:
40 swaps
1.93 days
20.8 swaps/day

Observed LP fee advantage:

Genesis APY:
11.55%

Vanilla APY:
6.52%

Delta:
+5.03% APY

Average Genesis fee:
4583 pips

Vanilla baseline:
3000 pips

WETH-side LP advantage:
+118.4%

This correction replaces the earlier 6.7-day observation assumption.
