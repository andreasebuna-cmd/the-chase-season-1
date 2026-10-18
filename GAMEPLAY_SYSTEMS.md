# Systèmes de gameplay implémentés — prototype 1

Cette version est une base jouable en cours d'extension, pas encore une campagne finale équilibrée.

## Ajouts
- Exploration contextuelle par événement avec trois éléments à inspecter, une seule fois chacun.
- Dossier d'indices persistant, avec les indices liés à l'événement et conservés dans la sauvegarde.
- Énigmes contextuelles réparties sur les six arcs : archives VANTEX, PROJECT MERGE, transferts d'énergie, BLACK VAULT, protocoles de sécurité, calibration, relais et noyau de synchronisation.
- Validation des réponses, erreurs enregistrées, et petite contre-mesure après plusieurs erreurs.
- Combat contextuel avec esquive, frappe, charge, onde d'énergie, attaque du noyau et repli tactique.
- Boss final avec une réserve partagée de 10 000 PV répartie en trois phases : clone, horde et The Hacker.
- PV, énergie, inventaire, indices, énigmes résolues, état des combats et conséquences sauvegardés localement.
- Un guide d'illustrations indiquant noms de fichiers et descriptions visuelles.

## Paramètres de prototype
Le document de conception spécifie 10 000 PV pour The Hacker, mais laisse certains chiffres d'équilibrage au choix de l'implémentation. Les PV joueur (100), énergie (100), ennemis standards (240 PV), dégâts, coûts et valeurs de riposte présents dans le prototype sont des paramètres provisoires, à équilibrer lors des tests.

## À compléter ensuite
- Étoffer les dialogues : les 50 événements ont désormais une première version scénarisée, mais plusieurs scènes doivent gagner en longueur et en interactions.
- Remplacer progressivement les réponses textuelles par des interfaces dédiées (claviers, cartes de nœuds, panneaux de circuit) et des énigmes à plusieurs étapes.
- Faire évoluer les phases du boss vers des animations et des patterns visuels distincts; les règles de combat sont déjà différenciées, mais les clones et les hordes ne sont pas encore représentés par des entités visuelles séparées.
- Développer davantage les ramifications entre les arcs, les dialogues alternatifs et les conséquences différées.
- Créer et déposer les images dans assets/scenes; les emplacements sont reliés mais les illustrations ne sont pas encore fournies.
- Tests de parcours complets, équilibrage, reprise d'une sauvegarde pendant chaque phase.
