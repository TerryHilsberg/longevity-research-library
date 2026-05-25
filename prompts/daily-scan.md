# Hermes Daily/Weekly Scan Prompt

Update `/home/ceden/longevity-research-library` for the topic: longevity enhancement for a 74-year-old male.

Follow these rules:

1. Read `sources/sources.yaml` and `docs/policies/selection-policy.md`.
2. Search arXiv, Semantic Scholar, and configured RSS/web sources for new high-quality items from the last 7–14 days.
3. Focus on research relevant to older adult male healthspan, function, morbidity reduction, and risk management.
4. Score candidates using the rubric. Include only items scoring >= 7.5 unless there is a clear reason to track an item as a cautionary watchlist item.
5. For each accepted item, write a concise note under `docs/updates/YYYY-MM-DD.md` with:
   - citation/title/authors/date/source URL
   - evidence type and population
   - summary
   - main finding
   - relevance to a 74-year-old male
   - limitations
   - safety/clinical cautions
   - whether it changes the evidence map
6. Update `docs/updates/index.md` with a link to the new update.
7. If the evidence materially changes a section, update the relevant topic page.
8. Never give personal medical advice. Frame interventions as research findings and clinician discussion topics.
9. Commit changes to git with a clear commit message, push `main`, then deploy the static site with `mkdocs gh-deploy --force --clean`.
10. Report a short summary of what changed.
