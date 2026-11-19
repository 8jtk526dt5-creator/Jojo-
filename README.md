# Jojo

Jeu de combat en pixel art, en un seul fichier HTML, sans dépendance. Garde, esquive, enchaîne les coups, invoque ton Stand et déclenche ta pose ultime contre trois adversaires.

## Jouer

Ouvre `index.html` dans un navigateur (iPhone, Android ou ordinateur). Avec GitHub Pages, le jeu est jouable directement depuis le lien du dépôt. Sur iPhone, le jeu se joue aussi en horizontal.

## Difficulté et vitesse

Sur l'écran de sélection, choisis FACILE, NORMAL ou DIFFICILE : cela change la vie, les dégâts, l'agressivité, la garde et l'usage des pouvoirs de l'adversaire. Le jeu tourne à 80 % de sa vitesse d'origine, et l'arène s'adapte à la hauteur de l'écran pour que tous les boutons restent visibles.

## Mobilité et choix de l'adversaire

Déplacement plus rapide, saut plus haut, **double saut** (appuie une seconde fois sur SAUT en l'air) et esquive plus courte. Après un coup, l'esquive peut annuler la fin de l'animation. Sur l'écran de sélection, l'onglet ADVERSAIRE te laisse choisir qui tu affrontes en premier ; ALÉATOIRE rétablit le tirage au sort. Les deux manches suivantes restent aléatoires.

## Mode en ligne

Bouton EN LIGNE sur l'écran de sélection : un joueur crée une partie (code à 4 caractères), l'autre entre le code. Duel en deux manches gagnantes, chacun avec le combattant qu'il a choisi. Le mode en ligne utilise la salle partagée de la page publiée sur Claude (capacité `room`) : il ne marche pas depuis ce dépôt ou un fichier local, et les deux joueurs doivent pouvoir ouvrir la page (connectés, invités).

## Style des personnages
Chaque combattant a son look : bandeaux, lunettes, casquettes, chapeaux, couronnes, boucles d'oreille, épaulières, gants, emblèmes, chaînes, capes, cols, genouillères, tatouages et lumière de contour.

## Orientation
Le jeu s'adapte à l'orientation du téléphone : en horizontal tu joues en horizontal, en vertical tu joues en vertical.

## Arène

L'arène fait deux fois la largeur de l'écran : la caméra suit le combat et le décor défile quand vous vous déplacez.

## Commandes

| Action | Tactile | Clavier |
| --- | --- | --- |
| Bouger | ◀ ▶ | Flèches ou A / D |
| Se baisser (tenir) : esquive les coups hauts et les projectiles, pas les balayages ni les coups lourds | ▼ | Bas ou C |
| Sauter | SAUT | Haut, W ou Espace |
| Attaque normale (appuie plusieurs fois pour enchaîner jab, crochet, coup de pied). Avec le Stand activé, c'est le Stand qui frappe, avec une portée plus longue | COUP | J |
| Rafale du Stand (coûte de la jauge bleue, qui se recharge) | RAFALE | K |
| Attaque spéciale propre au combattant (temps de recharge) | SPÉCIAL | I |
| Garde (tenir appuyé, réduit fortement les dégâts de face) | GARDE | S ou Maj |
| Esquive (courte invincibilité) | ESQUIVE | U ou E |
| Ultime (barre orange pleine) | ULTIME | L |
| Activer / désactiver le Stand (il reste sorti, même après une rafale, jusqu'à ce que tu rappuies : dégâts +30 %, jauge bleue qui se recharge plus lentement) | STAND | Q ou O |

## Combattants

30 combattants originaux, chacun avec son Stand, une attaque spéciale et un pouvoir ultime. Choisis le tien dans la grille : tu affrontes ensuite trois adversaires tirés au sort, dans trois décors. Les adversaires utilisent eux aussi leur spécial et leur ultime.

| # | Combattant | Stand | Spécial | Ultime | Effet de l'ultime |
| --- | --- | --- | --- | --- | --- |
| 1 | CRONOS | TIC-TAC | TROIS COUTEAUX (trois couteaux à la suite, figés pendant l'arrêt du temps) | LE TEMPS S'ARRÊTE | Arrête le temps 3,6 s : l'adversaire est figé, tes coups font double et tombent d'un coup à la reprise. |
| 2 | MIRELLA | ROSE NOIRE | PÉTALES NOIRS (quatre pétales à tête chercheuse) | RAYON ÉCARLATE | Un rayon écarlate traverse l'arène. Saute pour l'éviter. |
| 3 | KAÏTO VANCE | HORLOGE VIDE | RETOUR EN ARRIÈRE (remonte le temps : récupère la vie perdue ces 4 dernières secondes) | LE TEMPS EFFACÉ | Efface 1,6 s de temps : l'adversaire ne voit rien venir et tes coups font double. |
| 4 | LUNA FERRO | SABLIER | SABLIER FIGÉ (ralentit l'adversaire pendant 3,5 s) | RETOUR EN ARRIÈRE | Remonte le temps : tu retrouves la vie que tu avais il y a 4 secondes et repousses l'adversaire. |
| 5 | DOC MARROW | SUTURE | POINT DE SUTURE (soigne une grosse part de vie) | CHIRURGIE ÉCLAIR | Recoud tes blessures : tu regagnes environ 40 % de ta vie et ta jauge de Stand se remplit. |
| 6 | BRUTUS KANE | GRANITE | SECOUSSE (onde de choc au sol qui projette en l'air) | POING DE GRANIT | Fonce et écrase l'adversaire d'un poing de granit (40 dégâts, grosse projection). |
| 7 | NOX VESPER | ÉCLIPSE | PAS D'OMBRE (disparaît, réapparaît dans le dos et frappe) | ÉCLIPSE TOTALE | Disparaît et réapparaît dans ton dos : trois coups puis une projection. |
| 8 | DOCTEUR ORAGE | FOUDRE MÈRE | DOUBLE FOUDRE (deux éclairs tombent sur l'adversaire) | TEMPÊTE | Trois coups de foudre tombent successivement sur l'adversaire. Il doit bouger ou sauter. |
| 9 | ZÉPHYRINE | CYCLONE | RAFALE (vent géant qui repousse très loin) | TORNADE RASANTE | Une tornade rase le sol et projette l'adversaire. Saute par-dessus. |
| 10 | IGNACE BRAISE | HAUT-FOURNEAU | BOULET DE FEU (boule de feu en arc qui explose au sol) | MUR DE FLAMMES | Un mur de flammes avance au ras du sol. Saute pour l'éviter. |
| 11 | GLACIA NORD | HIVER ÉTERNEL | SOUFFLE GELÉ (éclat de glace qui gèle l'adversaire) | GEL ÉTERNEL | Fige l'adversaire dans la glace 2,4 s. Il ne peut plus bouger, il est projeté au dégel. |
| 12 | VOLT KÉROS | ÉTINCELLE | ÉTINCELLE (étincelle qui zigzague en vol) | DÉCHARGE | Paralyse l'adversaire 2,2 s d'une décharge électrique : il ne peut plus bouger. |
| 13 | ORCHIDÉE LAM | VENIN D'ORCHIDÉE | SPORES (piège de spores qui empoisonne et ralentit) | VENIN LENT | Empoisonne l'adversaire 7 s : il perd de la vie en continu et tu en récupères une partie. |
| 14 | SANGUIN REX | SOIF ROUGE | MORSURE ROUGE (bondit et mord : te rend la vie volée) | SAIGNÉE | Un rayon sombre qui te rend 80 % des dégâts infligés en vie. |
| 15 | PERLE ABYSSE | MARÉE NOIRE | MARÉE NOIRE (vague lente au sol qui ralentit) | EAU LOURDE | Ralentit l'adversaire de moitié pendant 7 s : il bouge et frappe au ralenti. |
| 16 | GRAVIT HELM | POIDS MORT | POIDS MORT (écrase l'adversaire au sol et le ralentit) | GRAVITÉ ÉCRASANTE | Plaque l'adversaire au sol : 26 dégâts et près de 2 s à terre pour le frapper. |
| 17 | ARGUS PRISM | MIROIR BRISÉ | MIROIR BRISÉ (renvoie les coups reçus pendant 1,4 s) | RENVOI | Un miroir te protège 4 s : les coups reçus de face sont renvoyés à l'adversaire. |
| 18 | TURBO LÉO | VITESSE LIMITE | VITESSE LIMITE (accélère fortement pendant 4,5 s) | ACCÉLÉRATION | Accélère 6,5 s : tu bouges et frappes une fois et demie plus vite. |
| 19 | BASTIEN MURE | MURAILLE | MURAILLE (mur invulnérable pendant 1,1 s) | FORTERESSE | Une muraille t'entoure 3,2 s : tu es invincible et ta jauge de Stand se remplit. |
| 20 | STELLA POLARIS | ÉTOILE FILANTE | ÉTOILES FILANTES (deux étoiles tombent du ciel) | PLUIE D'ÉTOILES | Six étoiles filantes à tête chercheuse. Esquive pour en éviter. |
| 21 | OSSIAN GRAVE | SQUELETTE ROI | OS BOOMERANG (os qui touche à l'aller et au retour) | RAFALE DES MORTS | Se jette sur l'adversaire et le martèle d'une longue rafale de poings fantômes. |
| 22 | MAGNUS PÔLE | AIMANT | ATTRACTION (attire l'adversaire contre toi et frappe) | ATTRACTION FATALE | Attire l'adversaire contre toi puis le martèle d'une rafale. |
| 23 | AYAME SORA | LAME DU VENT | COUPE-VENT (traverse l'adversaire d'un coup de lame) | MILLE LAMES | Apparaît dans ton dos et enchaîne quatre coups de lame avant de projeter. |
| 24 | DJANGO CALIBRE | SIX COUPS | SIX COUPS (six balles en rafale) | SIX COUPS | Six balles dorées à tête chercheuse tirées coup sur coup. |
| 25 | FRIDA PUMA | COBRA ROYAL | CRACHAT DE COBRA (venin qui empoisonne) | MORSURE ROYALE | Un venin plus violent : 5 s de poison, plus de dégâts par seconde. |
| 26 | BARON SABLE | DÉSERT VIVANT | SABLES MOUVANTS (piège sous les pieds de l'adversaire) | MUR DE SABLE | Un mur de sable rase le sol et projette l'adversaire. Saute par-dessus. |
| 27 | HELIOS AURÉ | SOLEIL FINAL | SOLEIL (grosse sphère lente qui poursuit) | RAYON SOLAIRE | Un énorme rayon doré (42 dégâts). Saute pour l'éviter. |
| 28 | NÉMÉSIS NEUF | RÉVERBÉRATION | ONDE DE CHOC (onde qui grandit et traverse) | ÉCHO MORTEL | Un écho te protège 5 s et renvoie 120 % des dégâts reçus de face. |
| 29 | PIXEL RIVA | GLITCH | ÉCHANGE (échange les places et étourdit) | ERREUR FATALE | Se téléporte dans ton dos et frappe deux fois avant de projeter. |
| 30 | KONRAD IRON | TITAN | MARTEAU DU TITAN (bondit et écrase le sol) | POING DU TITAN | Se rue sur l'adversaire et l'écrase d'un poing géant (44 dégâts). |

Chaque Stand a sa propre silhouette (corpulence, tête, torse, mains) et ses propres accessoires : ailes, queue de serpent, cape, tentacules, engrenages, éclairs, chaînes, flammes, cristaux, anneaux.

Tous les personnages et les Stands sont originaux.

## Graphismes 2.5D
Mélange 3D/2D : sol en perspective (lignes de fuite néon), brume d'horizon, rayons de lumière en parallaxe, ombres douces et projetées (selon la hauteur), volume sur les membres (ombre, demi-teinte, lumière, éclat), zoom caméra dynamique selon la distance et "punch" sur les coups.
