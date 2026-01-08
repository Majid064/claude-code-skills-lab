# SEO Factors Checklist

## Critical Factors

| Factor | Check | Issue If |
|--------|-------|----------|
| Title tag | Present, 50-60 chars | Missing, too short (<30), too long (>60) |
| Meta description | Present, 150-160 chars | Missing, too short (<70), too long (>160) |
| H1 tag | Exactly one per page | Missing or multiple H1s |
| HTTPS | URL uses https:// | HTTP only (insecure) |
| Mobile viewport | `<meta name="viewport">` present | Missing viewport meta |

## Important Factors

| Factor | Check | Issue If |
|--------|-------|----------|
| Heading hierarchy | H1 > H2 > H3 logical order | Skipped levels (H1 to H3) |
| Image alt text | All `<img>` have alt attributes | Missing alt on images |
| Canonical URL | `<link rel="canonical">` present | Missing canonical tag |
| Language | `<html lang="...">` specified | Missing lang attribute |
| Internal links | Page has internal links | No internal navigation |

## Content Factors

| Factor | Check | Issue If |
|--------|-------|----------|
| Content length | Sufficient text content | Very thin content (<300 words) |
| Keyword in title | Primary keyword in title | Title doesn't reflect content |
| Keyword in H1 | Primary keyword in H1 | H1 doesn't match topic |
| Keyword in URL | Clean, descriptive URL | URL has random IDs/parameters |

## Technical Factors

| Factor | Check | Issue If |
|--------|-------|----------|
| Open Graph tags | og:title, og:description present | Missing OG tags (poor social sharing) |
| Twitter cards | twitter:card meta present | Missing Twitter card tags |
| Structured data | JSON-LD or microdata present | No schema markup |
| Robots meta | No blocking directives | noindex or nofollow present |

## Scoring Guide

- **9-10**: Excellent - minor optimizations only
- **7-8**: Good - a few issues to address
- **5-6**: Fair - several important fixes needed
- **3-4**: Poor - critical issues present
- **1-2**: Critical - major SEO problems

**Deduct points:**
- Critical issue: -2 points each
- Important issue: -1 point each
- Content/Technical issue: -0.5 points each
