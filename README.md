# GitHub Pages site

Ovo je jednostavna statička stranica spremna za GitHub Pages.

## Kako objaviti (brzo)
1. Kreiraj repo na GitHubu (npr. `my-site`).
2. Kopiraj sve datoteke u repo i commit/push na `main` branch.
3. Ako koristiš gh CLI:
   ```bash
   gh repo create my-site --public --source=. --remote=origin
   git add .
   git commit -m "Initial site"
   git push -u origin main
