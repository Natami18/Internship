Dans ce répertoire, il y a toutes les images, graphes et vidéos faites pendant le stage et utiles à la compréhension du rapport.
Ce répertoire est rangé de la manière suivante : 

	I) Dimension
		A) Problème étudié
			1) Solutions
			2) Vecteurs propres
			3) Tests
				a) Méthodes utilisés pour résoudre le problème

Pour tous les problèmes et dans toutes les dimensions, des tests de weak scaling ont été effectués. 
Pour ces tests, on fixe $\omega = 10^6$ Hz.

En 2D, pour le problème 1, des tests de strong scaling ont été effectués. 
Pour ces tests, on fixe $\alpha = 0.3$ et $L = 5$ mm. 

Pour le problème 2, les graphes et les images représentent les erreurs $e = |u - u'|$ obtenues après utilisation de la méthode de décomposition de domaine à 2 niveau de préconditionnement en tant que solveur avec l'espace grossier FEHGS.

Les noms des sous-répertoires et leur correspondance sont regroupés dans le tableau ci-dessous.

|||
|:-:|:-:|
| Problème 1 | Problème $A.12$ |
| Problème 2 | Problème $C.2$ |
| Problème 3 | Problème $E.2$ (problème d'imagerie médicale) |
| Frequency | $\omega$ |
| Nb subdomains| $N_P$ |
| Fracndofbnd | $\alpha$ |
| Q | $M_0^{-1}$ |
|||

--------------------------------------------------------------------------
--------------------------------------------------------------------------

In this repository, there are images, graphs and videos made during the internship and useful to understand the report.
This repository is organized as follow : 

	I) Dimension
		A) Studied problem
			1) Solutions
			2) Eigenvectors
			3) Tests
				a) Method used to solve the problem

For all problems and all dimensions, weak scaling tests have been done.
For these tests, we set $\omega = 10^6$ Hz.
In 2D, for problem 1, strong scaling tests have been done.
For these tests, we set $\alpha = 0.3$ et $L = 5$ mm. 

For problem 2, the graphs and images represent the errors $e = |u - u'|$ obtained after using domain decomposition method with 2-level preconditionning as a solver using FEHGS as coarse space.

The sub-repositories names and their references are summarized in the table below :

|||
|:-:|:-:|
| Problème 1 | Problem $A.12$ |
| Problème 2 | Problem $C.2$ |
| Problème 3 | Problem $E.2$ (medical imaging problem) |
| Frequency | $\omega$ |
| Nb subdomains| $N_P$ |
| Fracndofbnd | $\alpha$ |
| Q | $M_0^{-1}$ |
|||