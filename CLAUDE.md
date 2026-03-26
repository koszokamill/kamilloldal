# Kamill Kószó — Személyes Weboldal

## Projekt
Személyes branding weboldal Kószó Kamill számára. Bemutatkozás, portfolió, hírlevél-feliratkozás. Később: szolgáltatások értékesítése.

## Repo
- **GitHub:** github.com/koszokamill/kamilloldal (privát)
- **Branch:** main
- **Hosting:** Vercel (beállítás alatt)

## Technológia
- Egyetlen `index.html` fájl (HTML + CSS + minimális JS)
- Google Fonts: Instrument Serif + Source Serif 4 + DM Sans
- Nincs build step, nincs framework, nincs Tailwind
- Vercel deploy: zero config, sima static site

## Design rendszer — Személyes brand (NEM AI Budapest brand!)
- **Layout:** Single-column editorial, Medium.com-inspiráció, hero-ban 2 oszlop (szöveg + fotó)
- **Háttér:** #FAFAF9 (meleg fehér)
- **Szöveg:** #18181B (ink), #3F3F46 (700), #71717A (500), #A1A1AA (400)
- **Akcentus:** #78350F (mély amber/barna, editorial karakter)
- **Címsor font:** Instrument Serif (modern editorial, gyönyörű italic)
- **Body font:** Source Serif 4 (olvasásra tervezett, Medium-érzet)
- **UI font:** DM Sans (labelek, gombok, nav)
- **Érzet:** Medium.com meets Craig Mod. Tipográfia-vezérelt, lélegző, irodalmi minimalista.
- **Reszponzív:** Mobile-first, max 660px szövegtörzs, max 1080px hero
- **Jellegzetesség:** Italic első betű az Instrument Serif címsorokban

## Szekciók
1. **Nav** — sticky, blur háttér, "Feliratkozom" pill gomb
2. **Hero** — headline + intro + hírlevél form + social linkek | fotó (offset-border frame)
3. **Rólam** — editorial szöveg, pull quote, timeline (állomások)
4. **Amit csinálok** — 4 tétel vonalakkal elválasztva (nem kártyák)
5. **Megjelenések** — proof strip (egy sor, pontokkal)
6. **Hírlevél** — ismételt feliratkozás, centered
7. **Footer** — social linkek + copyright

## Brand kontextus
- AI Budapest közösség alapítója (1000+ tag)
- 1337 Partners co-founder (AI stratégia, Financial Services)
- Korábbi: Meet Perspectives (service design, 8 év, 50+ cég)
- MBH Bank GenAI innováció, Qorus nemzetközi díj
- Service Design Day 2026 speaker
- Portfolio.hu konferencia előadó
- Hangnem: Substack-es — okos, informális, gondolatébresztő

## Fájlok
- `index.html` — az oldal (minden benne: HTML + CSS + JS)
- `assets/kamill.jpg` — speaker fotó (Service Design Day, 600x600)
- `CLAUDE.md` — ez a fájl
- `.gitignore` — variant fájlok és node_modules kizárva

## Dev tooling
- **Agentation** (npm, dev only) — vizuális annotációs tool, NEM commitolva az index.html-be
- Használathoz: importmap + esm.sh CDN, `http://localhost:3333`-on futtatva
- Élesben nincs benne, csak lokális fejlesztéshez

## Későbbi bővítések
- Domain regisztráció és Vercel-re kötés
- Hírlevél backend (Supabase vagy email szolgáltató)
- Szolgáltatások szekció (fizetős ajánlatok)
- SEO + Open Graph meta tagek
- Analytics (Plausible)
- Saját hírlevél brand és tartalom
