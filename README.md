# ⚠️ Disclaimer

👉 Ce projet est une **pure blague** 🎭.
Il n’a aucune utilité réelle à part afficher « Bonjour » dans plein de langues avec style.
Fait uniquement pour le **fun** 😎.

# 🌍 Bonjour

Une petite **Progressive Web App (PWA)** qui affiche _« Bonjour »_ et ses équivalents dans une centaine de langues, avec une animation façon **écran de bienvenue d’un iPad neuf**.  

[![Deploy to GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-2ea44f?logo=github)](https://levalex01.github.io/bonjour/)

---

## ✨ Fonctionnalités
- 🌐 Défilement automatique de **100+ langues**
- 📱 Installable en tant que **Web App** sur iPad/iPhone/Android
- ⚡ Mode hors-ligne grâce au **Service Worker**
- 🎨 Interface simple et fluide avec effet d’animation

## 🚀 Démo
👉 [Voir la démo en ligne](https://levalex01.github.io/bonjour/)  


## 📦 Installation locale
1. Clone le dépôt :
   ```bash
   git clone https://github.com/levalex01/bonjour.git
   cd bonjour
   ```

2. Ouvre un petit serveur local (par ex. avec `python` ou `live-server`) :
   ```bash
   python -m http.server 8000
   ```
   Puis visite [http://localhost:8000](http://localhost:8000)

3. L’app fonctionne aussi sur **GitHub Pages** :  
   - Va dans **Settings → Pages**  
   - Active **GitHub Pages** sur la branche `main`  
   - Ton site sera dispo sur `https://levalex01.github.io/bonjour-multilingue/`

## 📲 Ajouter sur iPad/iPhone
1. Ouvre l’app dans **Safari**.  
2. Clique sur **Partager** → **Ajouter à l’écran d’accueil**.  
3. Lance-la comme une vraie application.

## 📁 Structure
```
├── index.html         # Page principale avec l'animation
├── style.css          # Style de base (inclus inline ou externe)
├── manifest.json      # Déclaration de la PWA
├── service-worker.js  # Cache offline
├── icon-192.png       # Icône 192x192
└── icon-512.png       # Icône 512x512
```

## 🛠️ Technologies utilisées
- **HTML5 / CSS3 / JavaScript**
- **PWA (Progressive Web App)**

---

💡 Projet simple et fun pour découvrir le fonctionnement des **Web Apps installables** et les animations multilingues.

