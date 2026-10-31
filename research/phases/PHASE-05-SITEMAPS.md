# Phase 05 — Sitemaps and URL Discovery

**Project:** Google Search Console — Deep Research & Study Notes  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## What is a sitemap?
A sitemap lists URLs a site wants search engines to discover. It helps discovery but does not guarantee crawling, indexing or ranking.

## Sitemap report workflow
1. Open the Sitemaps report for the correct property.
2. Submit the sitemap URL.
3. Review status, last read and discovered URL counts where available.
4. Open error details and identify the cause.
5. Correct sitemap content or server response.
6. Resubmit if appropriate and monitor later.

Common statuses include Success, Couldn't Fetch and Sitemap Had Errors. Exact UI text can evolve.

## XML structure and limits
A standard XML sitemap uses a urlset root with URL entries containing loc. The lastmod field can help when it accurately reflects a meaningful page modification. Google ignores changefreq and priority for crawling decisions.

Google's documented limits include up to 50,000 URLs or 50 MB uncompressed per sitemap. Larger sites can split sitemaps and use a sitemap index. Verify current limits in official docs before implementation.

Sitemap options include XML sitemaps, index files, and specialized image, video or news sitemaps where supported. RSS/Atom feeds can help signal recent content.

## Important distinctions
- Successful submission does not guarantee every URL is indexed.
- The report may not show every sitemap Google knows about.
- Sitemaps are a discovery signal, not a replacement for internal linking.
- Prefer canonical, indexable URLs; avoid redirects, blocked URLs and non-canonical URLs unless there is a specific reason.

## Troubleshooting
- Check the sitemap's HTTP response.
- Validate XML syntax and URL encoding.
- Use the preferred protocol and hostname.
- Check robots.txt and page-level indexing directives.
- Confirm URLs are canonical and indexable.
- Ensure the sitemap is not accidentally served as HTML or an error page.

## Official references
- [Build and submit a sitemap](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap)
- [Sitemaps report](https://support.google.com/webmasters/answer/7451001?hl=en)
- [Sitemaps API](https://developers.google.com/webmaster-tools/v1/sitemaps/list)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.