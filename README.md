# Weekly Bible Study

Static website. Enable GitHub Pages in Settings → Pages → Deploy from a branch → main → / (root).

## Content maintenance
Edit data.json only for routine updates. Studies use ISO dates, title, passages (array of reference/url objects), introduction (array of heading/text and optional scriptureLinks), questions (number, text, optional scriptureLinks, readingPrompts and subquestions). Subquestions are objects with label, text and optional scriptureLinks. Scripture links use text and url. Preserve this rich schema and existing fields; old source download URLs are provenance only. Preserve existing studies, deduplicate by date/passage, and sort by date. Events use ISO dates, title, description, and status (confirmed or tentative). Keep uncertain events tentative. Do not publish email headers, addresses, private contact details, or unrelated correspondence. Read attachments for actual questions; never invent missing material. Verify JSON before committing. Check deployment before reporting publication.

Custom domain: smallgroup.robinsonfamily.ca. Configure this in Pages settings and update the existing DNS record only after the new site works.
