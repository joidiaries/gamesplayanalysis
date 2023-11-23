# Video Game Play Analysis

#### This is a short analysis on games popular between 1980 - 2023.


> **GOAL:** This is to showcase python skills by manipulating data and visualizing results using different libraries.


Here are the **questions** we want to answer:
1. What are the top 10 games under Adventure genre?
2. What are the top 10 games under RPG released in 2022?

#### Reading and exploring the data:
Here is the link to the data source:
Kaggle: [Popular Video Games 1980 - 2023](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023/).
Please note that this data is scrapped from [Backlogged](https://www.backloggd.com/games/lib/popular/) using mostly Beautiful Soup.

![image](https://github.com/joidiaries/gamesplayanalysis/assets/150142726/d719f5be-23e6-44b6-9075-d0ed42b29e17)

#### Data Cleaning and Processing:
1. Choosing relevant columns and droping duplicate rows.
2. Trimming "Year" from "Release Date" for Question 2.
3. Separating value per "Genre" for Question 1.
4. Converting "K" to 1000

![image](https://github.com/joidiaries/gamesplayanalysis/assets/150142726/3fa814ac-c4d4-4b86-bf4f-0a0b66a5861b)


#### Results:

![image](https://github.com/joidiaries/gamesplayanalysis/assets/150142726/69468097-fe11-484b-9568-93cd66af8445)
*The analysis shows the top 10 games under Adventure genre. Top 1 is Minecraft with 33,000 plays.*

![image](https://github.com/joidiaries/gamesplayanalysis/assets/150142726/c2f7a5c8-8031-44e2-8220-f5c9e11aa3b9)
*The analysis shows the top 10 RPG games released in 2022. Top 1 is Elden Ring with 17,000 plays.*
