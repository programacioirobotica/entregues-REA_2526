# Visualitzador d'Entregues – Robots en Acció

Web estàtica per publicar amb GitHub Pages.

## Publicació ràpida a GitHub Pages

1. Crea un repositori a GitHub.
2. Puja aquests fitxers a l'arrel del repositori:
   - `index.html`
   - `.nojekyll`
   - `README.md` opcional
3. Ves a **Settings → Pages**.
4. A **Build and deployment**, tria **Deploy from a branch**.
5. Selecciona la branca `main` i la carpeta `/ (root)`.
6. Desa els canvis i obre l'enllaç de GitHub Pages.

## Notes

- Aquesta web és estàtica: no necessita servidor propi per mostrar-se.
- La càrrega automàtica de dades depèn de l'URL d'Apps Script configurada dins `index.html` o dels proxies CORS inclosos.
- El fallback `/api/dades` només funciona amb el servidor local indicat al codi; a GitHub Pages no existirà perquè GitHub Pages no executa backend.
