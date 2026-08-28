# Academic Research Digest — Learning Environments
**Window covered:** 29 July – 28 August 2026 (30 days) · **Compiled:** 28 August 2026

> Note on scope: the standing brief asks for the "last 7 days" in its framing but sets a 30-day cutoff in the selection criteria. This digest uses the 30-day window so genuinely new items aren't missed, and states each paper's exact date so the reader can see how recent it is within that window.

---

## AI & Learning Environments

### Self-Reported AI Usage for Learning in Computer Science Education: Relationships with Goal Orientation and Academic Help-Seeking
- **Authors:** Piret Luik, Karin Naruskov, Karmen Kalk, Merle Taimalu
- **Source:** arXiv preprint (arXiv:2608.21373)
- **Publication date:** August 2026 (per arXiv's ID-month convention; a specific submission day surfaced in search results but conflicted with that convention and is omitted here rather than reported unverified)
- **URL:** https://arxiv.org/abs/2608.21373

Surveying 236 students in a database course, the study finds that students' *help-seeking threat* — how socially costly asking for help feels — predicts both how often and how broadly they turn to AI tools, independent of goal orientation. For teaching quality, this reframes AI uptake as partly a proxy for whether students feel safe asking for help at all, suggesting that course climate (not just an AI-use policy) shapes how students actually use these tools. Through the lens of student psychological needs, the pattern suggests AI use can function as a low-threat substitute for relatedness-based support-seeking, with direct implications for how instructors scaffold competence and autonomy in AI-assisted learning.

---

## Comparative Learning Environments Research

### Learning environment perceptions among occupational therapy students in Norway: sociodemographic, study behaviors, and performance covariates to cluster allocation
- **Authors:** Amayra Tannoubi, Gry Mørk, Tore Bonsaksen (additional co-author reported in some sources)
- **Source:** *Learning Environments Research* (Springer)
- **Publication date:** Published online 17 August 2026
- **URL:** https://link.springer.com/journal/10984 (a stable direct article permalink could not be resolved — see transparency note)

Drawing on longitudinal data from 233 Norwegian occupational therapy students (2017–2020), this study clusters students into "negative" (~19%), "neutral" (~40%), and "positive" (~41%) learning-environment perception groups and links cluster membership to study behaviors and academic performance. For instructional effectiveness, the sizeable negative-perception minority — and its association with weaker study behaviors — points to concrete levers (structure, feedback, transparency of expectations) that programs could adjust rather than treating environment perception as a fixed student trait. Read through Self-Determination Theory, the clusters plausibly track how well the program supports competence (clear feedback, coherent structure) and relatedness (peer/faculty connection), positioning "learning environment" as a needs-support variable rather than a purely descriptive label.

---

## SDT, Belonging & Student Well-Being

### Sense of belonging and academic outcomes among postsecondary students: a meta-analysis
- **Authors:** Not reliably identified from available sources (see transparency note)
- **Source:** *Frontiers in Psychology*
- **Publication date:** Reported as 5 August 2026 in two independent search results; a third result reported 7 July 2026. Flagged as unresolved rather than silently reconciled.
- **URL:** https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2026.1841185/full

Synthesizing 83 correlational studies, this meta-analysis finds sense of belonging correlates moderately with academic motivation (r≈0.30), interest (r≈0.44), and self-efficacy (r≈0.36), but functions more as a motivational/psychosocial resource than a direct driver of performance outcomes. For teaching quality, this argues for treating belonging-building (inclusive facilitation, early low-stakes interaction) as an investment in motivational infrastructure rather than a performance lever expected to move grades directly. The outcome set itself — motivation, interest, self-efficacy — maps closely onto what Self-Determination Theory predicts relatedness should feed into, reinforcing belonging as one leg of the autonomy–competence–relatedness triad rather than a stand-alone construct.

---

## Search Scope & Transparency Note

**Databases queried:** Live web search only (Google Scholar, ArXiv, Learning Environments Research/Springer, Frontiers, ResearchGate, PMC, ScienceDirect, Taylor & Francis, MDPI, and general web).

**What worked:** Web search surfaced candidate papers across all requested theme areas and multiple publishers.

**What didn't, and why:** This session's network egress policy blocks direct HTTP(S) access to `arxiv.org`, `link.springer.com`, `www.frontiersin.org`, `pmc.ncbi.nlm.nih.gov`, and `api.semanticscholar.org` (confirmed via repeated `EGRESS_BLOCKED` errors on both a native `arxiv`/`scholarly`-style API call and page-level fetches). This ruled out:
- Native ArXiv API/`arxiv` package queries — fell back to web-search snippets of arXiv pages.
- OpenAlex and Semantic Scholar API queries (intended as the Scopus fallback per protocol) — blocked outright, so the Scopus fallback chain landed on Google Scholar/general web search instead.
- Direct verification of full text, exact dates, and full author lists on Springer/Frontiers/PMC pages — all bibliographic details above come from search-engine snippets, which is a weaker source than the primary page and occasionally produced conflicting facts (flagged inline where found, e.g. the belonging meta-analysis's date and one arXiv submission-date claim that contradicted the ID convention).

**Selection outcome:** Several additional candidates were found and excluded — either because their true publication dates fell outside the 30-day window (a number of "2026" search hits were actually from January–May 2026, e.g. two DEI/belonging studies and two other *Learning Environments Research* articles), or because a title or author list could not be confirmed with confidence (one *Learning Environments Research* article by Burns, Luo & Perlman, published 17 Aug 2026, was identified but its title could not be verified and is omitted rather than guessed).

**Net result:** 3 papers met both the date and keyword criteria with confirmable bibliographic details, spanning all three requested themes. This is a narrower yield than a full database sweep (with working API access) would likely produce.
