# 🎯 Peta Pikado Invenda Liga

Statični sajt za 5. sezonu Pikado Invenda Lige (2026–2027) — tabela, igrači, mečevi, kalendar, plej-of, head-to-head statistika, arhiva kola i galerija. Hostovan preko GitHub Pages.

## Kako radi

- `index.html` — ceo sajt, jedan fajl (HTML + CSS + JS)
- `data/liga.json` — svi podaci sezone (igrači, mečevi, arhiva, plej-of, raspored)
- `images/` — logo, pozadina, slike igrača, galerija

Podaci se javno čitaju direktno sa GitHub-a (bez tokena). Admin panel (tab 🔐 Admin) piše izmene nazad u `data/liga.json` preko GitHub API-ja — potreban je GitHub token sa pristupom ovom repou, unosi se pri svakom loginu i ne čuva se trajno.

## Novo u 5. sezoni

- Unos rezultata je vezan direktno za mečeve kola (umesto nezavisnog unosa po igraču) — iz toga se automatski gradi head-to-head istorija.
- Tab **Plej-of** — bracket za Top 4 na kraju regularnog dela.
- Kalendar celog rasporeda (15 kola) u tabu **Mečevi**, računat iz datuma početka sezone i intervala između kola (podešava se u Admin panelu).
