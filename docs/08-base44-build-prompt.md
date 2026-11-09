# Base44 Build Prompt

*(The single detailed prompt used to generate the first version of this site. Written before generation, then the live site was substantially hand-edited afterward — see `09-reflection.md`.)*

---

**What the site is for, in one sentence:**
A marketing / "about us" site for **Smart Library**, a solar-powered smart-library nonprofit initiative that helps **children in low-literacy regions of Niger** learn to read through AI-driven, personalized, gamified lessons delivered on rugged tablets — even without reliable electricity or internet.

**Who it is for:**
Adult decision-makers, not children: local and national government education officials, donor organizations (e.g. UNICEF), corporate data-partnership contacts, and individual donors/press. They care about credibility, cost-per-child, security of hardware and data, measurable impact, and a clear path to partner or give. This is explicitly NOT a kids' app UI — it should read like a serious nonprofit/edtech institutional site.

**Pages I want, and what belongs on each** (full detail in `03-sitemap.md`):
1. **Home** — hero with one-sentence value prop + CTA, two real photos flanking two headline statistics (90% of Niger's children in poverty; 93% of grade 2–5 students can't read to grade level, sourced to UNICEF), a "clear message" grid (Who We Are / What We Do / Value We Offer / Why Look Closer), a "Problem" section on the literacy-poverty cycle, a one-line "Our Innovation" teaser linking to Features, a regional stats band, and a closing CTA.
2. **About Us** — must use tabbed navigation across exactly these four sections: **Our Story**, **Who We Are**, **Why We Created This**, **Testimonials** (rotating carousel).
3. **Features** — one block per major feature (AI Reading Tutor, Adaptive Lesson Difficulty / Machine Learning, Solar+IoT Monitoring), each with a concept-rendering image, plain-language explanation, and an explicit "Why it matters" line connecting it back to the value proposition; end with a table mapping Feature → 4IR Technology → Barrier Removed.
4. **Where We Work** — why Niger, the three pilot regions (Maradi, Zinder, Dosso) as individual cards, site-selection criteria, expansion plan.
5. **Get Involved** — three partner tracks (Local Government / Donor Orgs / Corporate), a responsible-data-partnership section (opt-in, anonymized), a "what funding builds" grid, and three fixed donation tiers ($120 tablet / $2,500 shed power / $8,000 full library).
6. **Contact** — a working-style contact form (name, email, organization, reason dropdown, message) plus direct contact details.

**My actual copy — use this verbatim, do not invent new messaging:**
See `06-site-copy.md` for the full page-by-page copy (headlines, value propositions, feature descriptions, About Us content, and every CTA). Paste that document's content directly into each corresponding page; only lightly adjust for UI constraints (character limits in buttons/eyebrows), never change the meaning or statistics.

**Design direction — three reference sites and what to borrow from each** (full detail in `05-design-inspiration.md`):
- **charity: water** (charitywater.org) → borrow the "huge real photo + blunt impact number" hero pairing and the one-CTA-per-section discipline.
- **Lexia Learning** (lexialearning.com) → borrow the credibility-first separation of "how the technology works" from "who it's for," and the professional, non-cartoonish education-sector tone.
- **Pencils of Promise** (pencilsofpromise.org) → borrow leading with the global literacy statistic before any solution pitch, and segmenting the "Get Involved" page into distinct funder pathways with specific dollar tiers.
Do not copy layout code, text, or images from these sites — only the structural patterns described above, reinterpreted in our own brand.

**Visual style:**
- **Colors:** solar orange `#F4A300` (primary/CTA), deep night blue `#0B3954` (secondary/nav/footer), warm sand `#FDF6EC` (background), green `#2E8B57` (positive/growth accents), red `#C94C4C` (used only in "the problem" statistics, sparingly).
- **Fonts:** Poppins (600–800) for all headings; Nunito Sans (400–700) for body text.
- **Mood:** mission-driven and credible-technical — not playful/childish (that's the separate kids' app, not this site), not sterile-corporate either. Confident, data-backed, human.
- **Product images:** use the two real photographs of Nigerien children (provided separately) only in the homepage hero flanking the statistics — do not use stock photography elsewhere. For the Features page, since the physical product doesn't exist yet, use clearly-labeled "concept rendering" mockups (styled UI/dashboard illustrations) instead of claiming real screenshots.

**Primary call to action, and where it should appear:**
"Support a Library" / "Partner With Us" — persistent in the top navigation on every page, repeated as the hero CTA on Home, and as the final CTA band on every inner page, all routing to `get-involved.html` (donation tiers) or `contact.html` (partnership inquiries).
