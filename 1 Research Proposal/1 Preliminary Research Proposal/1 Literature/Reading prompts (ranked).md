# Reading prompts (ranked)

Read top to bottom. For each paper: upload the PDF to Claude, copy the whole grey block, paste, send. Then check the output against the PDF before it goes into the workbook. Fill-ins are drafts: change them if your question changes. Cite-only claims are draft sentences; the prompt checks and rewrites them.

Not on this list? Paste its abstract into the triage prompt at the bottom.


## Tue 6 Oct

### 1. Li, Vertinsky & Li (2014)  (Deep, Must)
File: 2r ...pdf  |  Why here: A. Gap and closest work: closest model paper (distance -> exit success, moderators tested)

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How each distance (institutional, cultural, geographic) is measured, how international experience moderates distance, how exit success is coded, and the result for VC industry specialization in Table 2.
```

### 2. Bertoni, F., & Groh, A. P. (2014)  (Deep, Must)
File: 3e ...pdf  |  Why here: A. Gap and closest work: cross-border performance in Europe, decides how narrow your gap sentence must be

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Which European countries and years are covered, how cross-border is defined (investor HQ or office), whether distance is measured or only foreign vs domestic, and what the authors say is still unknown for Europe.
```

### 3. Moore, C. B., Payne, G. T., Bell, R. G., & Davis, J. L. (2015)  (Deep, Must)
File: 4e ...pdf  |  Why here: A. Gap and closest work: shows distance studied for flows, not performance

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): This paper studies flows, not performance: note which institutional dimensions matter, how institutional distance is measured, and whether European countries are in the sample.
```

### 4. Bottazzi, L., Da Rin, M., & Hellmann, T. (2016)  (Deep, Must)
File: download first  |  Why here: A. Gap and closest work: European deals + a country pair feature; biggest overlap risk

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How trust between nations is measured (Eurobarometer), whether trust works through selection or performance, why more trust goes with fewer successful exits, and whether other distance measures are included.
```

### 5. Compano, R., Johanyak, J., Testa, G., Zhen, Q., & Tuebke, A. (2026)  (Deep, Must)
File: download first  |  Why here: A. Gap and closest work: most recent European distance study (flows)

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): The unit of analysis (region pairs), which proximity types are measured, which ecosystem features moderate distance, and whether any performance outcome is studied.
```

### 6. Alhorr, H. S., Moore, C. B., & Payne, G. T. (2008)  (Deep, Must)
File: download first  |  Why here: A. Gap and closest work: EU integration as a pair-level factor

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How EU economic integration is measured, whether integration weakens the effect of distance, and the time period and countries.
```


## Wed 7 Oct

### 7. Devigne, D., Manigart, S., Vanacker, T., & Mulier, K. (2018)  (Deep, Must)
File: 0a ...pdf  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): The future research agenda: every open question on what weakens or strengthens the liability of foreignness or distance in VC, and on European cross-border VC.
```

### 8. Boryniec, P., Li, Y., & Tan, J. (2025)  (Deep, Must)
File: 0b ...pdf  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): The research agenda and any table that lists moderators or contingencies of cross-border VC performance.
```

### 9. Hutzschenreuter, T., Kleindienst, I., & Lange, S. (2016)  (Deep, Must)
File: download first  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Their classification of distance dimensions and which moderators of distance effects they call underexplored.
```

### 10. Beugelsdijk, S., Kostova, T., Kunst, V. E., Spadafora, E., & van Essen, M. (2018)  (Deep, Must)
File: download first  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Which moderators of the cultural distance effect the meta-analysis tests (e.g. experience, entry mode, host country development) and their direction.
```

### 11. Zhou, C., Kwon, Y., Zhang, Y., Li, J., Kim, J., & Heo, Y. (2021)  (Deep, Must)
File: 0d ...pdf  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Which moderators of national distance appear across the reviewed studies and which ones the authors call understudied.
```

### 12. Tihanyi, L., Griffith, D. A., & Russell, C. J. (2005)  (Deep, Must)
File: download first  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Whether cultural distance relates to performance and which moderators (home country, industry, sample) change that relationship.
```

### 13. Tykvova, T., & Schertler, A. (2014)  (Deep, Must)
File: 4c ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How local syndication partners moderate geographic and institutional distance, which outcome is used, and whether European deals are in the sample.
```

### 14. Liu, Y., & Maula, M. (2021)  (Deep, Must)
File: 2i ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How host-country regulatory institutions moderate the effect of network status on performance, and how performance is coded.
```

