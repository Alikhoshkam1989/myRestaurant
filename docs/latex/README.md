# LaTeX-documentatie

Drie inleverbare documenten, gebaseerd op de bestaande markdownbronnen en de
opdrachtstructuur (titel, inhoudsopgave, klassendiagram, twee sequentiediagrammen,
zes keuzes, zes limitaties, API-referentie).

| Bron | PDF |
|---|---|
| `technisch-ontwerp.tex` | Technisch ontwerp |
| `verantwoordingsdocument.tex` | Verantwoordingsdocument |
| `api-documentatie.tex` | API-documentatie |

Vereist: een TeX-distributie met `pdflatex` (bijvoorbeeld MiKTeX of TeX Live)
en de pakketten in `restaurant-docs.sty` (tikz, booktabs, listings, hyperref, babel).

```powershell
cd docs\latex
pdflatex -interaction=nonstopmode technisch-ontwerp.tex
pdflatex -interaction=nonstopmode technisch-ontwerp.tex
pdflatex -interaction=nonstopmode verantwoordingsdocument.tex
pdflatex -interaction=nonstopmode verantwoordingsdocument.tex
pdflatex -interaction=nonstopmode api-documentatie.tex
pdflatex -interaction=nonstopmode api-documentatie.tex
```

De tweede run vult de inhoudsopgave. Titelpagina's vermelden versie 4.3 en
inleverdatum 8 november 2026.
