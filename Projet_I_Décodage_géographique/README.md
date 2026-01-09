Le premier projet consiste à s'entrainer à identifier les différentes localisations des clients d'une entreprise d'un détaillant B2B basé au Royaume-Unis, pour répondre à certaines questions.
Ci-dessous, l'énoncé du projet. (Tiré du livre: "The Well Grounded Data Analyst" de David Asboth).

Project 1: Identifying customer geographies

"As an analyst for ProWidget Systems, a UKbased B2B (business-to-business) retailer, you’ve been asked to report on spending volumes for London-based customers versus those based in the rest of the United Kingdom. The board has supplied a high-level data extract containing all customers’ addresses and their total spending to date. They want to know:
- Which UK cities are currently underserved 
- Whether their customers are primarily London based
The address data for this project comes from Companies House, an executive agency sponsored by the UK government’s Department for Business and Trade. The original public data, at https://mng.bz/mGxr."

I. Reflexions sur le projets

Intérêt du projet : En tant que data scientist, une des tâches les plus fréquentes, est la création d'un graphique pour cartographier la base clientèle d'une entreprise. Combiné à, par exemple, la listes publiques, complète, des entreprises opérant dans les mêmes industries que notre base clientèle: le département des ventes pourraient prospecter et identifier d'autres clients, lors, par exemples des livraisons chez nos clients. La direction pourrait envisager des stratégies d'expansions dans des zones où il y'a de nombreux potentiels clients...

Impact Business: Il est évident qu'avoir plus de clients mènerant à plus de ventes, une augmentation du chiffres d'affaires et des répercussions sur la croissance de l'entreprise.

Approche de résolution:
La première étape, comme dans tout métier d'analyse, est de bien comprendre le sujet, ce qui est demandé, ce qui est attendu comme résultats. Ce à nous quoi nous allons nous attaquer:

Problématique:
Ici, les questions sont plutôt clairs, il s'agit d'identifier, à partir de la base de données clients, les villes les moins bien déservis par nos services (Donc là où les clients dépensent le moins) et d'identifier clairement si l'essentiel de la clientèle est localisé à Londre. 

Réflexions:
Scope: Vu que les données concernent les dépenses "à ce jour", je suppose que l'analyse portera sur les données disponibles depuis la création de l'entreprise (ce n'est pas une étude sur une année, le mois précédent, trimestre...)

--> Sans mention de la base de données disponible, j'aurai eu besoin idéalement de la liste des clients de l'entreprise, des où les clients sont situés, et du total de leur dépenses respectives, tout simplement.
--> D'après le sujet, nous auront une base de données, contenant les addresses des clients, leurs dépenses à ce jour. Il n'y aura, apparemment, pas de problème à trouver les villes les moins déservies et faire une comparaison avec la ville de Londres.(simple classement et tries)

Pour l'instant, la solution finale ressemblera probablement, à un diagramme en bar avec en exergue la ville de londre et les villes les moins déservies, pour répondre aux deux ques

Vu que le projet paraît plutôt simple, J'ai tout de suite envie de voir à quoi les données ressemblent, vu que ce sont  les addresses, il faudra en extraire les villes exactes, en espérant qu'elle soient toutes correctement formulées (ce qui n'arrive presque jamais :-)). Aussi  à quel moment peut-on estimer une ville fait partie des moins desservies, y'a t'il un seuil? dans la même veine, à quel moment j'estime que les clients sont essentiellement à Londres? 

Plongeons nous dans la données pour y voir plus clair.

