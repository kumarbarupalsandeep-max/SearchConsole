# Phase 05 — Sitemap aur URLs Dhoondhna

**Project:** Google Search Console — Research Notes aur Study Guide  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Sitemap kya hota hai?
Sitemap ek file hai jisme website ke un URLs ki list hoti hai jinhe website owner Google jaise search engines ko dikhana chahta hai. Isse pages dhoondhne mein help milti hai, lekin crawl, indexing ya ranking ki guarantee nahi milti.

## Sitemap submit karne ke steps
1. Sahi property mein Sitemaps report kholein.
2. Sitemap ka address submit karein.
3. Status, last read aur discovered URLs ki details dekhein, agar available hon.
4. Error aaye to uski details kholein.
5. Sitemap ya server ki problem theek karein.
6. Zaroorat ho to dobara submit karke baad mein check karein.

Aam status mein Success, Couldn't Fetch ya Sitemap Had Errors jaise messages ho sakte hain. Screen par likhe exact words badal sakte hain.

## XML sitemap aur limits
Aam XML sitemap mein URL entries hoti hain. Har entry mein `loc` se URL diya jaata hai. `lastmod` tabhi use karein jab page mein waqai meaningful update hua ho. Google crawling decisions ke liye `changefreq` aur `priority` ko use nahi karta.

Google ki documented limit aam taur par ek sitemap mein 50,000 URLs ya 50 MB uncompressed data hai. Badi website sitemap ko parts mein baant sakti hai aur sitemap index use kar sakti hai. Implementation se pehle official docs mein current limit check karein.

XML sitemap ke alawa zaroorat ke hisaab se image, video aur news sitemap bhi ho sakte hain. RSS/Atom feeds naye content ki discovery mein madad kar sakti hain.

## Yaad rakhein
1. Sitemap submit hone ka matlab har URL index hona nahi.
2. Report mein Google ko pata har sitemap dikhna zaroori nahi.
3. Sitemap internal links ka replacement nahi hai.
4. Sitemap mein sahi, canonical aur index hone layak URLs rakhna behtar hai.

## Error kaise solve karein?
1. Sitemap ka server response check karein.
2. XML format aur URLs check karein.
3. Sahi domain aur HTTPS address use karein.
4. robots.txt aur noindex rules check karein.
5. Confirm karein ki URLs redirect ya galat canonical par nahi ja rahe.
6. Dekhein sitemap ke badle HTML page ya error page to nahi aa raha.

## Example
Online store ke sitemap mein product aur category pages ke URLs ho sakte hain. Aise URLs na daalein jo galat, duplicate ya index nahi hone chahiye.

## Official links
- [Sitemap banana aur submit karna](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap)
- [Sitemaps report](https://support.google.com/webmasters/answer/7451001?hl=en)
- [Sitemaps API](https://developers.google.com/webmaster-tools/v1/sitemaps/list)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.
