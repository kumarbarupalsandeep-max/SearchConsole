# Phase 04 — Indexing, Page Indexing and URL Inspection

**Project:** Google Search Console — Deep Research & Study Notes  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Crawl, index and serve are different
1. Crawl: Googlebot fetches a URL.
2. Index: Google processes a page and may include it in its index.
3. Serve: Google decides whether and how a page appears for a query.
A successful crawl does not guarantee indexing; indexing does not guarantee ranking.

## Page Indexing report
The report summarizes indexed and non-indexed pages and groups reasons Google detected. Possible categories include server errors, redirect errors, not found pages, robots.txt blocks, noindex directives, discovered/crawled but not indexed pages, duplicate/canonical situations and pages indexed without content. Exact labels may change.

Not every non-indexed URL is a problem: login pages, duplicates, redirects and intentionally excluded pages may be correct.

## URL Inspection
URL Inspection investigates an individual URL. Depending on view and available data, it can show indexing state, last crawl, crawl permission, page fetch, indexing permission, user-declared and Google-selected canonical, sitemap/discovery information and enhancements.

- **Indexed version:** information from Google's indexed data.
- **Live test:** tests the current accessible page, but does not guarantee indexing or reproduce every indexing decision.
- **Request indexing:** requests recrawling/indexing consideration; it is not a guarantee.

## Common reasons to investigate
- Unexpected noindex directive.
- Robots.txt blocks a page that should be crawled.
- Server errors or timeouts.
- Incorrect redirects.
- Duplicate content or canonical mismatch.
- Content is inaccessible or not useful enough for indexing.
- Google has discovered a URL but has not crawled/indexed it yet.

## Fix workflow
1. Inspect the URL.
2. Decide whether exclusion is intentional.
3. Check HTTP response, robots.txt, meta robots/X-Robots-Tag, canonical, redirects, rendered content and internal links.
4. Fix the root cause at template/site level.
5. Test the live URL.
6. Request indexing for important fixed URLs if appropriate.
7. Use report validation when available.
8. Monitor after Google recrawls.

Validation can take time and does not guarantee inclusion in search.

## API
The URL Inspection API provides selected information about Google's indexed version for a URL in a verified property. It is not equivalent to every detail in the web UI or a live test.

## Official references
- [Page Indexing report](https://support.google.com/webmasters/answer/7440203?hl=en)
- [URL Inspection](https://support.google.com/webmasters/answer/9012289?hl=en)
- [Request indexing](https://support.google.com/webmasters/answer/12482179?hl=en)
- [URL Inspection API](https://developers.google.com/webmaster-tools/v1/urlInspection.index/inspect)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Aasaan Hindi (Hinglish) mein samjho

Crawling ka matlab Googlebot page ko khol kar dekhne ki koshish karta hai. Indexing ka matlab Google page ko process karke apne search index mein rakh sakta hai. URL Inspection ek specific URL ki status details dekhne ka tool hai.

**Example:** Example: Naya page publish karne ke baad Google ko use discover aur process karne mein time lag sakta hai. Request indexing sirf request hai, guarantee nahi.

**Project:** Google Search Console — Deep Research & Study Notes  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.
