
# Mini-cours Web – BTS SIO

Mini-site de démonstration pour la classe de **BTS SIO**.  
Objectif : revoir les bases de **HTML**, **CSS** et **SQL** avec des exemples simples et des petites activités à modifier.

---

## 1. Structure du projet

- `index.html`  
  Page d’accueil avec présentation et liens vers chaque mini-cours.

- `HTML/`
  - `index.html` : cours complet HTML (balises de base, listes, liens, images, tableaux, formulaires, etc.).
  - `cours-html.zip` *(optionnel)* : archive à télécharger de la page/exemples HTML.

- `CSS/`
  - `index.html` : mini-cours CSS (thème clair/sombre, menu, box model, flexbox, pseudo-classes…).
  - `style.css` : feuille de style principale.
  - `cours-css.zip` *(optionnel)* : archive à télécharger de la page/exemples CSS.

- `SQL/`
  - `index.html` : mini-cours SQL (création BD, import CSV, formes normales, jointures, contraintes, dates…).
  - `style.css` : style de la page SQL.
  - `screens/` : captures d’écran phpMyAdmin.
  - `cours-sql.zip` *(optionnel)* : archive à télécharger des scripts/exemples SQL.

---

## 2. Comment lancer le site

1. Ouvrir le dossier `exemples codes`.
2. Double-cliquer sur `index.html` pour ouvrir la page d’accueil dans un navigateur (Chrome, Edge, Firefox…).
3. Cliquer sur :
   - **“Ouvrir le cours HTML”**
   - **“Ouvrir le cours CSS”**
   - **“Ouvrir le cours SQL”**
   selon la partie à travailler.

---

## 3. Utilisation en classe

### 3.1. Partie HTML

- Lire les explications section par section.
- En bas de la page, utiliser la section **“Utilisation : pratiquer le HTML en direct”** :
  - Zone de gauche : code HTML avec des `<!-- TODO -->` à compléter.
  - Bouton **“Exécuter le code”** : met à jour l’aperçu à droite (dans une iframe).
- Idée d’exercice : demander aux étudiants de créer une mini-page de présentation en complétant tous les TODO.

### 3.2. Partie CSS

- Observer l’effet de `style.css` sur la page :
  - changement de thème (bouton “Changer de thème”),
  - menu de navigation,
  - box model,
  - flexbox,
  - pseudo-classes.
- En TP, ouvrir `CSS/index.html` et `CSS/style.css` dans un éditeur (VS Code, Notepad++, etc.) et modifier les couleurs, marges, polices…

### 3.3. Partie SQL

- Lire les explications puis reproduire les opérations dans **phpMyAdmin** (via WAMP / XAMPP) :
  - création de base / tables,
  - import CSV,
  - requêtes `SELECT`, `JOIN`, `ORDER BY`, `GROUP BY`, etc.
- Les images du dossier `screens/` illustrent les manipulations à faire.

---

## 4. Archives ZIP (facultatif)

Si tu ajoutes les fichiers ZIP :

- `HTML/cours-html.zip`
- `CSS/cours-css.zip`
- `SQL/cours-sql.zip`
- éventuellement `mini-cours-bts-sio.zip` à la racine,

les étudiants pourront télécharger les sources directement depuis les boutons de chaque page.

---

## 5. Pré‑requis techniques

- Un navigateur web récent.
- Pour la partie SQL :
  - WAMP / XAMPP / autre serveur local,
  - phpMyAdmin ou équivalent.
