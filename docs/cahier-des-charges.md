# Cahier des charges

Chaque exigence est numérotée et reliée à un test de validation.
La colonne Résultat sera remplie à la fin du projet, avec une preuve (capture ou vidéo).

| ID | Exigence | Test de validation | Résultat |
|---|---|---|---|
| EX-01 | Le coffre ne s'ouvre qu'avec un badge enrôlé | Badge valide ouvre, badge inconnu refusé | À tester |
| EX-02 | Un badge copié est détecté | Clone de l'UID sur la carte magique : alarme | À tester |
| EX-03 | Trois échecs bloquent le coffre 60 s | 3 mauvais badges : blocage | À tester |
| EX-04 | Une ouverture sans badge déclenche l'alarme | Ouvrir le couvercle sans badge | À tester |
| EX-05 | Une attaque à l'aimant est détectée | Aimant externe + ouverture : événement ATTAQUE_AIMANT_SUSPECTEE | À tester |
| EX-06 | Des vibrations répétées déclenchent l'alarme | Taper 5 fois sur la boîte | À tester |
| EX-07 | État, mesures et journal sont visibles dans l'application | Contrôle visuel | À tester |
| EX-08 | L'application peut verrouiller, jamais déverrouiller | Aucune commande unlock n'existe | À tester |
| EX-09 | Une commande rejouée ou mal signée est refusée | Rejeu avec MQTTX | À tester |
| EX-10 | Aucun secret n'est dans le code source | Relecture du dépôt | À tester |
| EX-11 | Toute modification du journal est détectée | Modifier une ligne puis vérifier | À tester |
| EX-12 | Une alerte signale l'humidité supérieure à 60 % | Souffler sur le capteur | À tester |
| EX-13 | La disparition du coffre est signalée | Couper l'alimentation : HORS_LIGNE | À tester |
