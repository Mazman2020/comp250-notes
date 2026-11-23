# Note 9: The Fix Is Also a Clue

Quotation
---------

“Chainguard unilaterally broke the embargo and published built images containing the
fix. . . . Any attacker could now study the fix in binary form while every other PHP
user was still waiting for the release” (PHP Foundation 2026, under “Leak and disrupted
disclosure”).

Commentary
---------

Our storyboard treats disclosure, when a flaw goes public, as one single moment.
PHP2Shell shows it can leak out in pieces. The flaw numbers leaked two days early so
the Foundation moved the release up a day and then Chainguard posted the fix hours
before everyone else (PHP Foundation 2026). A fix gives away where the flaw is because
attackers can compare the old and new code. If AI can build an attack from a
description it can probably build one from a fix too but we dont have any evidence for that yet maybe we will continue to look.

Subject terms
---------

disclosure; embargo; patch window