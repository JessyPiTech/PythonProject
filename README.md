# 🗺️ Alcoolémis – Carte interactive de la consommation d'alcool mondiale

Une **visualisation interactive** de la consommation d'alcool par pays, avec une **touche d'humour**. Ce projet utilise des données publiques fiables pour créer plusieurs **visualisations dynamiques** en Python.

## 🍷 Objectifs

- Carte mondiale interactive de la consommation d'alcool
- Analyse comparative par continent
- Top 10 des pays consommateurs
- Évolution temporelle des plus gros consommateurs
- Tendances mondiales (moyenne et médiane)
- Tableaux de mini-graphiques par pays

---

## 📊 Sources de données

- **Origine** : [Our World in Data – Consommation d'alcool](https://ourworldindata.org/alcohol-consumption)
- **Format** : CSV
- **Métrique principale** : `Consommation d'alcool par habitant (litres d'alcool pur, estimations projetées, 15+ ans)`

---

## 📈 Visualisations disponibles

1. **Carte du monde interactive**
   - Affichage par code couleur
   - Annotations humoristiques
   - Données détaillées au survol

2. **Analyse continentale**
   - Comparaison entre continents
   - Graphique à barres horizontal
   - Moyennes par région

3. **Top 10 des pays**
   - Classement des plus gros consommateurs
   - Visualisation en barres
   - Annotations personnalisées

4. **Évolution temporelle**
   - Suivi des 5 premiers pays
   - Graphique linéaire sur 20 ans
   - Tendances historiques

5. **Statistiques mondiales**
   - Moyenne et médiane mondiale
   - Évolution sur 20 ans
   - Double courbe comparative

6. **Vue détaillée par pays**
   - Mini-graphiques individuels
   - Évolution pour chaque nation
   - Vue d'ensemble comparative

## 🧰 Bibliothèques Python requises

- `pandas` – Traitement des données
- `plotly.express` – Visualisations interactives
- `plotly.graph_objects` – Graphiques personnalisés
- `pycountry` – Gestion des codes pays ISO

Installation des dépendances :
```bash
pip install pandas plotly pycountry
```

## 🎨 Palette de couleurs
- Rouge pour la carte thermique mondiale
- Dégradé personnalisé pour les graphiques
- Codes couleur cohérents entre les visualisations
