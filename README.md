# Claude Code Skills Lab

Custom skills for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) that automate repetitive content and SEO workflows.

## Demo

https://files.catbox.moe/06eayw.mp4

## What Are Skills?

Skills are modular packages that extend Claude's capabilities with specialized knowledge and workflows. They transform Claude from a general-purpose assistant into a domain expert equipped with procedural knowledge for specific tasks.

## Skills Overview

| Skill | Manual Work Replaced | Time Saved | Quality Improvement |
|-------|---------------------|------------|---------------------|
| **blog-post** | Writing SEO-optimized articles from scratch | 2-4 hours per post | Consistent SEO structure, proper keyword placement |
| **multi-platform-seo-content** | Creating separate content for each social platform | 1-2 hours per product | Platform-specific optimization, no copy-paste errors |
| **seo-audit** | Manual page-by-page SEO checks | 30-60 min per page | Comprehensive checklist coverage, prioritized fixes |
| **skill-creator** | Learning skill syntax and structure | Hours of documentation reading | Properly formatted, validated skills |

## Skill Details

### blog-post
Generates SEO-optimized informational blog posts for kitchen niche products.

**Replaces:** Researching SEO best practices, structuring articles, writing FAQs, ensuring keyword density
**Output:** 1,200-1,500 word article in Markdown, ready to publish

### multi-platform-seo-content
Creates platform-specific content for Pinterest, Instagram, TikTok, and YouTube from a single keyword.

**Replaces:** Manually adapting content for each platform's character limits, hashtag research, alt-text writing
**Output:** Ready-to-post content for 4 platforms with optimized titles, descriptions, hashtags

### seo-audit
Analyzes any webpage for on-page SEO issues and provides actionable recommendations.

**Replaces:** Manual SEO checklist reviews, identifying missing meta tags, checking heading structure
**Output:** Scored audit report with prioritized fixes

### skill-creator
Guides creation of new Claude Code skills with proper structure and validation.

**Replaces:** Reading documentation, trial-and-error skill formatting
**Output:** Validated, packaged `.skill` files

## Usage

Invoke any skill by name in Claude Code:
```
/blog-post
/multi-platform-seo-content
/seo-audit
```