### 15. Alvarez-Garrido, E., & Guler, I. (2018)  (Deep, Must)
File: 6a ...pdf  |  Why here: C. Moderator discovery: tests moderators (only paper in folder with a pair feature as moderator)

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Which country-pair or host-country features moderate the value of status, and how selection is handled.
```


## Thu 8 Oct

### 16. Nahata, R., Hazarika, S., & Tandon, K. (2014)  (Deep, Must)
File: download first  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Which institutional and cultural measures predict success, and whether any factor (experience, local partner, legal origin) moderates them.
```

### 17. Dai, N., & Nahata, R. (2016)  (Deep, Must)
File: 4a ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How cultural distance shapes syndication with local VCs, how this relates to exits, and how cultural distance is computed.
```

### 18. Chemmanur, T. J., Hull, T. J., & Krishnan, K. (2016)  (Deep, Must)
File: 1i ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Whether local co-investors complement international VCs, which outcome is used, and how international vs local VC is defined.
```

### 19. Devigne, D., Manigart, S., & Wright, M. (2016)  (Deep, Must)
File: Not Screened Yet: 1-s2.0-S0883902616000033-main.pdf  |  Why here: Design reference for the main outcome

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How follow-on investment decisions are defined and coded (my main outcome), and how domestic and international investors differ in them.
```

### 20. Mingo, S., Morales, F., & Dau, L. A. (2018)  (Deep, Must)
File: 4f ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How regional networks moderate national distances, and how distances are measured (Mahalanobis on WGI).
```

### 21. Huang, X., Qiu, B., Wu, J., & Yao, X. (2023)  (Deep, Must)
File: 4b ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How networks and trust moderate institutional and geographic distance, and whether this logic could transfer to country pairs within Europe.
```

### 22. Northemann, A. (2023)  (Deep, Must)
File: 1c ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How industry specialization is measured and whether it changes the effect of distance on the internationalization decision.
```

### 23. Zhang, J., & Pezeshkan, A. (2016)  (Deep, If time)
File: 5b ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How host country network and industry experience interact, and whether either moderates a distance effect.
```

### 24. Wesemann, H., & Antretter, T. (2023)  (Deep, If time)
File: 2f ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How syndication moderates the effect of distance on returns, and how distance is measured.
```

### 25. Qiu, B., Chen, J., & Yang, J. (2021)  (Deep, If time)
File: 1a ...pdf  |  Why here: C. Moderator discovery: tests moderators

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): How reputation moderates the liability of foreignness in syndication choices.
```

### 26. Stahl, G. K., Tung, R. L., Kostova, T., & Zellmer-Bruhn, M. (2016)  (Deep, If time)
File: download first  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): Which alternative views of distance (positive effects, diversity, foreignness) and which moderators the authors propose.
```

### 27. Zaheer, S., Schomaker, M. S., & Nachum, L. (2012)  (Deep, If time)
File: download first  |  Why here: B. Moderator discovery: reviews

