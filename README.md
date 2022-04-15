# Django-Polls-App

Développement d'une application simple de questions/réponses en Django pour un projet scolaire de M1 développée avec le framework Python Django en ersion 4.0.4 sur 
un environnement Windows.

## Scénarios

#### Page d'accueil

| Action | Résultat | URL     |
| :-------- | :------- |:------- |
| Accéder au site | Accéder au site | 127.0.0.1:8080/ |
| Cliquer sur "En savoir plus" | Slide vers la partie du bas | 127.0.0.1:8080/# |
| Cliquer sur "Commencer à répondre" | Renvoie vers la liste des sondages | 127.0.0.1:8080/polls/ |

![App Screenshot](https://raw.githubusercontent.com/c-bringer/Django-Polls-App/main/documentation/img/accueil.png)

#### Page de la liste des sondages

| Action | Résultat | URL     |
| :-------- | :------- |:------- |
| Accéder à la page | Affiche la liste des sondages | 127.0.0.1:8080/polls/ |
| Cliquer sur "En savoir plus" | Slide vers la partie du bas | 127.0.0.1:8080/polls/# |
| Cliquer sur une des questions | Renvoi vers le sondage | 127.0.0.1:8080/polls/{idSondage} |

![App Screenshot](https://raw.githubusercontent.com/c-bringer/Django-Polls-App/main/documentation/img/liste_sondages.png)

#### Page détail du sondage

| Action | Résultat | URL     |
| :-------- | :------- |:------- |
| Accéder à la page | Affiche les détails avec les choix à voter | 127.0.0.1:8080/polls/{idSondage} |
| Cliquer sur "En savoir plus" | Slide vers la partie du bas | 127.0.0.1:8080/polls/{idSondage}# |
| Choisir une réponse et cliquer sur "Voter" | Renvoi vers la page des résultats et ajoute en base un vote | 127.0.0.1:8080/polls/{idSondage}/results/ |

![App Screenshot](https://raw.githubusercontent.com/c-bringer/Django-Polls-App/main/documentation/img/detail_sondage.png)

#### Page résultats de sondages

| Action | Résultat | URL     |
| :-------- | :------- |:------- |
| Accéder à la page | Affiche les résultats | 127.0.0.1:8080/polls/{idSondage}/results |
| Cliquer sur "En savoir plus" | Slide vers la partie du bas | 127.0.0.1:8080/polls/{idSondage}/results/# |
| Cliquer sur "Voter à nouveau?" | Renvoi vers la page du sondage | 127.0.0.1:8080/polls/{idSondage} |

![App Screenshot](https://raw.githubusercontent.com/c-bringer/Django-Polls-App/main/documentation/img/result_sondage.png)

#### Page de contact

| Action | Résultat | URL     |
| :-------- | :------- |:------- |
| Accéder à la page | Affiche le formulaire de contact | 127.0.0.1:8080/polls/contact/ |
| Cliquer sur "Envoyer" | Slide vers la partie du bas | 127.0.0.1:8080/polls/contact/# |
| Compléter le formulaire et cliquer sur "Envoyer" | Envoi le formulaire par mail dans la console | 127.0.0.1:8080/polls/# |

![App Screenshot](https://raw.githubusercontent.com/c-bringer/Django-Polls-App/main/documentation/img/contact.png)
