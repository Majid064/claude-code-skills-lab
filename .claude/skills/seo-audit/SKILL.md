---
name: seo-audit
description: |
  Perform a quick SEO audit of any website by analyzing key on-page SEO factors.
  Use when the user asks to: audit a website's SEO, check SEO issues, analyze
  on-page SEO, review a site for SEO problems, or get SEO recommendations for a URL.
  Triggers: "SEO audit", "check SEO", "analyze SEO", "SEO review", "SEO issues".
---

# SEO Audit Skill

Perform quick on-page SEO audits and provide actionable recommendations.

## Workflow

1. **Fetch the page** using WebFetch with the target URL
2. **Analyze SEO factors** from the checklist in [references/seo-checklist.md](references/seo-checklist.md)
3. **Report findings** using the output format below

## Output Format

```markdown
## SEO Audit: [URL]

### Score: [X/10]

### Critical Issues
- [Issue]: [Brief explanation + fix]

### Warnings
- [Issue]: [Brief explanation + fix]

### Passed Checks
- [Factor]: OK

### Top 3 Recommendations
1. [Most impactful fix]
2. [Second priority]
3. [Third priority]
```

## Guidelines

- Focus on **actionable** issues only
- Prioritize by SEO impact (critical > warnings > minor)
- Keep explanations concise (one line per issue)
- If page fails to load, report the error and suggest checking URL/accessibility
