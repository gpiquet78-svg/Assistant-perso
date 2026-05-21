# 🤖 Mon Assistant Personnel

Assistant IA personnel pour gérer ton planning Google Calendar, tes menus de la semaine et ta liste de courses.

## ✨ Fonctionnalités

- 💬 **Assistant vocal & textuel** — donne des consignes en langage naturel
- 📅 **Google Calendar** — consulte et ajoute des rendez-vous
- 🍽️ **Menus semaine** — génération automatique de menus sains et variés
- 🛒 **Liste de courses** — générée à partir des menus, avec ouverture du Drive
- 📱 **PWA installable** — fonctionne comme une vraie app sur mobile

---

## 🚀 Installation sur GitHub Pages

### Étape 1 — Créer le dépôt GitHub

1. Connecte-toi sur [github.com](https://github.com)
2. Clique sur **"New repository"** (bouton vert en haut à droite)
3. Nom du dépôt : `assistant-personnel`
4. Coche **"Public"**
5. Clique **"Create repository"**

### Étape 2 — Uploader les fichiers

1. Dans ton dépôt, clique **"uploading an existing file"**
2. Glisse-dépose les fichiers : `index.html` et `manifest.json`
3. Clique **"Commit changes"**

### Étape 3 — Activer GitHub Pages

1. Dans ton dépôt, clique sur **"Settings"** (onglet en haut)
2. Menu gauche → **"Pages"**
3. Sous "Branch" → sélectionne **"main"** → **"/ (root)"**
4. Clique **"Save"**
5. Attends 2-3 minutes
6. Ton app sera disponible sur : `https://gpiquet78-svg.github.io/assistant-personnel`

### Étape 4 — Configurer Google OAuth

1. Retourne sur [console.cloud.google.com](https://console.cloud.google.com)
2. Va dans **"Identifiants"**
3. Clique sur ton Client ID OAuth
4. Dans **"Origines JavaScript autorisées"**, ajoute :
   ```
   https://gpiquet78-svg.github.io
   ```
5. Clique **"Enregistrer"**

### Étape 5 — Première utilisation

1. Ouvre `https://gpiquet78-svg.github.io/assistant-personnel`
2. Entre ta clé Gemini et ton Client ID Google
3. Configure tes préférences (cuisines, budget, supermarché)
4. Clique **"Démarrer mon assistant"**

### Étape 6 — Installer sur ton téléphone (optionnel)

**Android (Chrome) :**
- Ouvre l'app dans Chrome
- Menu ⋮ → "Ajouter à l'écran d'accueil"

**iPhone (Safari) :**
- Ouvre l'app dans Safari
- Bouton partage □↑ → "Sur l'écran d'accueil"

---

## 🎤 Comment utiliser l'assistant

| Consigne | Action |
|---|---|
| "Ajoute un RDV chez le dentiste vendredi 15h" | Crée l'événement dans Google Calendar |
| "Quels sont mes prochains rendez-vous ?" | Liste les événements à venir |
| "Génère les menus de la semaine" | Crée 7 jours de menus |
| "Fais ma liste de courses" | Génère la liste depuis les menus |
| "Ouvre le Drive Leclerc" | Ouvre le Drive dans le navigateur |

---

## 🔑 Sécurité

- Tes clés API sont stockées **uniquement sur ton appareil** (localStorage)
- Elles ne transitent jamais par un serveur externe
- La communication se fait directement avec Google et Gemini

---

## 🆘 Support

En cas de problème, demande de l'aide à Claude sur claude.ai !
