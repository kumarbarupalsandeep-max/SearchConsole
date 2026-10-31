# Phase 04 — Indexing aur URL Inspection

**Project:** Google Search Console — Research Notes aur Study Guide  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Crawling, Indexing aur Search Results ka farq
1. **Crawling:** Googlebot URL khol kar page ko dekhne ki koshish karta hai.
2. **Indexing:** Google page ko process karke apne search database mein rakh sakta hai.
3. **Search mein dikhana:** Google tay karta hai ki page kisi search par dikhana hai ya nahi.

Page crawl hone se indexing pakki nahi hoti, aur indexing se ranking pakki nahi hoti.

## Page Indexing report
Yeh report indexed aur index na hue pages ka summary deti hai aur Google ko mili wajahen dikhati hai. Wajahen server error, redirect error, page na milna, robots.txt block, noindex rule, duplicate page, ya page milne ke baad index na hona ho sakti hain. Report ke exact labels badal sakte hain.

Har non-indexed URL problem nahi hota. Login pages, duplicate pages aur jaan-boojhkar exclude kiye gaye pages theek bhi ho sakte hain.

## URL Inspection kya hai?
Is tool se ek khaas URL ki jaankari check kar sakte hain. Available details mein index status, last crawl, Google page khol sakta hai ya nahi, canonical URL, sitemap/discovery aur kuch enhancements shamil ho sakte hain.

- **Indexed version:** Google ke paas pehle se maujood page ki jaankari.
- **Live test:** Abhi page ko check karta hai; indexing ki guarantee nahi.
- **Request indexing:** Google se page dobara dekhne ki request; guarantee nahi.

## Problem kaise check karein?
1. URL Inspection mein URL daalein.
2. Decide karein ki page ka index na hona jaan-boojhkar hai ya nahi.
3. Server response, robots.txt, noindex, canonical, redirects, page content aur internal links check karein.
4. Root cause ko theek karein.
5. Live URL test karein.
6. Zaroori fixed pages ke liye indexing request bhejein.
7. Report mein validation option ho to use karein.
8. Google ke dobara crawl karne ke baad status check karein.

## Example
Aapne naya page publish kiya. Google ko use dhoondhne aur process karne mein time lag sakta hai. Indexing request bhejna sirf request hai, turant search result mein aane ka wada nahi.

## API ki baat
URL Inspection API verified property ke ek URL ke indexed version ki kuch details deti hai. Yeh website UI ke har detail ya live test ka poora badal nahi hai.

## Official links
- [Page Indexing report](https://support.google.com/webmasters/answer/7440203?hl=en)
- [URL Inspection](https://support.google.com/webmasters/answer/9012289?hl=en)
- [Request indexing](https://support.google.com/webmasters/answer/12482179?hl=en)
- [URL Inspection API](https://developers.google.com/webmaster-tools/v1/urlInspection.index/inspect)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.