```text
You are helping me extract research design information from an academic paper for my master's thesis proposal. My topic (still open, I am reading to decide the design): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. My supervisor has set: Europe as scope, the startup's first institutional round, a foreign lead investor, follow-on funding as main outcome, and logit models. Moderators, distance measures and controls are still to be decided, so do not filter on my current ideas: report everything the paper does.

Read the attached paper and fill in the template below. Rules:
- Only report what the paper actually says. If something is not reported, write "Not reported". Never guess or fill in from general knowledge.
- Give a page number for every item. For definitions, measures and key findings, add a short direct quote (max 25 words).
- Use (Author, Year) in every bullet and every table row.
- PART A: write short bullets I can paste into my proposal and rewrite. End each section with "Use for my thesis:" (copy / adapt / avoid, and why, max 2 sentences).
- PART B: be EXHAUSTIVE. List every item the paper uses, also ones that seem irrelevant to my study. Output each as a table row with exactly the columns given, separated by " | ", one row per item, no extra text between rows.

=== PART A: DESIGN CHOICES (bullets) ===
A0. Reference: full APA 7 reference; research question (1 sentence); countries/region and time period.
A1. Scope and sample: unit of analysis; which financing round(s) and why; definition of "cross-border"/"foreign"; how the lead investor is identified; investor types included/excluded; sector scope; exclusion rules; final sample size.
A2. Method: estimation model(s); how interactions are tested and interpreted; standard errors (clustering); selection/endogeneity approach and its justification.
A3. Findings (only hypotheses on distance, moderators of distance, or follow-on funding / exit success): result per hypothesis, effect size if reported.
A5. Moderators: (a) every moderator the paper TESTS (what it moderates, mechanism, result); (b) every moderator, boundary condition or contingency the authors SUGGEST in the discussion or future research but do not test; (c) which of these could apply to cross-border deals within Europe, and why (max 2 sentences each).
A4. Relevance to my thesis: which parts of my proposal it could support (theory, distance, Europe/gap, moderators, method); which design options it suggests that I have not considered yet; one sentence I could cite it for.

=== PART B: COMPLETE INVENTORIES (table rows) ===
L1 Theories: Paper | Theory | What it is used to explain | Page
L2 Outcomes (main AND alternative): Paper | Outcome | Main or alternative | Exact definition/coding | Time window | Data source | Page
L3 Distance and other main independent variables: Paper | Variable | Type (institutional/cultural/geographic/psychic/other) | Indicators used | Formula | Data source and year | Page
L4 Moderators (every interaction tested AND every moderator suggested): Paper | Moderator | Tested or suggested | Level (investor/deal/venture/home country/host country/country pair) | Relationship moderated (X -> Y) | Expected sign | Mechanism (1 sentence) | Result | Page
L5 Controls (every control variable): Paper | Control | Level (investor/deal/venture/home country/host country/country pair/time) | Measurement | Data source | Page
L6 Fixed effects: Paper | Fixed effect | Page
L7 Robustness checks: Paper | Check | What it addresses | Result changed? (yes/no) | Page
L8 Data sources: Paper | Database | Used for | Coverage problem admitted | Page
L9 Limitations and future research: Paper | Type (limitation/future research) | Statement | Relevant to cross-border VC in Europe, moderators of distance, or follow-on funding? (yes/no) | Page

Extra focus for this paper (answer this in A3/A5 as well): The critique of symmetric distance and what it implies for measuring distance between country pairs (direction, asymmetry).
```

### 28. Guiso, L., Sapienza, P., & Zingales, L. (2009)  (Targeted, Must)
File: download first  |  Why here: D. Moderator theory (pair features)

```text
Read the attached paper. What I want to learn from this paper: how bilateral trust between European countries is measured, how it affects trade and investment, and the role of common language and shared history.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 29. Grinblatt, M., & Keloharju, M. (2001)  (Targeted, Must)
File: download first  |  Why here: D. Moderator theory (pair features)

```text
Read the attached paper. What I want to learn from this paper: how shared language and culture affect investment choices, and the information mechanism behind it.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 30. Portes, R., & Rey, H. (2005)  (Targeted, Must)
File: download first  |  Why here: D. Moderator theory (pair features)

```text
Read the attached paper. What I want to learn from this paper: how bilateral trade and information frictions explain cross-border equity flows.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 31. Hegde, D., & Tumlinson, J. (2014)  (Targeted, Must)
File: download first  |  Why here: D. Moderator theory (pair features)

```text
Read the attached paper. What I want to learn from this paper: how social proximity affects both which startups VCs select and how those startups perform (selection vs performance).
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 32. Dow, D., & Karunaratna, A. (2006)  (Targeted, Should)
File: download first  |  Why here: D. Moderator theory (pair features)

```text
Read the attached paper. What I want to learn from this paper: which psychic distance stimuli (language, religion, colonial ties, industrial development) are measured and how.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 33. [Authors to check] (2024)  (Targeted, Should)
File: download first  |  Why here: D. Novelty check

```text
Read the attached paper. What I want to learn from this paper: what it finds on culture as an informal institution in cross-border VC, which moderators it tests, and whether it overlaps with my study (novelty check).
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```


## Fri 9 Oct

### 34. Tian, X. (2011)  (Targeted, Must)
File: download first  |  Why here: E. Outcome (follow-on funding)

```text
Read the attached paper. What I want to learn from this paper: how distance between VC and startup affects staging and follow-on rounds, and how follow-on rounds are counted.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 35. Gompers, P. A. (1995)  (Targeted, Must)
File: download first  |  Why here: E. Outcome (follow-on funding)

