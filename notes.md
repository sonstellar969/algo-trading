- Averaging-in / scaling-in: The point Chan's making: if you strictly followed a linear model, your position size should scale continuously and proportionally with how far price has deviated from the mean — not a single all-or-nothing trade at one threshold. So instead of "price crosses the band, buy 100% position," you buy a little at 1 std dev away, a little more at 1.5, more at 2, etc. — building ("scaling into") the position gradually as the deviation increases, rather than jumping in all at once at a single trigger point. Covered properly in his Chapter 3

- equal weighting concept: Practical use: rank all stocks by this score, buy the top decile (highest scores), short the bottom decile (lowest scores) — a long-short portfolio. This is a real, common quant strategy structure, not a toy example

- no matter how carefully you have tried to prevent data-snooping bias in your testing process, it will somehow creep into your model. So we must perform a walk-forward tes as a final, true out-of-sample test

- more volatile = bigger std dev

- 
