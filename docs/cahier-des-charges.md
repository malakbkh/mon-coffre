# Cahier des charges : pilulier intelligent

Chaque exigence est numérotée et reliée à un test de validation.
La colonne Résultat sera remplie à la fin du projet, avec une preuve (capture ou vidéo).

| ID | Exigence | Test de validation | Résultat |
|---|---|---|---|
| EX-01 | Un compartiment ne s'ouvre qu'avec un badge enrôlé | Badge valide ouvre, badge inconnu refusé | À tester |
| EX-02 | Un badge copié est détecté | Clone de l'UID : alarme | À tester |
| EX-03 | Trois échecs bloquent le pilulier 60 s | 3 mauvais badges | À tester |
| EX-04 | Un compartiment ne se déverrouille que pendant sa fenêtre de prise | Badge valide hors fenêtre : refus | À tester |
| EX-05 | Après une prise validée, le compartiment reste verrouillé jusqu'au lendemain | Second badge après la prise : refus | À tester |
| EX-06 | Un rappel (écran, LED, buzzer) se déclenche à l'heure prévue | Horaire réglé dans 2 minutes | À tester |
| EX-07 | Une prise manquée est signalée dans l'application | Laisser la fenêtre se terminer | À tester |
| EX-08 | Une ouverture forcée d'un compartiment verrouillé déclenche l'alarme | Ouvrir sans badge | À tester |
| EX-09 | Le programme n'est modifiable que par une commande signée et fraîche | Fausse signature, rejeu : refus | À tester |
| EX-10 | Le programme survit à une coupure d'électricité | Débrancher puis rebrancher | À tester |
| EX-11 | Le pilulier continue à fonctionner sans Wi-Fi | Couper le Wi-Fi pendant un rappel | À tester |
| EX-12 | Le journal des prises est infalsifiable | Modifier une ligne, vérifier | À tester |
| EX-13 | Une alerte signale une humidité supérieure à 60 % ou une température supérieure à 30 °C | Souffler sur le capteur | À tester |
| EX-14 | Aucun nom de médicament dans les messages envoyés au cloud | Lecture des messages avec MQTTX | À tester |
| EX-15 | Aucun secret dans le code source | Relecture du dépôt | À tester |
| EX-16 | La disparition du pilulier est signalée | Couper l'alimentation : HORS_LIGNE | À tester |
