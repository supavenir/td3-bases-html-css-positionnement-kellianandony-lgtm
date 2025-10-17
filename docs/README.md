# TD3 — Bases HTML/CSS (positionnement)

Bloc 1 — Bases HTML/CSS • Positionnement (TD3)

Durée indicative: 4 h

🎯 Objectifs

- Approfondir le positionnement CSS (flexbox, colonnes, positionnement, images).
- Structurer des pages en blocs réutilisables (header/main/footer, sections).
- Mettre en pratique une méthodologie Git (branche, Pull Request, code review).
- Publier les livrables et garantir leur qualité (validation W3C).

✅ Pré‑requis

- Avoir accepté l’assignment « td3 » sur GitHub Classroom.
- Disposer d’une connexion internet et de droits administrateur sur le poste (pour installer si nécessaire).

📦 Organisation du repository

Travaillez en local. Commits réguliers, puis push et PR vers `main` pour la revue.

Chemins de travail pour ce TD:

- HTML: `docs/pages/td3/`
- CSS: `docs/assets/css/td3/`

Arborescence attendue (extrait):

```
docs/
├─ index.html
├─ assets/
│  └─ css/
│     ├─ main.css       # (optionnel)
│     └─ td3/
│        ├─ conseil-gestion.css
│        └─ web-arena.css
└─ pages/
   └─ td3/
      ├─ conseil-gestion.html
      ├─ about-us.html
      └─ blog.html
```

## Comment tester localement

1. Depuis la racine du workspace, lancer un serveur HTTP simple :

```bash
python3 -m http.server --directory docs 8000
```

2. Ouvrir la page d'accueil dans le navigateur hôte (ou copier-coller l'URL) :

```
http://localhost:8000
```

> Si `$BROWSER` est défini dans ton environnement tu peux aussi exécuter :

```bash
"$BROWSER" http://localhost:8000
```

## Checklist de livrables

- [ ] `docs/pages/td3/conseil-gestion.html` + `docs/assets/css/td3/conseil-gestion.css`
- [ ] `docs/pages/td3/about-us.html` + `docs/assets/css/td3/web-arena.css`
- [ ] `docs/pages/td3/blog.html` (utilise `web-arena.css`)
- [ ] `docs/index.html` avec liens fonctionnels
- [ ] Captures d'écran finales (desktop) incluses dans la PR
- [ ] Validation W3C HTML et CSS (erreurs corrigées)

## Validation W3C (rapide)

1. HTML : https://validator.w3.org/ — copier/coller l'URL (ou uploader le fichier) et corriger les erreurs.
2. CSS : https://jigsaw.w3.org/css-validator/ — copier/coller l'URL vers le fichier CSS ou uploader le fichier.

## Git / PR

- Crée une branche par exercice : `git checkout -b td3/conseil-gestion`.
- Commit clair : `git add . && git commit -m "TD3: ajout conseil-gestion (HTML + CSS)"`.
- Push : `git push origin td3/conseil-gestion`.
- Ouvre une Pull Request vers `main` et mentionne `@jcheron` pour revue.

Dans la description de la PR, joins :
- Captures d'écran
- Résumé des corrections faites
- Éventuels avertissements W3C non corrigés (et pourquoi)

---

Si tu veux, je peux maintenant :

- Lancer le serveur local dans le conteneur et te donner l'URL (je peux le lancer pour toi),
- Valider automatiquement les fichiers HTML/CSS (vérifications locales basiques),
- Préparer les commandes Git pour commit/push et une description de PR prête à coller.
# TD3 — Bases HTML/CSS (positionnement)

Bloc 1 — Bases HTML/CSS • Positionnement (TD3)

Durée indicative: 4 h

🎯 Objectifs
- Approfondir le positionnement CSS (flexbox, colonnes, positionnement, images).
- Structurer des pages en blocs réutilisables (header/main/footer, sections).
- Mettre en pratique une méthodologie Git (branche, Pull Request, code review).
- Publier les livrables et garantir leur qualité (validation W3C).

✅ Pré‑requis
- Avoir accepté l’assignment « td3 » sur GitHub Classroom.
- Disposer d’une connexion internet et de droits administrateur sur le poste (pour installer si nécessaire).

📦 Organisation du repository
Travaillez en local. Commits réguliers, puis push et PR vers `main` pour la revue.

Chemins de travail pour ce TD:

- HTML: `docs/pages/td3/`
- CSS: `docs/assets/css/td3/`

Arborescence attendue (extrait):

```
docs/
├─ index.html
├─ assets/
│  └─ css/
│     ├─ main.css       # (optionnel)
│     └─ td3/
│        ├─ conseil-gestion.css
│        └─ web-arena.css
└─ pages/
   └─ td3/
      ├─ conseil-gestion.html
      ├─ about-us.html
      └─ blog.html
```

## Comment tester localement

1. Depuis la racine du workspace, lancer un serveur HTTP simple :

```bash
python3 -m http.server --directory docs 8000
```

2. Ouvrir la page d'accueil dans le navigateur hôte :

```bash
