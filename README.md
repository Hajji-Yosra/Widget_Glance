# tp5_widget

<img width="320" height="750" alt="3" src="https://github.com/user-attachments/assets/f19b5656-99c4-448c-b8f3-b3b56b107c18" />
<img width="320" height="750" alt="4" src="https://github.com/user-attachments/assets/07f9aa9c-d1b3-4697-ab38-f1d9cc53b678" />
<img width="320" height="750" alt="3" src="https://github.com/user-attachments/assets/4a0047fe-1748-4e97-ba55-b5eb2d3a9125" />
<img width="320" height="750" alt="2" src="https://github.com/user-attachments/assets/0779bcb1-d694-412d-a3eb-a1fb62b1781f" />
<img width="320" height="750" alt="5" src="https://github.com/user-attachments/assets/8321d5f8-d5a7-4fd9-ac08-e404cad0177a" />

# Questions des étapes:
Étape 1. 
	Sans la ligne <receiver>, le système ne connaît plus le widget : il n’apparaît 	plus dans la liste des widgets.


Étape 2. 
	Le widget reposé affiche rien car L’état n’existe que pour les widgets posés. 


Étape 3. 
	le processus de l'application exécute RafraichirAction . On le vérifier dans Logcat.


Étape 4. 
	Mettre à jour le widget toutes les 5 secondes n’est pas possible, pour deux raisons :
		- WorkManager impose un minimum de 15 minutes entre chaque exécutions.
		- Consomme et vide la batterie pour rien.

# Exercice 4
<img width="642" height="265" alt="image" src="https://github.com/user-attachments/assets/fc0084a9-f4d2-42ff-bcd8-0aeb3b81db80" />
