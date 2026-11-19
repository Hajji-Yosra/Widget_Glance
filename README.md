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
		

# Questions de compréhension

1. Flutter dessine ses propres pixels, alors qu’un widget est dessiné par le launcher.


2. Compose est dessiné par l’app et se met à jour tout seul. 
Glance est dessiné par le launcher et se met à jour seulement sur demande (updateAll()).


3. La valeur est stockée dans un fichier DataStore. 
Chaque widget posé a ses propres données.


4. Ces fonctions lisent et écrivent un fichier (suspend), et ne doivent pas bloquer l’écran.


5. Le worker démarre seulement quand un widget existe, même si l’app n’est jamais ouverte.


6. La mise à jour du système est lente (30 min minimum) et peu fiable. WorkManager la remplace.


# Exercice 4
<img width="642" height="285" alt="image" src="https://github.com/user-attachments/assets/fc0084a9-f4d2-42ff-bcd8-0aeb3b81db80" />
