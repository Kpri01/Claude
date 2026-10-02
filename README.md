# Maison KYSTIN — site vitrine 3D

Site vitrine « Premium 3D Glass » de la Maison KYSTIN : un chardon en verre (symbole du
sceau KYSTIN) se décompose puis se recompose au scroll, sur cinq chapitres
(Accueil, La Maison, Nos cuvées, En chiffres, Contact).

- `site/index.html` — le site (a besoin d'un serveur : `cd site && python3 serve.py`)
- `site/version-monofichier.html` — tout le site dans un seul fichier, s'ouvre par double-clic
- `site/site.json` — le brief (textes, couleurs, forme) ; régénérer avec
  `cd site && python3 tools/build_site.py site.json --out ../site-build`

Modifier : textes et e-mail dans `site/index.html`, forme 3D dans
`site/assets/shapes/shape.svg`, logo du header dans `site/assets/brand/mark.svg`,
couleurs dans `SITE.palette` en tête de `site/js/app.js`.
