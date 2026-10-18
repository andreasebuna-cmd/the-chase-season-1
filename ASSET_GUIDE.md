# Guide des illustrations — THE CHASE Season 1

Les images sont facultatives pour tester le gameplay. Le jeu actuel conserve un décor abstrait de secours si un fichier image n'est pas encore présent.

## Convention de nommage
- Utiliser des noms minuscules, sans accents ni espaces.
- Format conseillé : WebP ou JPG, format paysage 16:9, 1920×1080.
- Nom : `arc01_the_first_glitch.webp`.
- Garder les fichiers dans `assets/scenes/`.
- Ne pas réutiliser la même image pour des scènes qui ont une composition différente.

## Liste initiale de scènes à produire
| Nom de fichier | Contenu visuel demandé |
|---|---|
| `arc01_the_first_glitch.webp` | Salle de contrôle VANTEX à 02:17, écrans remplis de lignes corrompues, lumière rouge d'alerte, aucun texte lisible. |
| `arc01_digital_collapse.webp` | Vue large d'une salle de serveurs où plusieurs écrans s'éteignent en cascade, atmosphère réaliste et froide. |
| `arc01_vantex_alert.webp` | Gros plan d'un moniteur de sécurité affichant des alertes abstraites, reflet d'un opérateur inquiet. |
| `arc01_abandoned_headquarters.webp` | Couloir de bureaux VANTEX désert, câbles arrachés, éclairage d'urgence, portes entrouvertes. |
| `arc01_project_merge.webp` | Laboratoire secret, prototype humain-numérique au centre, câbles et écrans de diagnostic, ambiance de science-fiction réaliste. |
| `arc01_hacker_revealed.webp` | Silhouette humaine derrière une paroi de confinement opaque, lueur numérique subtile, aucune caractéristique faciale précise. |
| `arc02_worldwide_outage.webp` | Centre de supervision mondial, cartes réseau sombres et plusieurs régions déconnectées. |
| `arc03_area51_arrival.webp` | Complexe militaire isolé dans le désert du Nevada au crépuscule, entrée souterraine discrète. |
| `arc03_the_bullet.webp` | Grande sphère de confinement métallique au cœur d'une chambre souterraine, anneaux mécaniques et lumières d'état. |
| `arc03_containment_failure.webp` | Même chambre, voyants rouges, fissures lumineuses sur les écrans de contrôle, sans destruction gore. |
| `arc04_the_merge.webp` | Sujet vu de dos devant une machine de synchronisation, filaments lumineux reliant le corps à une interface numérique. |
| `arc05_network_ghosts.webp` | Espace numérique abstrait constitué de nœuds lumineux, fragments de silhouette qui se dispersent. |
| `arc06_final_approach.webp` | Immense salle de serveurs presque vide, une silhouette face à une forme numérique lointaine. |
| `arc06_hacker_phase1_clone.webp` | Clone numérique humanoïde au centre d'une arène, silhouette faite de fragments de données. |
| `arc06_hacker_phase2_horde.webp` | Arène numérique avec plusieurs silhouettes ennemies en arrière-plan, composition lisible et non gore. |
| `arc06_hacker_phase3_core.webp` | The Hacker au centre d'un noyau de synchronisation, arcs d'énergie et réseaux lumineux convergeant vers lui. |
| `arc06_ending_recontainment.webp` | Sphère de confinement stabilisée, lumière froide et équipe en silhouette derrière une vitre. |
| `arc06_ending_total_erasure.webp` | Noyau numérique qui se dissout en particules, salle silencieuse après l'arrêt du réseau. |
| `arc06_ending_they_are_doomed.webp` | Ville vue de nuit, réseau lumineux qui s'étend au-dessus des bâtiments, ambiance de menace persistante. |

## Intégration
Place les fichiers dans `assets/scenes/` en gardant exactement les noms du tableau. Les emplacements de scène sont déjà associés à ces noms dans index.html. Il suffit de déposer les fichiers dans ce dossier avec les noms exacts. Tant qu'un fichier manque, le décor abstrait de secours reste affiché.