```text
Read the attached paper. What I want to learn from this paper: why staged financing and follow-on rounds signal progress, and how a financing round is defined.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 36. Hochberg, Y. V., Ljungqvist, A., & Lu, Y. (2007)  (Targeted, Must)
File: download first  |  Why here: E. Outcome (follow-on funding)

```text
Read the attached paper. What I want to learn from this paper: how they define investment success (survival to a later round or exit) and how VC network position is measured.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 37. Alexy, O. T., Block, J. H., Sandner, P., & Ter Wal, A. L. J. (2012)  (Targeted, Should)
File: download first  |  Why here: E. Outcome (follow-on funding)

```text
Read the attached paper. What I want to learn from this paper: how subsequent funding is used as a performance outcome for early-stage startups.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 38. Zaheer, S. (1995)  (Targeted, Must)
File: 1 ...pdf  |  Why here: F. Theory: foreignness and distance

```text
Read the attached paper. What I want to learn from this paper: the definition and sources of the liability of foreignness, and how foreign firms overcome it.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 39. Kostova, T. (1999)  (Targeted, Must)
File: Not Screened Yet: Transnational_transfer_of_stra.pdf  |  Why here: F. Theory: foreignness and distance

```text
Read the attached paper. What I want to learn from this paper: the definition of institutional distance and its regulatory, cognitive and normative pillars.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 40. Xu, D., & Shenkar, O. (2002)  (Targeted, Must)
File: download first  |  Why here: F. Theory: foreignness and distance

```text
Read the attached paper. What I want to learn from this paper: how institutional distance affects foreign firms and which institutional pillars matter most.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 41. Beugelsdijk, S., Ambos, B., & Nell, P. C. (2018)  (Targeted, Must)
File: 0c ...pdf  |  Why here: F. Theory: foreignness and distance

```text
Read the attached paper. What I want to learn from this paper: best practice for measuring distance: which indicators and formulas to use, and which pitfalls to avoid.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 42. Berry, H., Guillen, M. F., & Zhou, N. (2010)  (Targeted, Must)
File: download first  |  Why here: F. Theory: foreignness and distance

```text
Read the attached paper. What I want to learn from this paper: the dimensions of cross-national distance, their data sources, and why the Mahalanobis method is used.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 43. Kogut, B., & Singh, H. (1988)  (Targeted, Must)
File: Not Screened Yet: palgrave.jibs.8490394.pdf  |  Why here: F. Theory: foreignness and distance

```text
Read the attached paper. What I want to learn from this paper: the Kogut-Singh cultural distance index: formula, data and rationale.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 44. Buchner, A., Espenlaub, S., Khurshed, A., & Mohamed, A. (2018)  (Targeted, Must)
File: 2e ...pdf  |  Why here: G. Europe and introduction

```text
Read the attached paper. What I want to learn from this paper: how returns of cross-border and domestic VC investments differ, and the foreignness mechanism behind it.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 45. Liu, Qiu, Bu, Xie & Han (2026)  (Targeted, Must)
File: 2q ...pdf  |  Why here: G. Europe and introduction

```text
Read the attached paper. What I want to learn from this paper: what multinational VC does to startup performance in Europe, which outcome and data they use, and whether distance is measured (overlap check).
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 46. Bosio, Buttice, Crisanti, Croce & Signore (2025)  (Targeted, Should)
File: 3b ...pdf  |  Why here: G. Europe and introduction

```text
Read the attached paper. What I want to learn from this paper: how Brexit changed cross-border VC between the UK and the EU, as evidence that institutional change within Europe affects VC.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 47. Gompers, P., Kovner, A., & Lerner, J. (2009)  (Targeted, Should)
File: Not Screened Yet: Economics Manag Strategy - 2009 - Gompers ...pdf  |  Why here: H. Mechanisms and investor level

```text
Read the attached paper. What I want to learn from this paper: how industry specialization is measured and how it relates to investment success.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 48. Kogut, B., & Zander, U. (1992)  (Targeted, Should)
File: Not Screened Yet: Kogut-KnowledgeFirmCombinative-1992.pdf  |  Why here: H. Mechanisms and investor level

```text
Read the attached paper. What I want to learn from this paper: the difference between tacit and codified knowledge, and why tacit knowledge transfers poorly across distance.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 49. Grant, R. M. (1996)  (Targeted, Should)
File: Not Screened Yet: Strategic Management Journal - Winter 1996 - Grant ...pdf  |  Why here: H. Mechanisms and investor level

