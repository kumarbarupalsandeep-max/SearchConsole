# Phase 06 — Crawl Stats, robots.txt and Crawl Management

**Project:** Google Search Console — Deep Research & Study Notes  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Crawl Stats report
Where available, Crawl Stats summarizes Googlebot activity such as total crawl requests, download size, average response time, host status, response codes, file types, crawl purpose and Googlebot type.

## What to monitor
- **Response codes:** successful responses, redirects, 4xx, 5xx, throttling and fetch failures.
- **Host status:** DNS resolution, server connectivity and robots.txt fetching.
- **File types:** HTML, images, JavaScript, CSS, PDFs and other resources.
- **Crawl purpose:** discovery of new URLs versus refresh of known URLs.
- **Googlebot type:** crawlers and agents may have different purposes.

## robots.txt report
The report can help inspect Google's fetch status, current/previous file versions and issues. Check the live robots.txt carefully before changing rules.

Robots.txt controls crawling; it is not a reliable way to keep a URL out of the index. If the goal is to prevent indexing, use appropriate indexing controls and understand that Google must be able to crawl a page to see page-level directives.

## Crawl budget
Crawl budget is mainly a concern for very large or frequently updated sites. It depends on crawl capacity and crawl demand. Most small and medium sites do not need special crawl-budget optimization unless there is evidence of a crawling constraint.

## Troubleshooting workflow
1. Compare crawl requests and response times over time.
2. Check increased 5xx, 429, DNS or timeout errors.
3. Review server logs where available.
4. Confirm robots.txt is accessible and does not block important sections/assets unintentionally.
5. Fix server capacity or response issues before attempting to increase crawling.
6. Keep important pages discoverable through internal links and accurate sitemaps.
7. Avoid changing crawl-rate controls without understanding the cause.

## Cautions
Search Console crawl data and server logs can differ because of timing, scope, bot identification and reporting methodology. Crawl Stats is not a complete substitute for server logs.

## Official references
- [Crawl Stats report](https://support.google.com/webmasters/answer/9679690)
- [robots.txt report](https://support.google.com/webmasters/answer/6062598)
- [Crawl budget guidance](https://developers.google.com/crawling/docs/crawl-budget)
- [Reduce crawl rate](https://developers.google.com/search/docs/crawling-indexing/reduce-crawl-rate)
- [Troubleshoot crawling errors](https://developers.google.com/search/docs/crawling-indexing/troubleshoot-crawling-errors)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.