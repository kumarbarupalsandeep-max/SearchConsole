# Phase 10 — Core Web Vitals, Page Experience and HTTPS

**Project:** Google Search Console — Deep Research & Study Notes  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Core Web Vitals
| Metric | What it measures | Good threshold |
|---|---|---|
| LCP | Loading performance of main visible content | 2.5 seconds or less |
| INP | Responsiveness to user interactions | 200 milliseconds or less |
| CLS | Unexpected layout movement | 0.1 or less |

Google evaluates these metrics using the 75th percentile of page visits. Consult current official guidance for exact thresholds and measurement details.

## Report behavior
Core Web Vitals reports separate mobile and desktop field data where available. Reports group URLs with similar patterns. Data may be unavailable for URLs/properties without sufficient real-user data; this does not automatically mean the site is slow or broken.

## Common optimization approaches
### LCP
- Optimize main images and critical resources.
- Reduce slow server response.
- Review render-blocking CSS and JavaScript.
- Prioritize important above-the-fold content appropriately.

### INP
- Reduce long JavaScript tasks.
- Optimize event handlers.
- Reduce unnecessary component rerenders and expensive calculations.
- Review third-party scripts and interaction work.

### CLS
- Reserve image/video dimensions and space for ads/embeds.
- Avoid inserting content above existing content unexpectedly.
- Review font loading and dynamic UI.
- Test different screen sizes.

These are possible remedies, not a diagnosis of any particular website.

## Field data vs lab data
- **Field data** comes from real-user experiences and is used in Search Console's Core Web Vitals report where available.
- **Lab data** comes from controlled tests such as Lighthouse and is useful for debugging.
Results can differ because of device, network, page state and measurement conditions.

## HTTPS report
The HTTPS report can show indexed HTTPS/HTTP URL information and detected HTTPS-related issues for eligible properties. Possible problems include invalid certificates, HTTP canonical references, HTTP sitemap URLs, redirect problems, crawl blocks or URLs not yet evaluated. Check current report documentation for the exact issue list.

## HTTPS audit checklist
1. Verify certificate validity and hostname coverage.
2. Check HTTP-to-HTTPS redirects.
3. Ensure canonical tags use the preferred HTTPS URL.
4. Update sitemaps and internal links to preferred URLs.
5. Review robots.txt and indexing directives.
6. Test key pages and assets.
7. Monitor Search Console after recrawling.

## Page experience
Page experience is broader than speed alone. Consider secure delivery, responsive layout, readable content, stable layout, useful navigation and non-intrusive presentation. A retired report/tool does not mean the underlying user-experience principle is irrelevant.

## Useful tools
- [PageSpeed Insights](https://pagespeed.web.dev/)
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- [Core Web Vitals guide](https://web.dev/articles/vitals)

## Ranking caveat
Good Core Web Vitals support user experience but do not guarantee high search rankings. Content relevance and many other systems matter.

## Official references
- [Core Web Vitals report](https://support.google.com/webmasters/answer/9205520?hl=en)
- [Core Web Vitals documentation](https://developers.google.com/search/docs/appearance/core-web-vitals)
- [Page experience guidance](https://developers.google.com/search/docs/appearance/page-experience)
- [HTTPS report](https://support.google.com/webmasters/answer/11396518?hl=en)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.