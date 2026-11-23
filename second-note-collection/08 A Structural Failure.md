# Note 8: A Structural Failure

Quotation
---------

“Combined with the lack of a known path to remote code execution and the small team of
core developers with the necessary deep knowledge of the engine occupied with many
responsibilities, this decision process caused work on a fix to stall and restart
repeatedly over months. We won’t pretend otherwise: the delay was a structural failure,
caused by both the security team’s decision process and its lack of resources” (PHP
Foundation 2026, under “A first external audit and increased security focus”).

Commentary
---------

This makes our claim paragraph more complicated. We say AI found flaws that had been
hidden in PHP for over ten years. But according to the PHP Foundation people found the
first signs of the problem during a 2024 security audit. What they didnt have was proof
that the flaw could be used to break into a server. That proof came in August 2026 when
the security firm Calif reported a working attack with the same root cause (PHP
Foundation 2026), after using AI tools (Ntsele 2026). So AIs real role was proving how
dangerous the flaw was which I think is closer to attacking than defending. The passage also
shows the delay was caused by people and not so much the technology. The team couldnt agree and didnt
have enough engineers so a known problem sat unfixed for about two years. 

Subject terms
---------

human bottleneck; AI-assisted discovery; open-source maintenance