# MSE_book_v2 – Mathematics for Software Engineering (engelsk)

LaTeX-kilden til lærebogen til MSE1. Den engelske udgave er autoritet for indholdet; den danske udgave i `C:\GitHub\MSE_book_v2_da` er oversat herfra.

## Opbygning

- `main.tex` samler bogen i fem dele: Introductory Concepts (kap. 0–3), Probability and Statistics (4–6), Linear Algebra (7–9), Differential Calculus (10–11), Additional Topics (12–15). Derefter `concepts.tex` og `appendix01.tex`.
- Kapitel NN svarer til session NN på MSE1_26 for kapitel 1–11. Kapitel 0 er forudsætninger.
- `msecolors.tex` definerer farverne, som matcher kursussiden (fx `mseViaBlue` #6CA2C6, `mseOrange` #FF8C00, `mseDarkText` #363636). `mymacro.sty`, `clrscode4e.sty` og `elegantbook.cls` ligger lokalt i repoet.
- `listings` er sat op til både Python og Java; `\inlinecode{...}` giver inline-Java.
- Forsiden er billedet `figure/cover_mse1_26.png`.

## Arbejdsgang

- `BOOK_AUDIT.md` er revisionsregistret (status `TODO`, `FIXED`, `REVIEW`). Et punkt markeres først som færdigt, når kilden er rettet, bogen bygger, og de berørte sider er tjekket i PDF'en. Opdatér registret, når du retter faglige fejl.
- `main.pdf` er tracket i git og linkes direkte fra kursussiderne (MSE1_26, MSU1_26). Et push af `main.pdf` publicerer altså bogen for de studerende. Byg og commit PDF'en, når kildeændringer skal ud.
- Rettelser her skal som regel også laves i den danske udgave. Notér det, eller spørg, hvis det ikke er en del af opgaven.

## Rod i arbejdskopien

Der ligger hjælpefiler fra `main_review` og `main_test`, `main_contourtmp*`, `build_log.txt` og `main.bbl-SAVE-ERROR` (sidstnævnte er tracket). De hører ikke til opgaverne og skal ikke committes.
