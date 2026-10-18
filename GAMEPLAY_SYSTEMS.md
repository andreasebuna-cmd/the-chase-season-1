# Systèmes de gameplay implémentés — prototype 1

Cette version est une première couche jouable, pas encore une campagne finale équilibrée.

## Ajouts
- Exploration contextuelle par événement avec trois éléments à inspecter, une seule fois chacun.
- Dossier d'indices persistant, avec les indices liés à l'événement et conservés dans la sauvegarde.
- Énigmes textuelles pour les recherches corrompues, l'identification des cibles, les coordonnées de BLACK VAULT, le protocole de sécurité, la calibration, les nœuds réseau et le noyau de synchronisation.
- Validation des réponses, erreurs enregistrées, et petite contre-mesure après plusieurs erreurs.
- Combat contextuel avec esquive, frappe, charge, onde d'énergie, attaque du noyau et repli tactique.
- Boss de fin de jeu avec 10 000 PV conformément au cahier des charges.
- PV, énergie, inventaire, indices, énigmes résolues, état des combats et conséquences sauvegardés localement.
- Un guide d'illustrations indiquant noms de fichiers et descriptions visuelles.

## Paramètres de prototype
Le document de conception spécifie 10 000 PV pour The Hacker, mais laisse certains chiffres d'équilibrage au choix de l'implémentation. Les PV joueur (100), énergie (100), ennemis standards (240 PV), dégâts, coûts et valeurs de riposte présents dans le prototype sont des paramètres provisoires, à équilibrer lors des tests.

## À compléter ensuite
- Dialogue narratif spécifique et complet pour chacun des 49 événements.
- Énigmes avec interface dédiée (claviers, cartes de nœuds, panneaux de circuit) plutôt que seulement des réponses textuelles.
- Différencier précisément les trois phases du boss, ses clones, ses hordes, ses retraits temporaires et sa régénération.
- Conséquences scénaristiques individualisées et ramifications entre les arcs.
- Images effectivement intégrées dans chaque scène; voir ASSET_GUIDE.md.
- Tests de parcours complets, équilibrage, reprise d'une sauvegarde pendant chaque phase.
