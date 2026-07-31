# 📅 Gestionnaire de Planning Paramétrable

Un outil web simple, fluide et 100% autonome pour générer, visualiser, personnaliser et imprimer des plannings de roulement et de travail en équipe (3x8, 2x8, 5x8, cycles personnalisés, etc.).

🔗 **Projet en ligne / Modèles :** [https://planning-poste.pages-perso.free.fr/](https://planning-poste.pages-perso.free.fr/)

---

## ✨ Fonctionnalités

- 🗓️ **Vue Annuelle Complète** : Visualisation sous forme de grille synthétique des 12 mois de l'année.
- 👥 **Affichage Multi-Équipes ou Individuel** :
  - **Vue d'ensemble** : Affiche toutes les équipes côte à côte avec les noms orientés verticalement en en-tête.
  - **Vue par équipe** : Zoom sur le planning d'une équipe ou d'une personne spécifique.
- ⚙️ **Paramétrage Évolué de la Rotation** :
  - Date de début du cycle et durée du cycle (en jours).
  - Gestion du nombre d'équipes et du décalage en jours entre chaque équipe.
  - Personnalisation complète des libellés de postes/jours (ex: *M*, *A*, *N*, *RH*...).
  - **Gestion avancée des couleurs** : Choix de la couleur de fond ET de la couleur de texte pour chaque jour du cycle (possibilité d'afficher des cases à fond blanc avec texte coloré).
- 🇫🇷 **Jours Fériés & Week-ends** : Calcul automatique des jours fériés français (y compris fêtes mobiles comme Pâques, Ascension, Pentecôte) et mise en valeur visuelle des week-ends/fériés.
- 💾 **Sauvegarde & Import/Export** :
  - Enregistrement automatique de vos réglages dans le navigateur (`localStorage`).
  - Exporter et charger votre configuration facilement via un fichier de configuration `.json`.
  - Bouton pour réinitialiser ou repartir d'un planning vide.
- 🖨️ **Optimisé pour l'Impression / PDF** : Style d'impression intégré (`@media print`) masquant automatiquement les panneaux de configuration et adaptant le calendrier pour un rendu papier ou PDF parfait.

---

## 🚀 Prise en main rapide

Cet outil fonctionne entièrement en local dans votre navigateur. Aucune installation de serveur ni base de données n'est requise.

### 1. Utilisation locale
1. Téléchargez ou clonez ce dépôt.
2. Ouvrez directement le fichier `planning.html` dans n'importe quel navigateur récent (Chrome, Firefox, Edge, Safari).

### 2. Publication sur GitHub Pages
Pour rendre votre planning accessible directement via une URL web publique grâce à GitHub Pages :
1. Renommez le fichier `planning.html` en `index.html` (ou conservez `planning.html`).
2. Allez dans les **Settings** (Paramètres) de votre dépôt GitHub.
3. Dans la section **Pages** (menu de gauche) :
   - Sous **Source**, sélectionnez la branche `main` (ou `master`).
   - Cliquez sur **Save**.
4. Votre site sera disponible sous quelques minutes à l'adresse :  
   `https://<votre-compte>.github.io/<nom-du-depot>/`

---

## 🛠️ Guide de Configuration

Pour configurer votre planning :
1. Cliquez sur le bouton **⚙️ Réglages**.
2. **Paramètres de la rotation** :
   - Indiquez la **date de début** de votre cycle de référence.
   - Réglez la **durée du cycle** (ex: 7, 14, 21, 28 jours...).
   - Indiquez le **nombre d'équipes** (ex: 3, 4, 5...) et le **décalage** en jours entre deux équipes successives.
3. **Noms des équipes** : Saisissez les noms personnalisés de vos équipes ou collaborateurs.
4. **Définition des jours du cycle** :
   - Entrez le code ou le texte de chaque jour (ex: `M` pour Matin, `A` pour Après-midi, `N` pour Nuit, `RH` pour Repos...).
   - Choisissez la **couleur de fond** et la **couleur de texte** pour chaque poste.
5. Cliquez sur **Appliquer et enregistrer**.
6. Vous pouvez télécharger votre configuration grâce au bouton **💾 Sauvegarder en .json** pour la partager ou la réimporter ultérieurement.

---

## 📄 Licence & Crédits

- Développé pour la gestion simplifiée des plannings de roulement de postes.
- Site de référence et ressources : [https://planning-poste.pages-perso.free.fr/](https://planning-poste.pages-perso.free.fr/)
