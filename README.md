### TD Simulation Individu-Centrée de la capture d'insectes dans des Pièges Barber

Sur cette page vous trouverez un TD portant sur la capture des insectes dans un piège Barber (*'TD Simulation Barber.ipynb'*). 

Dans un premier temps, le TD propose une façon de simuler la capture d'insectes virtuels (représentant des cararbes par exemple) dans des pots Barber, ainsi qu'une visualisation de ce processus (*'Visualisation Exemple.mp4'*). 

Dans un second temps, on simule des bases de données virtuelles (*'data_simulated.xlsx'* et *'data_simulated_dispersion.xlsx'*) pour calibrer un modèle bayésien hierarchique. Ce modèle a pour objectif de prédire le nombre initial d'individus sur la parcelle en fonction du nombre d'individus piégés dans les pots en fin de simulation et de leur capacité de dispersion. La définition du modèle est donnée dans le TD. Afin d'obtenir les distributions a posteriori des paramètres du modèle (~ capacité de dispersion et nombre intial d'individus sur la parcelle) il est nécessaire de le calibrer, mais les résultats de la calibration (Echantillons des chaines de Markov) sont également données dans ce repo (*'Données\Echantillon_MCMC_Model_Dispersion_et_Densité.nc'*) 
