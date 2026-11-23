# Note 2: Five Days or Forty-Seven

Quotation
---------

“Our average TTE excludes 15 total data points, including two n-days and 13 zero-days,
that we identified as outliers from a standard deviation-based statistical analysis.
Without the removal of these outlier TTEs, the average grows from five to 47” (Charrier
and Weiner 2024, under “Time-to-Exploit”).

Commentary
---------

Our storyboard says  5 days with no warning, but this sentence shows the number is
shakier than it looks. Mandiant left out 15 of the 138 flaws it tracked and with them
included the average jumps from 5 days to 47. This  means that most flaws get attacked fast
but a few take a very long time. I still think our point is right, but we should say
“most flaws are attacked within days” instead of relying on one average. Rapid7 (note 4)
gives percentages, which show the spread better.

Subject terms
---------

time-to-exploit; measurement; outliers