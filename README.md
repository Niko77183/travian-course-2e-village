# Course au 2e village

Simulateur **Travian: Legends** : trouve l'ordre de constructions qui fait partir les 3 colons du 2e village le plus tôt possible.

Le moteur juge chaque action sur trois gains à la fois : les ressources qu'elle fait produire, les points de culture qu'elle rapporte et la récompense de la tâche qu'elle accomplit. Il compare des milliers de plans (3 ou 4 fêtes, héros en combat ou en production, cachettes supplémentaires…) et affiche le meilleur, heure par heure, en temps serveur.

## Utilisation

1. **Village** : peuple, vitesse, ouverture du serveur ; coller la page des champs du jeu (Ctrl+A, Ctrl+C) ; PC cumulés ; niveau de chaque bâtiment, exemplaires supplémentaires compris.
2. **Troupes et héros** : effectif total de chaque unité, héros, pillage, palier des quêtes quotidiennes.
3. **Options** : bonus +25 %, avec ou sans or, précision du calcul, puis « Lancer le calcul ».
4. **Résultat** : heure de départ des colons, meilleur plan de chaque scénario, planning complet.

La population et la production de céréales sont recalculées et comparées au collage : un écart signale une saisie à corriger.

Les simulations s'enregistrent dans un fichier et se rouvrent depuis l'application ; la dernière saisie est aussi gardée dans le navigateur.

## Données

Coûts, durées, production et points de culture viennent de la base de connaissances officielle de Travian: Legends ; les récompenses des tâches viennent du jeu lui-même, et la formule qui les relie au niveau du héros a été vérifiée sur 128 valeurs.

Travian enrobe ses nombres de marques bidirectionnelles invisibles et sépare les milliers par une espace insécable : le collage les retire avant la lecture.
