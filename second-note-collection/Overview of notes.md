# Overview

My partner Ali Eldahshan and I are asking whether AI helps the people who find and fix security flaws more than the people who exploit them, and how AI changes the time organizations have to install a fix once a flaw is public.
Our case study is PHP2Shell two critical PHP flaws patched in an emergency release on October 21, 2026.
We argue that AI helps defenders before disclosure but attackers more afterward so organizations must respond within a faster time like hours and not so much days.

For this collection I focused more on the clock and how fast attackers move once a flaw is public and also how slowly organizations patch.
Mandiant and Rapid7 measure how fast attackers exploit flaws and Verizon measures how long organizations take to patch.
My fourth source is the PHP Foundation’s own account of PHP2Shell, which explains why the fix took so long.
I cite Ntsele (2026)  in commentary to tie notes back to the case.

My attention moved from attackers to defenders.
I expected to confirm the numbers in our storyboard and ended up questioning them.
The “five days” figure depends on removing outliers (notes 1 and 2) public exploits do not predict fast attacks (note 3), and Rapid7 measures exploitation in days, not hours (note 4), so the hours in our claim rests on PHP2Shell alone.
Verizon and the PHP Foundation then showed me that delays on the defender side come from people more than technology.

My most frequent subject terms are “patch window,” “time-to-exploit,” and “measurement,” at four notes each.

The key connection runs through notes 7, 8, and 10 every flaw AI finds becomes another patch for a few people to write and install so AI discovery may slow down the slowest step.
Note 8 also shows that humans saw signs of the PHP2Shell flaw in a 2024 audit, and AI’s contribution was proving it could be exploited.

