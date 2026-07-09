# ⚽ BIG WINNER — Planning Officiel du Tournoi

Ce dépôt contient le site vitrine et le planning interactif officiel de la première édition du tournoi de football **BIG WINNER** (32 équipes, 1 terrain, 4 jours).

Le site a été conçu pour être à la fois esthétiquement marquant (thème sportif sombre, animations, compte à rebours) et hautement interactif.

---

## 🚀 Fonctionnalités Clés

1. **Design Premium "Wow"** : Thème sombre moderne optimisé pour mobile et bureau, avec effet de verre dépoli (glassmorphisme) et accents lumineux.
2. **Personnalisation en Temps Réel** : Un panneau latéral vous permet de remplacer les codes génériques des équipes (`A1`, `B4`, etc.) par les vrais noms des clubs participants.
   * *Persistance* : Les noms saisis sont sauvegardés automatiquement dans le navigateur (`localStorage`) et se mettent à jour instantanément sur toutes les pages et dans le planning.
3. **Moteur de Recherche Dynamique** : Une barre de recherche globale permet de filtrer instantanément les matchs par club, par phase (Poule, Quart, Demi, Finale) ou par horaire.
4. **Filtre par clic** : Cliquez sur n'importe quelle équipe dans la composition des poules pour afficher instantanément tous ses matchs programmés.
5. **Compte à rebours intégré** : Calcule en temps réel le temps restant avant le coup d'envoi le vendredi 13 novembre 2026 à 15h00.

---

## 🛠️ Comment utiliser en local ?

Il s'agit d'un site statique ultra-léger (HTML/CSS/JS natifs, sans dépendance lourde).
Pour l'exécuter :
1. Téléchargez ou clonez ce dossier.
2. Double-cliquez sur le fichier `index.html` ou ouvrez-le avec n'importe quel navigateur web.

---

## 🌐 Déploiement sur GitHub Pages

Pour rendre ce planning accessible en ligne à tous les participants, joueurs et supporters, vous pouvez le déployer gratuitement sur **GitHub Pages**. Voici la procédure pas à pas :

### Étape 1 : Créer un dépôt sur GitHub
1. Connectez-vous sur votre compte [GitHub](https://github.com).
2. Cliquez sur le bouton **New** (Nouveau dépôt).
3. Nommez votre dépôt (par exemple : `tournoi-big-winner`).
4. Choisissez de le laisser en **Public** (nécessaire pour GitHub Pages gratuit).
5. Ne cochez pas "Add a README" (nous en avons déjà créé un) et cliquez sur **Create repository**.

### Étape 2 : Envoyer vos fichiers sur GitHub
Dans votre terminal local (dans ce dossier), exécutez les commandes suivantes :

```bash
# Initialiser le dépôt git local
git init

# Ajouter les fichiers
git add .

# Faire le premier commit
git commit -m "Initialisation du site vitrine BIG WINNER"

# Renommer la branche principale
git branch -M main

# Associer au dépôt GitHub (remplacez par votre lien de dépôt)
git remote add origin https://github.com/VOTRE_NOM_UTILISATEUR/tournoi-big-winner.git

# Envoyer les fichiers sur GitHub
git push -u origin main
```

*(Note : Si vous ne souhaitez pas utiliser le terminal, vous pouvez directement glisser-déposer les fichiers `index.html`, `BIG_WINNER_Planning_Tournoi.html` et `README.md` sur l'interface web de GitHub.)*

### Étape 3 : Activer GitHub Pages
1. Sur la page de votre dépôt sur GitHub, allez dans l'onglet **Settings** (Paramètres, icône d'engrenage).
2. Dans la barre latérale gauche, sous la section *Code and automation*, cliquez sur **Pages**.
3. Sous **Build and deployment** > **Source**, assurez-vous que **Deploy from a branch** est sélectionné.
4. Sous **Branch**, sélectionnez **main** (ou la branche principale) et le dossier `/ (root)`.
5. Cliquez sur **Save** (Enregistrer).

### Étape 4 : Accéder au site
Après 1 à 2 minutes, GitHub générera un lien public sous la forme :  
`https://VOTRE_NOM_UTILISATEUR.github.io/tournoi-big-winner/`

Votre planning est désormais en ligne et accessible par tous !

---

## 📅 Structure du planning (32 matchs)

* **Jour 1 (Vendredi 13 nov. - 15h à 18h)** : Barrages des poules A et B.
* **Jour 2 (Samedi 14 nov. - 8h à 18h)** : Barrages des poules C à H et finale de la poule A.
* **Jour 3 (Dimanche 15 nov. - 13h à 18h)** : Finales des poules B à G.
* **Jour 4 (Lundi 16 nov. - 8h à 18h)** : Finale de la poule H, Quarts de finale, Demi-finales, match pour la 3e place et **Grande Finale** à 16h15.
