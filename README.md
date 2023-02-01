Compiler avec la commande :
```bash
cd src
javac -d "..\class" *.java (sous Windows)
javac -d "../class" *.java (sous Linux)
```
Exécuter avec la commande :
```bash
cd src
java -cp "..\class" Main [options] (sous Windows)
java -cp "../class" Main [options] (sous Linux)
```

Options : 
	-jeu_non_graphique ou -jng :
		Active le jeu non graphique
		(le jeu se lance en mode graphique par d�faut de cet argument).

	-choix_auto ou -cha :
		Active le choix des fant�mes automatis� (pour les tests).

