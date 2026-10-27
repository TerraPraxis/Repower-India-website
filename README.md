# EMPOWER India website

The EMPOWER India results website (formerly REPOWER India), version 17 (27 October 2026), by Terra Praxis. It follows the body order of report v4.4.

`index.html` is one self-contained page. It contains all its charts, maps and report renders. It makes no external requests and works offline.

The site is served with GitHub Pages from the `main` branch, root folder.

Version 12.4 (14 October 2026): text and cost chart aligned to the rulings register (about 1 TW of firm nuclear by 2070; about 25 GW a year; US$40.6 per MWh at 7% real and US$33.7 at 4%; five delivery stages; REPOWER as a strategy); the 50 MWe fast-reactor case removed. Source of the edits: `2. workings/website_draft_2026-10-14/patch_site_2026-10-14.py` in the project library.

Draft version 12.5 (18 October 2026, branch `draft/empower-rename-2026-10-18`, not published): renamed EMPOWER India; cover tagline "Power to empower. A vision for 1 TW of firm, clean power for India by 2070."; the verb "repower" replaced by "empower" (or "a new nuclear unit") in the text and chart labels. Source of the edits: `2. workings/website_rename_2026-10-18/patch_site_empower_2026-10-18.py` in the project library.

Version 16.2 (26 October 2026): a new page on report v4.4, built from the project source (`12-redraft/4_website/site/src_v16_2/`, builder `build_site_v16_2.py`), not patched from v12.5. Seven chapters: the need, the industry, the Empower strategy (pace, eight requirements, five delivery stages, schedule, cost, siting constraints), the programme (existing coal sites, large new sites, marine sites, with a site tracker), the benefits (jobs), sites first, and the conclusion. The 3D construction model and the supply-chain chapter are removed. The interactive Figure 10 map includes TeleGeography submarine-cable data (published at the owner's decision, 26 October 2026). Notes: `site/README_site_v16_2.md` in the project.

Version 16.3 (26 October 2026): cover subtitle "Delivering affordable, reliable, clean power at scale"; the Oxford comma in every list of the page copy, chart labels, and dialog titles. Notes: `site/README_site_v16_3.md` in the project.

Version 17 (27 October 2026): review comments from Isuru Seneviratne. "Built in series" is shown as indexed columns, with the starting value at 1×. The build-time chart names the country of each unit. The site-type colours follow report Figure ES1. In the table of how the three site types meet the siting constraints, a cell, row or column under the pointer stays in full and the others dim. The reconductoring text gives the thermal rating and says that the Gooty-Tumkur line gains redundancy, not transfer capacity. The jobs chart stacks the five activities in the colours of report Figure 19. The harbour text no longer states 0.59 GW per million people. Notes: `site/README_site_v17.md` in the project.
