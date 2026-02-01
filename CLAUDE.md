# Valentine - Safa - Project Context

## Overview
Application web interactive "Will you be my Valentine?" avec un design soft aesthetic rose et blanc. Le bouton "No" fuit le curseur et le bouton "Yes" declenche une celebration avec confettis.

## Stack Technique
- **Langage** : HTML5, CSS3 (Flexbox), JavaScript Vanilla
- **Hebergement** : GitHub Pages (ou tout hebergement statique)
- **Versioning** : Git + GitHub (repo prive)

## Environnement de Deploiement

### Serveur
- **URL** : [URL]
- **IP** : [IP]
- **Port SSH** : [PORT]
- **User SSH** : [USER]
- **Chemin App** : [PATH]

### GitHub
- **Repository** : https://github.com/BarryBcr/Valentine-Safa (prive)
- **Branch principale** : main

## Deploiement Rapide (GitHub Pages)

### Option 1 : GitHub Pages (Gratuit)
```bash
# 1. Aller dans Settings > Pages sur GitHub
# 2. Source: Deploy from branch
# 3. Branch: main, folder: / (root)
# 4. URL: https://barrybcr.github.io/Valentine-Safa/
```

### Option 2 : Rendre le repo public temporairement
```bash
gh repo edit BarryBcr/Valentine-Safa --visibility public
# Activer GitHub Pages, puis remettre en prive si besoin
```

### Option 3 : Netlify Drop (instantane)
1. Aller sur https://app.netlify.com/drop
2. Glisser-deposer le dossier du projet
3. URL generee immediatement

### Option 4 : Vercel
```bash
npx vercel --prod
```

## Workflow Git
```bash
git add . && git commit -m "message" && git push origin main
```

## Regles pour les Agents IA

### Avant toute modification
1. Lire HANDOFF.md pour les bugs connus
2. Verifier CHANGELOG.md pour le contexte recent

### Apres toute modification
1. Mettre a jour CHANGELOG.md
2. Commit + push sur GitHub
3. Deployer sur le serveur
4. Documenter tout bug dans HANDOFF.md

---
*Cree le : 2026-02-01*
