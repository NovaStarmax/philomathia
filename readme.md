# 🧠 Philomathia : Mathématiques et Intelligence Artificielle

Philomathia est un projet éducatif interactif destiné à initier les apprenants aux concepts mathématiques essentiels pour la data science et l’intelligence artificielle. Considérez les mathématiques comme un langage universel reliant les esprits savants au fil des siècles et un outil fondamental pour explorer, découvrir et innover dans le monde scientifique.

> “Les mathématiques sont bien plus que des chiffres et des équations : elles sont l’origine même de la science, le fondement sur lequel repose notre compréhension du monde.” — Larousse 2023

## 📚 Table des matières

- Contexte du projet
- Structure du projet
- Installation des dépendances
- Glossaire des concepts mathématiques
- Compétences visées

---

## 📝 Contexte du projet

Les mathématiques sont bien plus que des outils abstraits ; elles transcendent les frontières et forment un langage commun. Utilisées dans des disciplines aussi diverses que l’astronomie, la physique, la biologie, et la chimie, elles permettent à l’humanité de progresser vers des découvertes et des innovations scientifiques. Dans Philomathia, vous allez manipuler des concepts mathématiques essentiels, vus comme des alliés précieux dans votre parcours en intelligence artificielle.

Les Notebooks Python, qui servent de support à ce projet, offrent une exploration interactive de ces concepts mathématiques, avec du code, du texte, et des visualisations pour une meilleure compréhension.

## 📂 Structure du projet

Le projet Philomathia est structuré comme suit :

- `philomathia.ipynb` : Le notebook Jupyter contenant les différents exercices interactifs et analyses mathématiques.
- `README.md` : Ce fichier, qui inclut la documentation de veille scientifique détaillant chaque concept mathématique et expliquant leur importance pour la data science.

## ⚙️ Installation des dépendances

Pour exécuter le notebook et travailler sur les différents exercices, assurez-vous d’avoir installé les bibliothèques nécessaires. Voici les commandes d’installation à exécuter dans votre terminal :

```bash
pip install numpy
pip install --upgrade pandas
pip install --upgrade sympy
pip install --upgrade matplotlib
pip install --upgrade sklearn
```

## 🔍 Glossaire des concepts mathématiques

### 🌐 Mathématiques fondamentales

1. **Vecteur**
   - Un vecteur est une quantité ayant à la fois une magnitude et une direction. En IA, les vecteurs sont souvent utilisés pour représenter les caractéristiques des données, comme les pixels d’une image.
   - *Exemple* : Un vecteur de position indique un déplacement de 3 unités sur l’axe X et 4 unités sur l’axe Y.

2. **Matrice**
   - Une matrice est un tableau de nombres organisés en lignes et colonnes, souvent utilisé pour les transformations de données et les calculs de réseaux neuronaux.
   - *Exemple* : La matrice est une matrice 2x2 où chaque élément représente une valeur spécifique.

### 📊 Concepts de Probabilité et Statistiques

3. **Probabilité, Loi de probabilité**
   - La probabilité mesure la chance qu’un événement se produise. Une loi de probabilité décrit la distribution des probabilités pour un ensemble d’événements possibles.
   - *Exemple* : La probabilité de tirer un as d’un jeu de cartes standard est de 4/52 (soit 7,7 %).

4. **Variables indépendantes**
   - Deux variables sont indépendantes si la variation de l’une n’affecte pas la variation de l’autre, une condition importante dans la modélisation statistique.
   - *Exemple* : Le résultat d’un lancer de dé et le tirage d’une carte d’un jeu sont indépendants l’un de l’autre.

5. **Espérance, Variance et Écart Type**
   - **Espérance** : Moyenne des valeurs possibles d’une variable aléatoire, pondérée par leur probabilité.
     - *Exemple* : L’espérance d’un lancer de dé à six faces est 3.5.
   - **Variance** : Mesure de la dispersion des valeurs par rapport à l’espérance.
     - *Exemple* : Pour un dé, la variance est 2.92.
   - **Écart Type** : Racine carrée de la variance, indiquant l’ampleur de la dispersion des données.
     - *Exemple* : Pour un dé, l’écart type est la racine carrée de la variance.

6. **Corrélation linéaire**
   - La corrélation linéaire mesure la relation entre deux variables, indiquant la force et la direction de leur association.
   - *Exemple* : La corrélation entre la taille et le poids est souvent positive.

7. **Moyenne, Médiane, Maximum, Minimum**
   - **Moyenne** : Somme des valeurs divisée par le nombre de valeurs.
     - *Exemple* : Pour les valeurs 1, 2, 3, la moyenne est 2.
   - **Médiane** : Valeur centrale d’un ensemble de données ordonnées.
     - *Exemple* : La médiane de 1, 3, 3, 6, 7, 8, 9 est 6.
   - **Maximum et Minimum** : Les valeurs extrêmes dans un ensemble de données.
     - *Exemple* : Pour l’ensemble 1, 2, 3, le maximum est 3 et le minimum est 1.

### 📈 Concepts statistiques avancés

8. **Quartiles**
   - Les quartiles divisent les données en quatre parties égales, facilitant l’analyse des données réparties.
   - *Exemple* : Si un ensemble de données ordonnées est 1, 3, 5, 7, 9, 11, le premier quartile (Q1) est 3.

9. **Boxplot**
   - Un boxplot est un graphique qui visualise la distribution des données, montrant les valeurs minimales, maximales, les quartiles, et la médiane.
   - *Exemple* : En visualisant les notes d’un groupe d’étudiants, un boxplot peut montrer les notes les plus basses, les plus hautes, et la médiane.

10. **Histogramme**
    - Un histogramme représente la fréquence de valeurs dans des intervalles spécifiques, montrant la distribution des données.
    - *Exemple* : Un histogramme peut montrer la distribution d’âge d’un groupe de personnes en groupes de 10 ans.

11. **Théorème Central Limite**
    - Ce théorème indique que la somme des variables aléatoires indépendantes suit une distribution normale, même si les variables originales ne sont pas normales.
    - *Exemple* : Si on additionne les résultats de nombreux lancers de dés, la distribution des sommes tendra vers une courbe en cloche.

12. **Dérivée**
    - La dérivée d’une fonction mesure la vitesse de changement de cette fonction en un point donné.
    - *Exemple* : La dérivée de la fonction f(x) = x^2 est f'(x) = 2x.

## 🎯 Compétences visées

Ce projet vise à renforcer les compétences suivantes :

- Compréhension et application de concepts mathématiques essentiels.
- Familiarité avec les Notebooks Python pour la visualisation et la simulation de concepts mathématiques.
- Développement de bases solides pour la data science et l’intelligence artificielle.
