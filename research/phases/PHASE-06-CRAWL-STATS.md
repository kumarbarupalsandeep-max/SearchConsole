# Phase 06 — Crawl Stats, robots.txt aur Googlebot

**Project:** Google Search Console — Research Notes aur Study Guide  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Crawl Stats kya batata hai?
Jahan yeh report available ho, wahan isse pata chal sakta hai ki Googlebot website par kitni requests kar raha hai, kitna data download ho raha hai, server ka response kitna time leta hai aur kis tarah ke responses mil rahe hain.

## Kya check karein?
1. **Response codes:** Page sahi khula, redirect hua, page nahi mila ya server error aaya.
2. **Host status:** Domain, server connection aur robots.txt fetch karne mein dikkat to nahi.
3. **File types:** HTML, images, JavaScript, CSS, PDF jaise resources.
4. **Crawl purpose:** Google naya URL dhoondh raha hai ya purane URL ko dobara check kar raha hai.
5. **Googlebot type:** Google ke alag crawlers ke alag kaam ho sakte hain.

## robots.txt kya hai?
robots.txt ek file hai jo crawlers ko batati hai ki website ke kaunse paths crawl karne ki permission hai ya nahi. Rules badalne se pehle current file ko dhyan se check karein.

**Important:** robots.txt crawl ko control karta hai; URL ko Google ke index se hatane ka pakka tareeka nahi hai. Page par noindex rule dekhne ke liye Google ko page crawl kar paana zaroori ho sakta hai.

## Crawl budget kya hota hai?
Yeh is baat se juda hai ki Google kisi website ko kitna crawl kar sakta hai aur kitna crawl karna chahta hai. Bahut badi ya baar-baar update hone wali websites ke liye yeh zyada relevant hota hai. Aam chhoti aur medium websites ko bina evidence ke special crawl-budget changes karne ki zaroorat nahi hoti.

## Problem check karne ke steps
1. Crawl requests aur response time ka trend compare karein.
2. 5xx, 429, DNS ya timeout errors badhe hain ya nahi dekhein.
3. Available ho to server logs check karein.
4. Confirm karein ki robots.txt sahi khul rahi hai aur important pages ko galti se block nahi kar rahi.
5. Crawl badhane ki koshish se pehle server ki problem fix karein.
6. Important pages ko internal links aur sahi sitemap se discoverable rakhein.
7. Bina wajah samjhe crawl-rate settings na badlein.

## Example
Agar server baar-baar 5xx error de, to Googlebot page ko sahi se load nahi kar payega. Hosting/server logs check karke error ki asal wajah theek karein.

## Zaroori baat
Search Console ke crawl data aur server logs mein farq ho sakta hai. Crawl Stats server logs ka poora replacement nahi hai.

## Official links
- [Crawl Stats report](https://support.google.com/webmasters/answer/9679690)
- [robots.txt report](https://support.google.com/webmasters/answer/6062598)
- [Crawl budget guide](https://developers.google.com/crawling/docs/crawl-budget)
- [Crawl rate kam karna](https://developers.google.com/search/docs/crawling-indexing/reduce-crawl-rate)
- [Crawling errors solve karna](https://developers.google.com/search/docs/crawling-indexing/troubleshoot-crawling-errors)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.
