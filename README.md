# ORteaching

Cours d'initiation à la Recherche Opérationnelle distribué sous licence CC-BY-NC-SA

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


A partir de mes cours de Recherche Opérationnelle (RO) et d'Optimisation Discrète à l'ENSTA Paris, Polytech' Paris-Saclay, et à l'université Paris-Saclay, 
Ce cours est une version unifiée et étendue de mon cours de Recherche Opérationnelle et Optimisation Discrète de mes cours de Recherche Opérationnelle (RO) et d'Optimisation Discrète à l'ENSTA Paris, Polytech' Paris-Saclay, et à l'université Paris-Saclay. 

Le cours initial de l'ENSTA était conçu pour les ingénieurs : sensibilisation aux notions fondamentales et les outils de la RO dans une optique utilisateur ou pouvoir dialoguer avec des experts de la RO. Enseigner un cours similaire à des étudiants sélectionnés de double licence mathématiques et informatique m'a amené à développer plus de liens et des ponts avec la rigueur mathématique et des bases solides d'algorithmique et de programmation informatique.


Le programme de ce cours est organisé comme suit dans la version en ligne.


Deux chapitres introductifs sont facultatifs, pour rappeler ou mentionner des résultats de l'optimisation continue. Cela permet de mettre en évidence des différences avec l'optimisation discrète, pour éviter les confusions. N.B : il est également intéressant avant les cours de Machine Learning d'avoir des notions d'algorithmes de gradient. Pour ce cours, on peut également voir l'algorithme du simplexe comme un algorithme de gradient projeté spécialisé pour les programmes linéaires :


- [OA00-OptimDimension1.pdf](https://github.com/ndupin/ORteaching/blob/main/OA00-OptimDimension1.pdf) : rappel des propriétés et difficultés générales de l'optimisation continue en dimension un (une variable)
- [OA0-OptimDimensionN.pdf](https://github.com/ndupin/ORteaching/blob/main/OA0-OptimDimensionN.pdf)  : de l'optimisation sans contrainte à l'optimisation avec contraintes et algorithmes numériques pour l'optimisation dans R^n.


La première partie du cours traite des fondements de l'optimisation discrète et linéaire, premiers résultats et algorithmes fondamentaux et techniques de modélisation pour l'optimisation linéaire:

- OA1-optim-complexite.pdf : fondements de l'optimisation discrète, premiers algorithmes fondamentaux et techniques de modélisation pour l'optimisation linéaire
- [OA2-ProgDynamique.pdf](https://github.com/ndupin/ORteaching/blob/main/OA2-ProgDynamique.pdf) : algorithmes de programmation dynamique pour l'optimisation combiantoire, études de cas : problèmes de sacs à dos, plus court chemins, voyageur de commerce, clustering 1D et application industrielle de plannings d' horaires de train
- OA3-PL-dualite.pdf : résolution de PL : résolution graphique à deux variables, algorithme du simplexe, éléments de théorie de la dualité
- [OA4-model-PLNE.pdf](https://github.com/ndupin/ORteaching/blob/main/OA4-model-PLNE.pdf) : techniques générales pour linéariser et modéliser des problèmes d'optimisation complexes comme des PL/PLNE, applications aux problèmes d'affectation, de clustering, ordonnancement, et application à la production d'électricité.
- [OA5-optim-graphes-PLNE.pdf](https://github.com/ndupin/ORteaching/blob/main/OA5-optim-graphes-PLNE.pdf) : Modélisation PLNE de problèmes d'optimisation de graphes : couvertures, colorations, cliques maximales/ensembles indépendants, plus court chemins, voyageur de commerce. Présentation d'heuristiques simples et utilisation de la théorie PL pour l'optimisation des graphes.


La dernière partie du cours OA se concentre sur les algorithmes de recherche arborescentes  pour l'optimisation combinatoire, principalement les variantes de l'algorithme Branch&Bound.

- OA6-KnapsackResolution.pdf : résolution du problème standard du sac à dos : algorithmes gloutons, heuristique de programmation dynamique avec Kernel Search, Branch&Bound.
- [OA7-resolPLNE.pdf](https://github.com/ndupin/ORteaching/blob/main/OA7-resolPLNE.pdf) : généralisation du Branch&Bound présenté pour le problème du sac à dos : algorithme Branch&Bound, opérateurs et outils pour résoudre les MILPs.
- [OA8-treeSearch.pdf](https://github.com/ndupin/ORteaching/blob/main/OA8-treeSearch.pdf) : généralisation de Branch&Bound : Branch&Cut, Branch&Bound sans relaxation LP, Branch&Reduce, autres recherches arborescentes pour l'IA et la RO : Beam Search et analogie entre Branch&Bound et Contraint Programming.
- OA9-DWcolGeneration.pdf : relaxation lagrangienne, algorithme de génération de colonne, reformulation de Dantzig Wolfe et Branch&Price.
- OA10-Benders-OptimUncertain.pdf : Décomposition de Benders et introduction à l'optimisation stochastique et robuste pour l'optimisation sous incertitude


Un autre cours porte sur l'initiation aux méta-heuristiques pour l'optimisation combinatoire, comme application de la programmation parallèle et distribuée avec MPI (Message Passing Interface):
- MPI-MH.pdf

Pour la partie MPI, le cours est classique et non mis en ligne. Je réfère au cours de Frank Nielsen de l'Ecole Polytechnique, avec un excellent polycopié en français :
https://www.researchgate.net/publication/326234797_Traitement_des_donnees_massives_INF442

Une version étendue en anglais est publiée sous forme de livre Springer, F. Nielsen. Introduction to HPC with MPI for Data Science. Springer, 2016, https://link.springer.com/book/10.1007/978-3-319-21903-5 .

Des TP de ce cours sont mis en ligne à l'adresse suivante:
https://franknielsen.github.io/HPC4DS/index.html


Dans ce cours, les algorithmes de Machine Learning sont présentés et utilisés comme une application de la programmation MPI, alors que dans mon cours, j'ai choisi les méta-heuristiques pour l'optimisation combinatoire comme application du calcul parallèle et distribué avec MPI, ce qui complète le cours d'optimisation exacte dans le cursus de le Master Réseaux Avancés et Optimisation (ANO) de l'Université Paris-Saclay.
