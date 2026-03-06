# SHŌRI — Streetwear

Boutique en ligne SHŌRI. Site statique déployé via **GitHub Pages**.

## 🚀 Déploiement sur GitHub Pages

### Étape 1 — Crée le repository

1. Va sur [github.com](https://github.com) → **New repository**
2. Nomme-le : `shori` *(ou `shori-hustle`)*
3. Mets-le en **Public**
4. **Ne coche pas** "Add README" (on l'a déjà)
5. Clique **Create repository**

### Étape 2 — Upload les fichiers

**Option A — Via l'interface GitHub (le plus simple) :**
1. Dans ton nouveau repo, clique **"uploading an existing file"**
2. Glisse-dépose `index.html` et ce `README.md`
3. Clique **Commit changes**

**Option B — Via Git (terminal) :**
```bash
git init
git add .
git commit -m "🚀 SHŌRI - Initial launch"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/shori.git
git push -u origin main
```

### Étape 3 — Active GitHub Pages

1. Dans le repo → **Settings** → **Pages** *(menu de gauche)*
2. Source : **Deploy from a branch**
3. Branch : **main** / **/ (root)**
4. Clique **Save**

⏳ Attends 1-2 minutes, puis ton site sera live sur :

```
https://TON_USERNAME.github.io/shori/
```

---

## 📁 Structure du projet

```
shori/
├── index.html      ← Toute la boutique (HTML + CSS + JS)
└── README.md       ← Ce fichier
```

> Le site est **100% single-file**. Pas de serveur, pas de build, pas de dépendances. Juste `index.html`.

---

## 🎨 Personnalisation rapide

| Ce que tu veux changer | Où chercher dans `index.html` |
|---|---|
| Couleurs | Variables CSS `:root` (ligne ~10) |
| Prix des produits | Chercher `€60` / `€55` |
| Ajouter de vraies photos | Remplacer les `.product-img-placeholder` par des `<img src="...">` |
| Lien Instagram | Chercher `shori.hustle` |
| Texte manifeste | Chercher `ÉTAT D'ESPRIT` |

---

**SHŌRI — Ambition · Hard Work · Faith**
