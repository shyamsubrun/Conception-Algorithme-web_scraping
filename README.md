# Conception-Algorithme-web_scraping
**Projet : A Song of Link and Wire**

Ce projet vise à créer un bot pour le jeu "A Song of Link and Wire" basé sur le wiki Game of Thrones. Les fonctionnalités clés sont les suivantes :

1. **Liste des Liens :** La fonction `liste_liens(page)` utilise les bibliothèques `requests` et `BeautifulSoup` pour extraire les liens hypertexte d'une page du wiki.

2. **Construction du Graphe :** Les fonctions `svg_dico(dico, fichier)` et `chg_dico(fichier)` permettent respectivement de sauvegarder le graphe du wiki localement et de le charger.

3. **Recherche du Plus Court Chemin :** La fonction `plus_court_chemin(source, cible)` trouve le chemin le plus court entre deux pages du wiki en utilisant un parcours en largeur.

4. **Pondération des Liens :** La fonction `pcc_voyelles(source, cible)` utilise l'algorithme de Dijkstra pour trouver un chemin de poids minimal, en considérant la longueur des pages et la présence de voyelles.

5. **Relations entre Personnages :** Obtention d'un graphe des relations entre personnages en considérant les fratries, les relations parent/enfant, et les amants/mariés. Identification des couples incestueux et création d'un graphe de descendance.
