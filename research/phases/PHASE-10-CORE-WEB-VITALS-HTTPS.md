# Phase 10 — Website Speed, User Experience aur HTTPS

**Project:** Google Search Console — Research Notes aur Study Guide  
**Owner / Content Creator:** Sandeep Barupal  
**Copyright:** © 2026 Sandeep Barupal. All rights reserved, except as stated below.

## Core Web Vitals kya hain?
Core Web Vitals teen measures hain jo batate hain ki website ka main content kitni jaldi dikhta hai, user ke action par kitni jaldi response milta hai aur page ka layout kitna stable rehta hai.

| Short name | Kya measure karta hai? | Achha result |
|---|---|---|
| LCP | Main content dikhne ka time | 2.5 seconds ya kam |
| INP | Click/tap jaise action ka response | 200 milliseconds ya kam |
| CLS | Page par cheezon ka achanak hilna | 0.1 ya kam |

Google in metrics ko real-user visits ke 75th percentile se evaluate karta hai. Exact measurement samajhne ke liye official guide check karein.

## Report ka data
Report mein mobile aur desktop ke real-user data alag dikh sakte hain aur milte-julte URLs ko group kiya ja sakta hai. Kisi URL ke liye data na milne ka matlab apne aap yeh nahi ki website slow ya broken hai.

## Speed sudharne ke aam tareeke
### LCP — Main content jaldi dikhana
1. Main images aur zaroori resources optimize karein.
2. Server response slow ho to use fix karein.
3. Page ko dikhne se rokne wale CSS aur JavaScript ko check karein.
4. Screen ke pehle dikhne wale important content ko priority dein.

### INP — Click/tap par jaldi response
1. Bahut der chalne wale JavaScript tasks kam karein.
2. Click handlers ko behtar banayein.
3. Be-wajah components ko dobara render karna aur heavy calculations kam karein.
4. Third-party scripts check karein.

### CLS — Page ka layout stable rakhna
1. Images, videos aur ads ke liye pehle se jagah reserve karein.
2. Naya content achanak existing content ke upar na daalein.
3. Fonts aur dynamic UI check karein.
4. Alag screen sizes par test karein.

Yeh general suggestions hain; kisi specific website ki diagnosis nahi.

## Real-user data aur lab test ka farq
- **Field data:** Asli users ke device aur network par mile experience ka data.
- **Lab data:** Lighthouse jaise tool se controlled test ka result.

Dono ke results alag ho sakte hain kyunki device, network aur test ki conditions alag hoti hain.

## HTTPS kya hai?
HTTPS browser aur website ke beech data ko secure/encrypt karne mein madad karta hai. HTTPS report eligible websites par HTTP/HTTPS URLs aur kuch related problems dikhati hai.

## HTTPS check-list
1. Certificate valid hai aur sahi domain cover karta hai.
2. HTTP se HTTPS par redirects sahi hain.
3. Canonical tags preferred HTTPS URL use karte hain.
4. Sitemap aur internal links mein preferred URL hai.
5. robots.txt aur indexing rules sahi hain.
6. Important pages aur resources test karein.
7. Google ke dobara crawl karne ke baad report check karein.

## Example
Agar page khulne ke baad button par click karne par response late aata hai, to interaction performance kharab ho sakti hai. HTTPS use karna zaroori hai, lekin sirf HTTPS ya achhe Core Web Vitals se high ranking ki guarantee nahi milti.

## Useful tools
- [PageSpeed Insights](https://pagespeed.web.dev/)
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- [Core Web Vitals guide](https://web.dev/articles/vitals)

## Official links
- [Core Web Vitals report](https://support.google.com/webmasters/answer/9205520?hl=en)
- [Core Web Vitals documentation](https://developers.google.com/search/docs/appearance/core-web-vitals)
- [Page experience guide](https://developers.google.com/search/docs/appearance/page-experience)
- [HTTPS report](https://support.google.com/webmasters/answer/11396518?hl=en)

## Copyright
© 2026 Sandeep Barupal. All rights reserved, except as stated below.
