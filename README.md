# 🟢 Catalogue – Template GitHub

## 🎯 Objectif du projet

Catalogue est un dépôt-template permettant à chacun·e de se créer son propre média numérique à partir de notre base.

* Possibilité de personnaliser le `manifest.json` avec ses propres contenus (ex : articles, images, PDFs, etc.) ou repartir de ceux proposés.
* Le projet est conçu pour apprendre en construisant : on déploie simultanément les nouveautés et les tests (bêtas), dans une approche itérative pour faciliter l’adhésion progressive.
* Le projet s’appuie sur une approche d’éducation populaire et d’empouvoirement par le numérique 

![logo](./images/og-default.jpg)

## 📦 Contenu du projet

```text
/css         → fichiers CSS (style)
/images      → visuels à afficher
/md          → fichiers Markdown (contenus)
/pdfs        → documents PDF
/scripts     → scripts JavaScript, ex. validate.html
/thumbs      → vignettes/stubs d'aperçu
/zips        → archives compressées (“downloads”)
/index.html  → page d'accueil du catalogue dynamique
/manifest.json → configuration des contenus affichés
```

## ⚙️ Fonctionnement technique

* **Deux fichiers essentiels** :

  * `index.html` : génère la page en fonction des entrées du manifest
  * `manifest.json` : liste les contenus à inclure (titres, chemins, types…)

* **Aucune infrastructure complexe** : le template se déploie facilement sur n’importe quel hébergement simple (GitHub Page, Netlify, etc.).

* **Pas de prestation technique garantie** : mais ouverture totale aux contributions, issues ou échanges via GitHub si besoin.

## 🚀 Démo en ligne

Le catalogue est consultable en live ici :
[dl.ouaisfi.eu](https://dl.ouaisfi.eu/)

## 🛠 Installation & usage

1. Fork ou clone ce dépôt.
2. Modifie `manifest.json` pour y indiquer **tes contenus** :

   * `"title"`, `"type"`, `"path"`, etc.
3. Place tes fichiers dans les dossiers correspondants (`md/`, `pdfs/`, etc.).
4. Ouvre `index.html` dans un navigateur ou déploie sur un serveur statique.
5. Observe ton catalogue personnalisé en ligne.

## 🌱 Bonnes pratiques pédagogiques

* Travail en **version bêta** : ajoute progressivement de nouveaux modules / tests.
* Approche **itérative et évolutive** : permet aux utilisateurs de prendre en main à leur rythme, et d'améliorer le projet ensemble.

## 🤝 Contributions bienvenues

Tu veux personnaliser, ajouter des tests, proposer un nouveau format de contenu ?

1. Fork → 2. Crée une branche → 3. Modifie → 4. Ouvre une Pull Request
   On peut fusionner, discuter et améliorer ensemble.

## 📜 Licence

* **Tous usages tolérés, sauf commercial.**
* Citation de la source appréciée, mais **non obligatoire**.
* Usage libre/ libre-service : adapte, modifie, partage.

## 📧 Contact

Besoin d’aide ou envie de collaborer ?
Utilise les **Issues GitHub** du dépôt, on répond dès que possible.

---

### 🟢 Pourquoi tout ça ?

Ce README donne à ton projet une structure claire et professionnelle, tout en gardant l’esprit d’ouverture et de participation que tu souhaites promouvoir. Il montre aussi la démarche d’apprentissage collectif et progressif.

Si tu veux une version en anglais, ou ajouter des sections (ex. exemples visuels, captures d’écran, roadmap), dis-le moi je peux te le générer direct !
