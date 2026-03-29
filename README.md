# ♟ Chess Coach — Stockfish pour Chess.com

Un script qui analyse tes parties sur **chess.com** en temps réel grâce à Stockfish, affiche les meilleurs coups avec des flèches, et peut jouer automatiquement à ta place (mode auto-play).

---

## 📋 Ce dont tu as besoin

- **Un navigateur** : Brave, Chrome ou Firefox 
- **Tampermonkey** : une extension navigateur 
- **Python 3.7+** : un langage de programmation 
- **Stockfish** : le moteur d'échecs 
- **Ce script** : les fichiers de ce repo 
---

## 🪜 Installation étape par étape

### Étape 1 — Installer Tampermonkey

Tampermonkey est une extension qui permet d'exécuter des scripts dans ton navigateur.

1. Ouvre ton navigateur
2. Va sur le store de ton navigateur :
   - **Chrome / Brave** → [chrome.google.com/webstore](https://chrome.google.com/webstore) → recherche "Tampermonkey"
   - **Firefox** → [addons.mozilla.org](https://addons.mozilla.org) → recherche "Tampermonkey"
3. Clique **"Ajouter"** ou **"Installer"**
4. Une icône Tampermonkey apparaît en haut à droite de ton navigateur ✅

---

### Étape 2 — Installer Python

Python est nécessaire pour faire tourner le serveur local qui communique avec Stockfish.

1. Va sur **[python.org/downloads](https://www.python.org/downloads/)**
2. Clique sur le gros bouton **"Download Python"**
3. Lance l'installateur téléchargé
4. ⚠️ **IMPORTANT** : coche la case **"Add Python to PATH"** avant de cliquer Install
5. Clique **"Install Now"**
6. Une fois terminé, Python est installé ✅

---

### Étape 3 — Installer Stockfish

Stockfish est le moteur d'échecs qui calcule les meilleurs coups.

1. Va sur **[stockfishchess.org/download](https://stockfishchess.org/download/)**
2. Clique sur **Windows**
3. Télécharge le fichier `.zip`
4. Extrais le `.zip` — tu obtiens un fichier `.exe`
5. Copie ce fichier `.exe` dans le dossier `chess-server` (le dossier de ce projet) ✅

---

### Étape 4 — Télécharger ce projet

1. Sur cette page GitHub, clique sur le bouton vert **"Code"**
2. Clique **"Download ZIP"**
3. Extrais le ZIP où tu veux (ex : sur le Bureau)
4. Tu obtiens un dossier `chess-server` avec tous les fichiers ✅

---

### Étape 5 — Installer le script Tampermonkey

1. Clique sur l'icône **Tampermonkey** en haut à droite de ton navigateur
2. Clique **"Tableau de bord"**
3. Clique l'onglet **"Utilitaires"**
4. Dans la section **"Importer depuis un fichier"**, clique **"Choisir un fichier"**
5. Sélectionne le fichier **`chess-coach-v9_5_user.js`** du dossier téléchargé
6. Clique **"Installer"** ✅

---

### Étape 6 — Lancer le serveur local

Le serveur local fait le lien entre ton navigateur et Stockfish.

1. Ouvre le dossier `chess-server`
2. Double-clique sur **`lancer.sh`**

   > Si ça ne marche pas, ouvre PowerShell dans le dossier (clique sur la barre d'adresse de l'Explorateur Windows, tape `powershell`, appuie sur Entrée) et tape :
   > ```
   > python server.py
   > ```

3. Une fenêtre noire s'ouvre avec le message `♟ Serveur lancé → http://localhost:8765` ✅
4. **Laisse cette fenêtre ouverte** pendant toute ta session de jeu

---

## 🎮 Utilisation

1. Lance le serveur (Étape 6)
2. Va sur **[chess.com](https://www.chess.com)** et commence une partie 
3. Le panneau **Chess Coach** apparaît en bas à droite de l'écran
4. Clique **"▶ Coach ON"** pour activer l'analyse
5. Une flèche verte indique le meilleur coup à jouer
6. (Optionnel) Clique **"🤖 Auto-play ON"** pour que le script joue automatiquement

---

## ⚙️ Options du panneau

**Coach ON/OFF** — Active ou désactive l'analyse en temps réel.

**Auto-play ON/OFF** — Le script joue les coups automatiquement à ta place.

**Niveau Stockfish** — De 1 (analyse rapide et superficielle) à 20 (niveau grand maître, calcul long).

**Barre d'évaluation** — Affiche qui est en â™Ÿ Chess Coach â€” Stockfish pour Chess.com

Un script qui analyse vos parties sur **chess.com** en temps rÃ©el grÃ¢ce Ã  Stockfish, affiche les meilleurs coups avec des flÃ¨ches, et peut jouer automatiquement Ã  votre place (mode auto-play).

---

## ðŸ“‹ Ce dont vous avez besoin

- **Un navigateur** : Brave, Chrome ou Firefox (gratuit)
- **Tampermonkey** : une extension navigateur (gratuit)
- **Python 3.7+** : un langage de programmation (gratuit)
- **Stockfish** : le moteur d'Ã©checs (gratuit)
- **Ce script** : les fichiers de ce repo (gratuit)

---

## ðŸªœ Installation Ã©tape par Ã©tape

### Ã‰tape 1 â€” Installer Tampermonkey

Tampermonkey est une extension qui permet d'exÃ©cuter des scripts dans votre navigateur.

1. Ouvrez votre navigateur
2. Allez sur le store de votre navigateur :
   - **Chrome / Brave** â†’ [chrome.google.com/webstore](https://chrome.google.com/webstore) â†’ recherchez "Tampermonkey"
   - **Firefox** â†’ [addons.mozilla.org](https://addons.mozilla.org) â†’ recherchez "Tampermonkey"
3. Cliquez **"Ajouter"** ou **"Installer"**
4. Une icÃ´ne Tampermonkey apparaÃ®t en haut Ã  droite de votre navigateur âœ…

---

### Ã‰tape 2 â€” Installer Python

Python est nÃ©cessaire pour faire tourner le serveur local qui communique avec Stockfish.

1. Allez sur **[python.org/downloads](https://www.python.org/downloads/)**
2. Cliquez sur le gros bouton **"Download Python"**
3. Lancez l'installateur tÃ©lÃ©chargÃ©
4. âš ï¸ **IMPORTANT** : cochez la case **"Add Python to PATH"** avant de cliquer Install
5. Cliquez **"Install Now"**
6. Une fois terminÃ©, Python est installÃ© âœ…

---

### Ã‰tape 3 â€” Installer Stockfish

Stockfish est le moteur d'Ã©checs qui calcule les meilleurs coups.

1. Allez sur **[stockfishchess.org/download](https://stockfishchess.org/download/)**
2. Cliquez sur **Windows**
3. TÃ©lÃ©chargez le fichier `.zip`
4. Extrayez le `.zip` â€” vous obtenez un fichier `.exe`
5. Copiez ce fichier `.exe` dans le dossier `chess-server` (le dossier de ce projet) âœ…

---

### Ã‰tape 4 â€” TÃ©lÃ©charger ce projet

1. Sur cette page GitHub, cliquez sur le bouton vert **"Code"**
2. Cliquez **"Download ZIP"**
3. Extrayez le ZIP oÃ¹ vous voulez (ex : sur le Bureau)
4. Vous obtenez un dossier `chess-server` avec tous les fichiers âœ…

---

### Ã‰tape 5 â€” Installer le script Tampermonkey

1. Cliquez sur l'icÃ´ne **Tampermonkey** en haut Ã  droite de votre navigateur
2. Cliquez **"Tableau de bord"**
3. Cliquez l'onglet **"Utilitaires"**
4. Dans la section **"Importer depuis un fichier"**, cliquez **"Choisir un fichier"**
5. SÃ©lectionnez le fichier **`chess-coach-v9_5_user.js`** du dossier tÃ©lÃ©chargÃ©
6. Cliquez **"Installer"** âœ…

---

### Ã‰tape 6 â€” Lancer le serveur local

Le serveur local fait le lien entre votre navigateur et Stockfish.

1. Ouvrez le dossier `chess-server`
2. Double-cliquez sur **`lancer.sh`**

   > Si Ã§a ne marche pas, ouvrez PowerShell dans le dossier (cliquez sur la barre d'adresse de l'Explorateur Windows, tapez `powershell`, appuyez sur EntrÃ©e) et tapez :
   > ```
   > python server.py
   > ```

3. Une fenÃªtre noire s'ouvre avec le message `â™Ÿ Serveur lancÃ© â†’ http://localhost:8765` âœ…
4. **Laissez cette fenÃªtre ouverte** pendant toute votre session de jeu

---

## ðŸŽ® Utilisation

1. Lancez le serveur (Ã‰tape 6)
2. Allez sur **[chess.com](https://www.chess.com)** et commencez une partie contre un bot
3. Le panneau **Chess Coach** apparaÃ®t en bas Ã  droite de l'Ã©cran
4. Cliquez **"â–¶ Coach ON"** pour activer l'analyse
5. Une flÃ¨che verte indique le meilleur coup Ã  jouer
6. (Optionnel) Cliquez **"ðŸ¤– Auto-play ON"** pour que le script joue automatiquement

---

## âš™ï¸ Options du panneau

**Coach ON/OFF** â€” Active ou dÃ©sactive l'analyse en temps rÃ©el.

**Auto-play ON/OFF** â€” Le script joue les coups automatiquement Ã  votre place.

**Niveau Stockfish** â€” De 1 (analyse rapide et superficielle) Ã  20 (niveau grand maÃ®tre, calcul long).

**Barre d'Ã©valuation** â€” Affiche qui est en avantage dans la partie. Plus la barre est blanche, mieux c'est pour les blancs. Plus elle est noire, mieux c'est pour les noirs.

---

## â“ ProblÃ¨mes frÃ©quents

**Le panneau Chess Coach n'apparaÃ®t pas**

VÃ©rifiez que Tampermonkey est bien activÃ© (cliquez sur l'icÃ´ne en haut Ã  droite du navigateur et vÃ©rifiez que le script est bien "ActivÃ©"). Rechargez ensuite la page chess.com.

**Le point reste rouge (serveur dÃ©connectÃ©)**

Le serveur Python n'est pas lancÃ©. Retournez Ã  l'Ã‰tape 6. Le point devient vert quand le serveur tourne correctement.

**La promotion de pion ne se fait pas automatiquement**

Assurez-vous d'utiliser la version **v9.5** du script (le fichier `chess-coach-v9_5_user.js`).

**Stockfish introuvable au dÃ©marrage**

VÃ©rifiez que le fichier `.exe` de Stockfish est bien copiÃ© dans le dossier `chess-server`. Le nom du fichier doit commencer par `stockfish`.

---

## âš ï¸ Avertissement

Ce script est conÃ§u pour **s'entraÃ®ner contre des bots** sur chess.com. L'utiliser en partie classÃ©e contre de vrais joueurs est contraire aux conditions d'utilisation de chess.com.

---

## ðŸ“ Contenu du projet

- `server.py` â€” Serveur local Python
- `chess.html` â€” Interface web optionnelle
- `lancer.sh` â€” Script de dÃ©marrage rapide
- `chess-coach-v9_5_user.js` â€” Script Tampermonkey Ã  installer
- `README.md` â€” Ce fichier d'instructions
- `stockfish.exe` â€” Ã€ tÃ©lÃ©charger sÃ©parÃ©ment sur stockfishchess.org (trop lourd pour GitHub)
