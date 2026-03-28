# URLs Directory

This directory contains URL references and archived links for all research sources.

## Subdirectories

- **references/** - Active URL references organized by topic
- **archived_urls/** - Archived versions of URLs (Wayback Machine, Archive.today)
- **broken_links/** - Record of URLs that are no longer accessible

## URL Management

### URL Format

Store URLs in markdown files with the following format:

```markdown
## [Source Title]

**URL:** https://example.com/article
**Archive URL:** https://archive.today/xyz123
**Access Date:** YYYY-MM-DD
**Source Type:** [news_article/academic_paper/etc.]
**Relevance:** [Brief description of relevance]
```

### Archiving Priority

**Critical URLs (Must Archive):**
- Sources supporting key findings
- Official documents and reports
- Evidence that may be removed
- Time-sensitive content

**Standard URLs (Should Archive):**
- News articles
- Blog posts
- Social media content
- Technical documentation

### Archive Services

- **Internet Archive:** https://web.archive.org/
- **Archive.today:** https://archive.today/
- **Perma.cc:** https://perma.cc/

## Broken Link Documentation

When a URL becomes inaccessible:
1. Move to broken_links/ directory
2. Document original URL and last known working date
3. Include archive URL if available
4. Note reason for inaccessibility