```text
Read the attached paper. What I want to learn from this paper: the core claims of the knowledge-based view and the role of tacit knowledge.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 50. Granovetter, M. (1985)  (Targeted, Should)
File: Not Screened Yet: Granovetter-EconomicActionSocial-1985.pdf  |  Why here: H. Mechanisms and investor level

```text
Read the attached paper. What I want to learn from this paper: how embeddedness in social relations creates trust and shapes economic exchange.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 51. Sorenson, O., & Stuart, T. E. (2001)  (Targeted, Must)
File: Not Screened Yet: 321301.link.pdf  |  Why here: H. Mechanisms and investor level

```text
Read the attached paper. What I want to learn from this paper: why VC investment is local (information and monitoring costs of distance) and how syndication networks extend a VC's reach.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 52. Megginson, W. L., & Weiss, K. A. (1991)  (Targeted, Should)
File: Not Screened Yet: The Journal of Finance - July 1991 - MEGGINSON ...pdf  |  Why here: H. Mechanisms and investor level

```text
Read the attached paper. What I want to learn from this paper: the certification role of VC backing, as the mechanism behind attracting follow-on investors.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 53. Certo, S. T., Busenbark, J. R., Woo, H.-S., & Semadeni, M. (2016)  (Targeted, Must)
File: download first  |  Why here: I. Method

```text
Read the attached paper. What I want to learn from this paper: when a Heckman selection model is needed and what a valid exclusion restriction looks like.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 54. Hoetker, G. (2007)  (Targeted, Must)
File: download first  |  Why here: I. Method

```text
Read the attached paper. What I want to learn from this paper: how to interpret and test interaction effects in logit and probit models.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 55. Chen, H., Gompers, P., Kovner, A., & Lerner, J. (2010)  (Targeted, Should)
File: download first  |  Why here: I. Method

