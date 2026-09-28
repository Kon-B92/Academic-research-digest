# Academic Research Digest — Learning Environments
**Window covered:** 29 August – 28 September 2026 (30 days) · **Compiled:** 28 September 2026

> Note on scope: the standing brief asks for the "last 7 days" in its framing but sets a 30-day cutoff in the selection criteria. As in the prior digest, this edition uses the 30-day window so genuinely new items aren't missed, and states each paper's exact date so the reader can see how recent it is within that window.

---

## AI & Learning Environments

### Flawed but Memorable: Student Critical Reception of Interest-Personalized GenAI Analogies in Computing Education
- **Authors:** Seth Bernstein (University of Michigan, Ann Arbor), Naaz Sibia (University of Toronto)
- **Source:** arXiv preprint (arXiv:2609.06095)
- **Publication date:** September 2026 (per arXiv's ID-month convention)
- **URL:** https://arxiv.org/abs/2609.06095

Ten students who had completed CS2 evaluated GenAI-generated analogies personalized to their stated interests (for linked lists and recursion) against generic technical explanations, via a think-aloud annotation task and follow-up interview. Most found the personalized analogies more engaging and memorable than generic ones, but trust was split — some students trusted the tailoring more, while others scrutinized it more closely or distrusted the personalization itself, especially where the underlying comparison was flawed. For teaching quality, the finding complicates a simple "personalize to engage" heuristic: instructors deploying GenAI explanations may need to explicitly teach students to critically evaluate AI-generated analogies rather than assume personalization alone improves understanding. Through the SDT lens, interest-based personalization is autonomy-supportive (content shaped around the learner's own interests) and can support relatedness (feeling seen as an individual), but the paper shows this can come at the expense of competence when a flawed-but-memorable analogy embeds inaccurate assumptions the learner is not positioned to catch.

---

## Comparative Learning Environments Research

### "The best of both worlds": exploring a hybrid coworking and early learning environment
- **Author:** Tipsuda Chaomuangkhong
- **Source:** *Learning Environments Research* (Springer), Vol. 29, Article 50
- **Publication date:** 24 September 2026
- **URL:** https://link.springer.com/article/10.1007/s10984-026-09607-x

Drawing on 12 months of ethnographic fieldwork and 175 hours of participant observation at a "Work & Fun Hub" — a hybrid coworking and early-childhood space — this study identifies five sociospatial design categories (visual connectivity, permeable separation, flexible zoning, negotiated control, sensory regulation) that let caregivers, children, and staff negotiate play-based learning, collective supervision, and adult work side by side, while also surfacing tensions around noise, crowding, and competing needs for focus and rest. For instructional effectiveness, the study reframes "environment design" itself as a pedagogical act in out-of-school settings: zoning and sightline choices function as an implicit curriculum shaping what kinds of learning and supervision are even possible. Read through student (here, child) psychological needs, flexible zoning and negotiated control map onto autonomy and competence (room to explore and self-regulate), while collective caregiving spaces support relatedness — but the documented tensions (unmet needs for rest and focus) show that hybrid environments can service some of the three needs only by trading off against others, rather than satisfying all three simultaneously.

---

## DEI, Belonging & SDT-Aligned Student Engagement

### Who Gets Engaged? Zoomed in on Diversity Interventions in STEM Education
- **Authors:** Charlotte Popp, Diana Wengler, Heidrun Stoeger, Albert Ziegler
- **Source:** *Education Sciences* (MDPI), Vol. 16, Issue 9, Article 1563
- **Publication date:** September 2026 (exact day not resolvable from available sources — see transparency note)
- **URL:** https://www.mdpi.com/2227-7102/16/9/1563

This review examines diversity interventions for underrepresented groups (women, ethnic minorities, students with special educational needs) in STEM, cataloguing mentoring programs, summer schools, hands-on activities, and curriculum-integrated lessons designed to raise STEM engagement and performance while fostering belonging and self-efficacy. For teaching quality, the "zoomed in" framing pushes back on treating DEI interventions as interchangeable — the review implies that engagement effects vary by intervention design and target population, meaning instructors and program designers need evidence at the level of specific intervention types rather than "DEI programming" as an undifferentiated category. Through the SDT lens, the reviewed interventions target competence (self-efficacy building via hands-on activities and mentoring) and relatedness (belonging, mentor relationships) as the mechanisms linking DEI efforts to engagement; autonomy is comparatively underspecified in the intervention types summarized, a potential gap for future intervention design to address.

---

## Search Scope & Transparency Note

**Databases queried:** Live web search only (Google Scholar-indexed results, ArXiv, Learning Environments Research/Springer, MDPI Education Sciences, PubMed/PMC, Frontiers, Taylor & Francis, ResearchGate, and general web).

**What worked:** Web search surfaced candidate papers across all three requested theme areas, including exact online-first publication dates for several Learning Environments Research and Frontiers articles pulled directly from search-result metadata.

**What didn't, and why:** As in the prior digest, this session's network egress policy blocks direct HTTP(S) access to primary-source domains — confirmed via repeated `EGRESS_BLOCKED` errors this run on `arxiv.org`, `pubmed.ncbi.nlm.nih.gov`, `link.springer.com`, `www.mdpi.com`, `api.openalex.org`, and `www.researchgate.net`. This ruled out:
- Native ArXiv API/`arxiv` package queries and direct abstract-page fetches — fell back to web-search snippets.
- OpenAlex API queries (the intended Scopus fallback per protocol) — blocked outright; the Scopus fallback chain landed on Google Scholar/general web search instead, as no Scopus access was available either.
- Direct verification of full text and exact publication days on Springer, MDPI, and PubMed pages — bibliographic details above come from search-engine snippets, which is weaker than the primary source. The exact publication day for the MDPI paper could not be pinned down beyond "September 2026, Issue 9" and is reported as such rather than guessed.
- ResearchGate and Academia.edu direct browsing — reverted to indexed web-search snippets of their listing pages, per the protocol's own fallback instruction.

**Selection outcome:** Several additional candidates were identified and excluded as outside the 29 August–28 September window despite initial promise — notably a *Learning Environments Research* article on faculty leadership and psychological safety in a graduate anatomy course (published 27 August 2026, two days before the window opened) and a Frontiers in Psychology study on AI-enhanced flipped learning and student engagement (published 19 August 2026). Both are recent and topically strong (psychological safety ties directly to relatedness; the flipped-learning study to engagement and self-regulation) but fell just outside the 30-day cutoff and are omitted rather than stretched in. A number of DEI/belonging and SDT-in-education papers surfaced in search results dated across 2025 and early-to-mid 2026 were likewise excluded on date grounds.

**Net result:** 3 papers met both the date and keyword criteria with confirmable bibliographic details, one per requested theme (AI, comparative learning environments, and DEI/SDT-aligned engagement). This is consistent with the prior digest's yield and reflects the same structural limitation: without working API access to ArXiv, Scopus/OpenAlex, or PubMed, date and author verification depends on search-engine snippets rather than primary sources.
