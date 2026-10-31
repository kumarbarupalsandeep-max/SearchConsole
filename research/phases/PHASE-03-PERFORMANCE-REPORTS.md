# Phase 03 — Performance Reports

**Project:** Google Search Console — Deep Research & Study Notes  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Main reports
- **Search Results:** performance for supported Google Search types.
- **Discover:** Discover traffic when the site meets Google's report availability conditions.
- **Google News:** performance associated with Google News surfaces covered by this report.
The News search type inside Search Results is not the same as the separate Google News report.

## Metrics
| Metric | Meaning |
|---|---|
| Clicks | Clicks from the supported Google surface |
| Impressions | Times a result was shown under report counting rules |
| CTR | Clicks divided by impressions, multiplied by 100 |
| Average position | Aggregate position metric under Google's methodology |

## Dimensions and controls
Depending on report type, dimensions may include Queries, Pages, Countries, Devices, Search Appearance and Dates. Controls can include date range, comparison, search type, query/page filters and export. Availability varies by report.

## Analysis workflow
1. Choose a suitable date range.
2. Review clicks, impressions, CTR and average position where available.
3. Compare periods only when meaningfully comparable.
4. Review queries for search intent and content opportunities.
5. Review pages gaining or losing traffic.
6. Segment by country, device, search appearance or search type where relevant.
7. Export data for deeper analysis if useful.
8. Compare trends with deployments, seasonality, indexing changes and search demand.

## Interpretation cautions
- Anonymized queries may be omitted for privacy.
- Charts and tables can differ because of aggregation and data limits.
- Data can be delayed or preliminary.
- Average position is not a fixed rank for every user.
- A traffic change does not prove a single cause.
- Discover data is only available when Google has sufficient eligible data.

## API note
Search Analytics API supports performance queries but has aggregation behavior, dimensions and row limits. Do not assume it returns every record without limits.

## Official references
- [Search Results report](https://support.google.com/webmasters/answer/7576553?hl=en)
- [Discover report](https://support.google.com/webmasters/answer/9216516?hl=en)
- [Google News report](https://support.google.com/webmasters/answer/10083653?hl=en)
- [Search Analytics API](https://developers.google.com/webmaster-tools/v1/searchanalytics/query)
- [Data limits](https://developers.google.com/webmaster-tools/v1/how-tos/all-your-data)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.