```text
Read the attached paper. What I want to learn from this paper: how VC office locations differ from headquarters and why that matters when measuring investor location.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 56. Mayer, T., & Zignago, S. (2011)  (Targeted, Should)
File: download first  |  Why here: I. Method

```text
Read the attached paper. What I want to learn from this paper: which bilateral variables (geographic distance, contiguity, common language) GeoDist contains and how each is coded.
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```

### 57. University of Antwerp PhD thesis (2020)  (Targeted, If time)
File: download first  |  Why here: Novelty check

```text
Read the attached paper. What I want to learn from this paper: whether any essay studies the performance of cross-border VC within Europe and which moderators it tests (overlap check).
Using only what the paper says (write "Not reported" otherwise), give:
(1) the full APA 7 reference;
(2) research question, sample and method in 3 bullets;
(3) the findings or arguments relevant to my section, as short paste-ready bullets with (Author, Year) and page number, plus a direct quote of max 25 words for definitions and key findings;
(4) the mechanism the paper gives (why the effect happens), if any;
(5) one sentence I could cite it for.
```


## Sat 10 Oct

### 58. Kollmann, Mullner & Puck (2025)  (Cite only, Must)
File: 1b ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "About 30% of VC investments involve a cross-border investor. [check the exact figure and year]"?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 59. Zhou, N., & Guillen, M. F. (2015)  (Cite only, Must)
File: Not Screened Yet: Strategic Management Journal - 2014 - Zhou ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "The liability of foreignness is not fixed: it declines as firms build experience in the host country."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 60. Ademi et al. (2026)  (Cite only, Must)
File: 0e ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Exits are the most common measure of venture performance, but they are rare and observed only with a long delay."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 61. Sahlman, W. A. (1990)  (Cite only, Must)
File: Not Screened Yet: 1-s2.0-0304405X90900658-main.pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "VCs stage their capital and monitor portfolio companies closely to reduce agency problems."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 62. Gorman, M., & Sahlman, W. A. (1989)  (Cite only, Must)
File: Not Screened Yet: 1-s2.0-0883902689900141-main.pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "VCs spend a large share of their time monitoring and assisting portfolio companies, often through board seats."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 63. Bernstein, S., Giroud, X., & Townsend, R. R. (2016)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Shorter travel time between VC and startup increases VC involvement and startup performance."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 64. Cumming, D., & Dai, N. (2010)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "VCs show a strong local bias in where they invest."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 65. Ghemawat, P. (2001)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Distance between countries has cultural, administrative, geographic and economic dimensions."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 66. Slangen, A. H. L., & Van Tulder, R. J. M. (2009)  (Cite only, Must)
File: Not Screened Yet: 1-s2.0-S0969593109000171-main.pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Governance quality explains foreign entry mode choices better than cultural distance."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 67. Guler, I., & Guillen, M. F. (2010)  (Cite only, Must)
File: Not Screened Yet: jibs.2009.35.pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Home and host country institutions shape where US VC firms invest abroad."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 68. Shenkar, O. (2001)  (Cite only, Must)
File: Not Screened Yet: palgrave.jibs.8490982.pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Common cultural distance measures rest on hidden assumptions such as symmetry and stability over time."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 69. Ahern, K. R., Daminelli, D., & Fracassi, C. (2015)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Cultural distance between countries reduces the number of cross-border mergers and their combined returns."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 70. Joshi, Chandrashekar, Brem & Momaya (2019)  (Cite only, Must)
File: 1j ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Research on foreign VC firms has focused largely on emerging markets such as India."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 71. Wang, L., & Wang, S. (2011)  (Cite only, Must)
File: 2a ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Studies of cross-border VC performance often use Chinese data."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 72. Humphery-Jenner, M., & Suchard, J.-A. (2013)  (Cite only, Must)
File: 2d ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Foreign VC involvement is associated with venture success in China."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 73. Dai, N., Jo, H., & Kassicieh, S. (2012)  (Cite only, Must)
File: 2n ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Foreign VCs select different ventures than local VCs, which must be accounted for when comparing exit performance."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 74. Taglialatela & Barontini (2025)  (Cite only, Must)
File: 3c ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Prior co-investments among European VC syndicate members are associated with exit outcomes."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 75. Christopoulos, Koeppl & Koppl-Turyna (2022)  (Cite only, Must)
File: 3g ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "A syndicate's network position affects the survival of European VC-backed companies."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 76. Meuleman, M., & Wright, M. (2011)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Institutional context and learning affect whether foreign private equity firms syndicate with local partners."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 77. Asdrubali & Testa. Cross-regional venture capital flows in Europe. European Commission / SSRN 6433315. [check if this is the same work as the JRC 2026 paper])  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Cross-regional VC flows in Europe are shaped by proximity between regions."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 78. Aizenman, J., & Kendall, J. (2012)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Cross-border VC investment is more likely between countries with a common language and closer economic ties."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 79. Cuypers, I. R. P., Ertug, G., & Hennart, J.-F. (2015)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Greater linguistic distance leads acquirers to take smaller stakes in cross-border acquisitions."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 80. Bengtsson, O., & Hsu, D. H. (2015)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "VCs are more likely to invest in founders who share their ethnic background."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 81. Gulati, R. (1998)  (Cite only, Must)
File: Not Screened Yet: Strategic Management Journal - 1998 - Gulati ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Prior ties between partners shape the formation and performance of alliances."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 82. Makela, M. M., & Maula, M. V. J. (2008)  (Cite only, Must)
File: 1e ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "A local co-investor helps a startup attract foreign VC by reducing the foreign investor's information disadvantage."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 83. Barney, J. (1991)  (Cite only, Must)
File: Not Screened Yet: barney-1991-...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Resources that are valuable, rare, hard to imitate and hard to substitute give a sustained competitive advantage."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 84. Wernerfelt, B. (1984)  (Cite only, Must)
File: Not Screened Yet: Strategic Management Journal - April June 1984 - Wernerfelt ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Firms can be analysed as bundles of resources rather than products."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 85. De Clercq, D., & Dimov, D. (2008)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "A VC firm's industry-specific knowledge improves its investment performance."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 86. Norton, E., & Tenenbaum, B. H. (1993)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "VCs manage risk through specialized knowledge rather than through diversification."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 87. Lehner (2023)  (Cite only, Must)
File: 5c ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Industry focus and geographic diversification of VC firms are related: firms that specialize by industry diversify more geographically. [check direction]"?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 88. Joshi, K. (2018)  (Cite only, Must)
File: 5d ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Foreign and domestic VC firms use different strategies to manage the risks of high-tech investments."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 89. De Prijcker, S., Manigart, S., Wright, M., & De Maeseneire, W. (2012)  (Cite only, Must)
File: 6b ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Experiential, inherited and external knowledge increase the likelihood that VC firms invest abroad."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 90. Gang & Kim (2025)  (Cite only, Must)
File: 2b ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Receiving follow-on funding is used as an outcome of VC syndication."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 91. Bedu, N., Brossard, O., & Montalban, M. (2024)  (Cite only, Must)
File: 2h ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Raising a later funding round is used as a measure of startup success."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 92. Nahata, R. (2008)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "More reputable lead VCs are more likely to bring their portfolio companies to a successful exit."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 93. Matusik, S. F., & Fitza, M. A. (2012)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "The relationship between VC firm diversification and performance is U-shaped."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 94. Knill, A. (2009)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "VC firms that diversify across industries perform differently from focused firms. [check direction]"?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 95. Sorensen, M. (2007)  (Cite only, Must)
File: Not Screened Yet: The Journal of Finance - 2007 - SORENSEN ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Part of the better performance of experienced VCs comes from selecting better companies, not only from adding value."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 96. Espenlaub, S., Khurshed, A., & Mohamed, A. (2015)  (Cite only, Must)
File: 2o ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Cross-border VC investments differ from domestic ones in exit route and time to exit."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 97. Cumming, D., Knill, A., & Syvrud, K. (2016)  (Cite only, Must)
File: 2l ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "International investors are associated with higher private firm value."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 98. Ai, C., & Norton, E. C. (2003)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "In logit and probit models, the interaction effect cannot be read from the coefficient of the interaction term."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 99. Wolfolds, S. E., & Siegel, J. (2019)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "A Heckman model without a valid exclusion restriction does not fix endogeneity and can make bias worse."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 100. Bertoni, F., Colombo, M. G., & Quas, A. (2015)  (Cite only, Must)
File: 3f ...pdf  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Investment patterns of European VC differ across investor types."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 101. Retterath, A., & Braun, R. (2020)  (Cite only, Must)
File: download first  |  Why here: J. Claim check while writing

```text
Does the attached paper support this claim: "Commercial VC databases differ in coverage, especially for early-stage deals."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 102. Hain, D., Johan, S., & Wang, D. (2016)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "Relational and institutional trust between countries increase cross-border VC investment."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 103. Devigne, D., Vanacker, T., Manigart, S., & Paeleman, I. (2013)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "Cross-border and domestic VC investors contribute differently to portfolio company growth, depending on the company's stage."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 104. Milanov, H., & Shepherd, D. A. (2013)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "A startup's first investors have a lasting influence on its later status."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 105. Bradley, W., Durufle, G., Hellmann, T., & Wilson, K. (2019)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "Policy makers care about cross-border VC because it brings capital and expertise to local startups."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 106. Viete, S., & Oschwald, D. (2025)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "Cross-border investors account for a large and growing share of VC in Germany and Europe. [check figure]"?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 107. Mariotti, S., & Piscitello, L. (1995)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "Information costs shape where foreign investors locate within a host country."?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```

### 108. [Authors to check] (2020)  (Cite only, If time)
File: download first  |  Why here: J. Claim check while writing (optional)

```text
Does the attached paper support this claim: "Euro adoption changed cross-border VC between member states. [check what is actually found]"?
Answer yes / partly / no. Quote the passage (max 40 words) with page number.
If partly or no, rewrite my sentence so it matches exactly what the paper says.
Give the full APA 7 reference.
```


## Triage prompt (new papers)

```text
Below is the abstract of a paper I found. My topic (still open): how distance between the investor's and the startup's country affects the performance of cross-border venture capital investments within Europe, and what weakens or strengthens that effect. I am especially looking for moderators of distance.
Based ONLY on the abstract, tell me:
(1) Reading level: Deep (tests or suggests moderators of distance or foreignness, or studies cross-border VC performance in Europe), Targeted (supports one theme), Cite only (one fact or claim), or Skip. One reason.
(2) Theme(s) from this list: Introduction / relevance; Liability of foreignness; Distance (types, mechanisms); Europe and gap; Moderators; Investor-level factors; Outcome / performance; Sample and data; Measures; Analysis and robustness; Limitations / future research.
(3) The fill-in for the matching prompt: Deep = one "Extra focus" line; Targeted = one "What I want to learn" line; Cite only = the one sentence I would cite it for.
(4) The APA 7 reference, with [check] on anything you cannot see in the abstract.
Abstract: [PASTE]
```
