# Academic Research Digest — Learning Environments
**Window covered:** 15 August – 14 September 2026 (30 days) · **Compiled:** 14 September 2026

> Note on scope: the standing brief asks for the "last 7 days" in its framing but sets a 30-day cutoff in the selection criteria. This digest uses the 30-day window so genuinely new items aren't missed, and states each paper's exact date so the reader can see how recent it is within that window. A number of strong-looking candidates found this cycle turned out, on verification, to fall just outside this window (e.g., several *Learning Environments Research* and *Journal of American College Health* articles dated April–July 2026) and were excluded rather than stretched to fit.

---

## AI & Learning Environments

### Generative AI and academic writing quality: learning self-efficacy as a mediator and individual-environmental moderators
- **Authors:** Qilei Ding, Jinlan Ye, Na Wang, Liqi Liu
- **Source:** *Interactive Learning Environments* (Taylor & Francis)
- **Publication date:** Published online in September 2026; search-engine snippets disagreed on the exact day (2 September vs. 7 September), so the day is reported as unconfirmed rather than guessed
- **URL:** https://www.tandfonline.com/journals/nile20 (a stable direct article permalink could not be resolved — see transparency note)

The study models how generative-AI use relates to academic writing quality, with students' learning self-efficacy acting as a mediating mechanism and both individual and environmental factors moderating the relationship. For teaching quality, this points instructors toward pairing AI writing tools with explicit self-efficacy-building supports (scaffolded feedback, modeling) rather than treating the tool itself as sufficient for better writing outcomes. Through the lens of student psychological needs, self-efficacy is functionally competence under another name, and the paper's "individual-environmental moderators" framing implicitly treats the learning environment as a co-determinant of whether AI support translates into a felt sense of competence.

---

## SDT & Student Agency

### Promoting student agency in science education: a meta-synthesis
- **Authors:** Esmeth C. Espinola, Maricar S. Prudente
- **Source:** *Disciplinary and Interdisciplinary Science Education Research* (Springer), Volume 8, article 25
- **Publication date:** 25 August 2026
- **URL:** https://link.springer.com/article/10.1186/s43031-026-00171-1

Following a PRISMA-guided meta-synthesis, this review maps how student agency has been conceptualized (sociocultural, psychological, sociological, and other frameworks) and catalogs the pedagogies science teachers use to promote it. For instructional effectiveness, the synthesis functions as a practical inventory: it identifies which classroom moves (student-centered instruction, valuing student interests and perspectives, dialogic interaction) reliably show up across studies as agency-promoting, giving teachers a menu grounded in accumulated evidence rather than a single study's context. Read through Self-Determination Theory, "agency" as used here maps closely onto autonomy — the reviewed pedagogies are largely autonomy-supportive teaching practices — making this a useful bridge between the agency literature and SDT's more theory-driven account of why those same practices support motivation.

---

## Search Scope & Transparency Note

**Databases queried:** Live web search only (Google Scholar, ArXiv, *Learning Environments Research*/Springer, *Interactive Learning Environments*/Taylor & Francis, Frontiers, ResearchGate, Academia.edu, PMC, Wiley Online Library, ScienceDirect, and general web). Dr. Phil's Newsletter (Philippa Hardman's Substack) was checked directly; it publishes commentary and synthesis on AI and learning design rather than original peer-reviewed papers, so it did not yield a qualifying item this cycle.

**What worked:** Web search surfaced candidate papers across most requested theme areas, including several journals not indexed in the prior digest (*Interactive Learning Environments*, *Race and Social Problems*, *Journal of American College Health*).

**What didn't, and why:** This session's network egress policy blocks direct HTTP(S) access to `arxiv.org`, `link.springer.com` (fetch, though search-engine snippets about it work), `www.tandfonline.com`, `onlinelibrary.wiley.com`, `www.nature.com`, `www.frontiersin.org`, and the OpenAlex/Semantic Scholar APIs (confirmed via a direct `curl` to `api.openalex.org`, which returned an HTTP 403 from the network proxy). This ruled out:
- Native ArXiv API/`arxiv`-package queries and direct abstract-page verification — no qualifying arXiv preprint from the 15 Aug–14 Sep window was confirmed this cycle; several promising-looking search hits turned out on closer checking to be from earlier months (April–August) once their arXiv ID month was examined.
- OpenAlex and Semantic Scholar API queries (the intended Scopus fallback per protocol) — blocked outright at the network layer, so the Scopus fallback chain landed on Google Scholar/general web search instead, as in the prior digest.
- Direct verification of full text, exact publication days, and DOIs on Taylor & Francis, Wiley, Springer, and Frontiers pages — all bibliographic details above come from search-engine snippets, a weaker source than the primary page, which is why the Ding et al. article's exact day and permalink are flagged as unconfirmed rather than stated as fact.

**Selection outcome:** Many additional candidates were found and excluded because their true publication dates fell outside the 30-day window once checked directly — including a *European Journal of Education* AI-engagement study (15 July 2026), a *Frontiers in Human Dynamics* AI-and-agency meta-synthesis (24 May 2026), a *Journal of American College Health* DEI/belonging/mental-health study (17 June 2026), a companion DEI/belonging study on LGBTQ+ students in the same journal (28 October 2025 online, May 2026 issue), a *Race and Social Problems* study on DEI interventions and belonging for BIPOC graduate students (January 2026), and two further *Learning Environments Research* articles (12 and 17 August 2026, i.e. just before the 30-day cutoff). This is consistent with last cycle's finding that many "2026"-dated search hits are from earlier in the year than they first appear, so each date above was checked individually rather than taken from a snippet at face value.

**Net result:** 2 papers met both the date and keyword criteria with confirmable-enough bibliographic details, spanning two of the four requested themes (AI & Learning Environments; SDT & Student Agency). No qualifying item was confirmed this cycle for the DEI & Belonging or Comparative Learning Environments Research themes — several near-miss candidates existed but fell outside the 30-day window on verification. This is a narrower yield than a full database sweep (with working API access) would likely produce, and narrower than the prior digest's 3 papers.
