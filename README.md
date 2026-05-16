# Projektna-naloga-vercel

## Opis
Napisal sem preprosto statično spletno stran real-phone-website z html,css in javascriptom jo dodal v github repo ki sem ga povezal z vercelom in na vercelu deployal,
kodo sem večkrat spremenil da sem testiral in commital spremembe,da sem videl če avtomatski CI/CD na vercelu deluje.

## Uporabljene tehnologije
- HTML
- CSS
- JavaScript
- GitHub
- Vercel
- Cloudflare ali Supabase

## Deploy 
Vercel Production URL:
https://real-phone-website.vercel.app/

## CI/CD
Samodejni deploy se izvede,ko narediš spremembo v kodi in želiš da se samodejno sprememba kode deploya tudi na vercelu torej z ukazi git add. in git commit in git push se morajo
spremembe samodejno shraniti v vercelu.

## Dodatna konfiguracija
Opis DNS, environment variables, Supabase ali Cloudflare nastavitev.

## Težave
Največje težave sem imel pri CI/CD,namreč 2.commit se mi pospremembah ni hotel avtomatsko deployati v vercelu kjer sem moral prekiniti povezavo z gitom in nato ponovno povezati zatem pa sem ponovno commital z ukazom z ukazom  --allow-empty -m 
