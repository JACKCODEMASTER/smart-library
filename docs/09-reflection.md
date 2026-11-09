# Learning & Reflection

*Draft based on our actual build process — edit/personalize before submitting so it reflects your own voice and any details I (the AI) wouldn't know.*

## Where AI Helped
- **Speed of first scaffold:** Generating a consistent 6-page site (shared nav, footer, color system, typography) in one pass would have taken hours by hand; AI produced a working first draft in minutes, which we then iterated on rather than building from zero.
- **Consistency enforcement:** Keeping the same brand name, nav structure, and footer across every page as we made changes (e.g., renaming "Lumière Learning" to "Smart Library," renaming "Our Technology" to "Features") was handled with a single sweep instead of manually editing six files by hand and risking missed spots.
- **Drafting at volume:** The feature-to-technology mapping table, the hardware spec table, and the testimonial copy were all first-drafted by AI and then reviewed/trimmed for accuracy and tone.

## Where Human Judgment Was Essential
- **Deciding what to cut:** AI's first draft included a full "The Solution" feature-card section and a live IoT dashboard mockup in the hero — both were removed on request because a human reviewer (not the AI) judged they cluttered the homepage and repeated what the new Features page now covers in depth.
- **Real-world facts the AI cannot know or invent:** actual team member names and roles (Jack Ryan, Henry Barenbaum, Autum Barness, Safiyah Sugapong) had to come from us directly — AI only had placeholder names until corrected.
- **Sourcing real images:** AI cannot access or insert photos a user pastes into a chat; a human had to actually locate the downloaded image files on disk and tell the AI their real file paths before they could be wired into the homepage.
- **Honesty about what's real vs. conceptual:** choosing to label the Features page visuals as "concept renderings" rather than letting them pass as real screenshots was a deliberate human call to keep the site credible to the government/NGO audience it's trying to reach.

## What We'd Prompt Differently Next Time
- Provide the **real team roster and image files up front** in the very first prompt, instead of adding them in later follow-up turns — would have saved several back-and-forth corrections.
- Specify **which exact statistics to feature and how large to display them** (e.g., "make these two stats the biggest element on the page") in the initial build prompt rather than as a later revision.
- Decide on the **Features page split from the Technology page earlier** — splitting "how it works" from "home page solution teaser" was a mid-project restructuring that could have been part of the original sitemap if we'd planned the rubric requirements (Features Page as its own graded section) before the first generation.
