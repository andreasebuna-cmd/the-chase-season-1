# Systèmes de gameplay implémentés — prototype 1

Cette version est une base jouable en cours d'extension, pas encore une campagne finale équilibrée.

## Ajouts
- Exploration contextuelle par événement avec trois éléments à inspecter, une seule fois chacun; 19 événements clés disposent désormais de hotspots uniques et d'indices propres à la scène.
- Dossier d'indices persistant, avec les indices liés à l'événement et conservés dans la sauvegarde.
- Énigmes contextuelles réparties sur les six arcs : archives VANTEX, PROJECT MERGE, transferts d'énergie, BLACK VAULT, protocoles de sécurité, calibration, relais et noyau de synchronisation.
- Quatre puzzles de routage interactifs : cartographier le réseau, neutraliser le premier nœud, rompre la liaison dans l'ordre sûr et tracer le dernier signal.
- Validation des réponses, erreurs enregistrées, et petite contre-mesure après plusieurs erreurs.
- Combat contextuel avec esquive, frappe, charge jusqu'à trois niveaux, onde d'énergie, frappe du noyau amplifiée par les charges et repli tactique.
- Arènes de combat animées distinctes pour le clone, la horde et la forme centrale de The Hacker; les indices récupérés peuvent neutraliser certaines capacités ennemies.
- Boss final avec une réserve partagée de 10 000 PV répartie en trois phases : clone, horde et The Hacker.
- PV, énergie, inventaire, indices, énigmes résolues, état des combats et conséquences sauvegardés localement.
- Un guide d'illustrations indiquant noms de fichiers et descriptions visuelles.

## Paramètres de prototype
Le document de conception spécifie 10 000 PV pour The Hacker, mais laisse certains chiffres d'équilibrage au choix de l'implémentation. Les PV joueur (100), énergie (100), ennemis standards (240 PV), dégâts, coûts et valeurs de riposte présents dans le prototype sont des paramètres provisoires, à équilibrer lors des tests.

## À compléter ensuite
- Étoffer encore les dialogues : 351 répliques sont désormais réparties sur les 50 événements, avec deux lignes contextuelles supplémentaires par événement. Certaines scènes restent trop courtes pour une campagne narrative de plusieurs heures.
- Remplacer progressivement les réponses textuelles par des interfaces dédiées (claviers, cartes de nœuds, panneaux de circuit) et des énigmes à plusieurs étapes.
- Ajouter des illustrations cinématiques dédiées aux événements; les arènes de boss utilisent pour l'instant des silhouettes et des formes générées en CSS, pas des illustrations originales.
- Développer davantage les ramifications entre les arcs, les dialogues alternatifs et les conséquences différées.
- Créer et déposer les images dans assets/scenes; les emplacements sont reliés mais les illustrations ne sont pas encore fournies.
- Tests de parcours complets, équilibrage, reprise d'une sauvegarde pendant chaque phase.
