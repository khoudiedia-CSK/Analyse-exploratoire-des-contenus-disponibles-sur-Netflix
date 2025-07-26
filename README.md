# 🎬 Analyse du catalogue Netflix

Ce projet est une **analyse exploratoire des contenus disponibles sur Netflix** à partir du dataset public `netflix_titles.csv`.  
Nous examinons l’évolution des ajouts de titres dans le temps, la répartition entre films et séries, ainsi que des tendances mensuelles.

---

## 📂 Contenu

- 📈 Analyse temporelle des ajouts (annuelle et mensuelle)
- 🎥 Évolution des **films** ajoutés
- 📺 Évolution des **séries TV**
- 📊 Visualisations sauvegardées dans `/images`
- 📁 Fichier de données : `netflix_titles.csv.zip`

---

## 🛠️ Technologies utilisées

- Python 3
- Pandas
- Matplotlib
- Seaborn

---

## 🔍 Aperçu des analyses

### 📅 1. Contenus ajoutés par an
Graphique en barres empilées
Montre le nombre total de contenus ajoutés chaque année.

Séparé par type : films et séries.

On voit une forte croissance jusqu’en 2019, puis un ralentissement après 2020.
<img width="626" height="290" alt="graphique_1" src="https://github.com/user-attachments/assets/7e689d74-c566-493b-b848-8569e176d9dc" />



### 🎬 2. Films ajoutés chaque année

Graphique en ligne rouge
Affiche le nombre de films ajoutés chaque année.

Forte hausse entre 2016 et 2019.

Baisse nette après 2020 (possiblement à cause de la pandémie ou de changement de stratégie de Netflix).
<img width="616" height="286" alt="graphique_2" src="https://github.com/user-attachments/assets/631b5c74-e362-47e8-9fc1-b455624a0bf3" />


### 📺 3. Séries ajoutées chaque année

Graphique en ligne bleue
Montre le nombre de séries ajoutées chaque année.

Tendance plus stable que les films.

Léger pic autour de 2018-2019, puis une stabilisation.
<img width="619" height="284" alt="graphique_3" src="https://github.com/user-attachments/assets/d8c753c1-28b9-4e83-9eec-086cb262610f" />


### 📆 4. Tendances mensuelles globales

Graphique en ligne violette

Visualise l’évolution mensuelle des ajouts de contenus (films + séries).

Permet de repérer des tendances saisonnières (ex. : plus d’ajouts en fin d’année).
<img width="821" height="328" alt="graphique_4" src="https://github.com/user-attachments/assets/61d827e2-c9d4-4ca5-b36b-aefd054d5ea4" />



