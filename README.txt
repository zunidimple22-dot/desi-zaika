# Desi Zaika — Website Setup Guide
=====================================

## Kya hai?
Pakistani desi recipes ki ELEGANT website (ivory + deep green + gold theme) —
16 full-detail recipes, alag Grilling & BBQ section, Blog (4 articles),
About, Contact aur Privacy Policy pages.
AdSense approval ke liye ready structure.

## Live kaise karein (cPanel / File Manager)
1. Is folder ki SARI files ko apne domain ke `public_html` mein upload karein.
2. `ads.txt` file root mein rakhein aur apna publisher ID likhein:
   google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f9404c445f3
3. Har page par AdSense ad code lagayein:
   - Har HTML file mein `<!-- AdSense:` wali comments dhoondein
   - Apna ad code paste karein (ca-pub-XXXX apne ID se replace karein)
   - AdSense account mein site verify kar ke "Auto ads" ON karna sab se aasan hai
4. Contact page ka email `hello@desizaika.com` apne asli email se replace karein.
5. Google Search Console mein site submit karein + sitemap banayein.

## AdSense approval tips
- Privacy Policy page pehle se hai (zaroori requirement).
- About + Contact pages hain (trust signals).
- 16 original detailed recipes = strong content (thin content reject hota hai).
- Kam az kam 2-3 hafte site live rakhein, phir AdSense ke liye apply karein.
- Apne ads par khud click NA karein — account ban ho jata hai!

## Files
- index.html ............ Home
- recipes.html ........... Sari 16 recipes ki listing
- grilling.html .......... Alag BBQ section + grilling tips
- <recipe>.html .......... 16 recipe pages (print button ke saath)
- blog.html .............. Blog listing (4 articles)
- <article>.html ......... 4 full food articles
- about.html / contact.html / privacy-policy.html
- ads.txt ................ AdSense ke liye (publisher ID dalna zaroori)
