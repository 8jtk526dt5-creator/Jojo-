# Jojo

Jeu de combat en pixel art, en un seul fichier HTML, sans dépendance. Garde, esquive, enchaîne les coups, invoque ton Stand et déclenche ta pose ultime contre trois adversaires.

## Jouer

Ouvre `index.html` dans un navigateur (iPhone, Android ou ordinateur). Avec GitHub Pages, le jeu est jouable directement depuis le lien du dépôt. Sur iPhone, le jeu se joue aussi en horizontal.

## Difficulté et vitesse

Sur l'écran de sélection, choisis FACILE, NORMAL ou DIFFICILE : cela change la vie, les dégâts, l'agressivité, la garde et l'usage des pouvoirs de l'adversaire. Le jeu tourne à 80 % de sa vitesse d'origine, et l'arène s'adapte à la hauteur de l'écran pour que tous les boutons restent visibles.

## Mobilité et choix de l'adversaire

Déplacement plus rapide, saut plus haut, **double saut** (appuie une seconde fois sur SAUT en l'air) et esquive plus courte. Après un coup, l'esquive peut annuler la fin de l'animation. Sur l'écran de sélection, l'onglet ADVERSAIRE te laisse choisir qui tu affrontes en premier ; ALÉATOIRE rétablit le tirage au sort. Les deux manches suivantes restent aléatoires.

## Commandes

| Action | Tactile | Clavier |
| --- | --- | --- |
| Bouger | ◀ ▶ | Flèches ou A / D |
| Sauter | SAUT | Haut, W ou Espace |
| Attaque normale (appuie plusieurs fois pour enchaîner jab, crochet, coup de pied). Avec le Stand activé, c'est le Stand qui frappe, avec une portée plus longue | COUP | J |
| Rafale du Stand (coûte de la jauge bleue, qui se recharge) | RAFALE | K |
| Attaque spéciale propre au combattant (temps de recharge) | SPÉCIAL | I |
| Garde (tenir appuyé, réduit fortement les dégâts de face) | GARDE | S ou Maj |
| Esquive (courte invincibilité) | ESQUIVE | U ou E |
| Ultime (barre orange pleine) | ULTIME | L |
| Activer / désactiver le Stand (Stand sorti en permanence : dégâts +30 %, mais la jauge bleue se vide doucement) | STAND | Q ou O |

## Combattants

30 combattants originaux, chacun avec son Stand, une attaque spéciale et un pouvoir ultime. Choisis le tien dans la grille : tu affrontes ensuite trois adversaires tirés au sort, dans trois décors. Les adversaires utilisent eux aussi leur spécial et leur ultime.

| # | Combattant | Stand | Spécial | Ultime | Effet de l'ultime |
| --- | --- | --- | --- | --- | --- |
| 1 | CRONOS | TIC-TAC | COUTEAU (projectile rapide) | LE TEMPS S'ARRÊTE | Arrête le temps 3,6 s : l'adversaire est figé, tes coups font double et tombent d'un coup à la reprise. |
| 2 | MIRELLA | ROSE NOIRE | TROIS ÉPINES (trois projectiles en éventail) | RAYON ÉCARLATE | Un rayon écarlate traverse l'arène. Saute pour l'éviter. |
| 3 | KAÏTO VANCE | HORLOGE VIDE | PAS EFFACÉ (téléportation dans le dos de l'adversaire) | LE TEMPS EFFACÉ | Efface 1,6 s de temps : l'adversaire ne voit rien venir et tes coups font double. |
| 4 | LUNA FERRO | SABLIER | GOUTTE DE SABLE (soigne un peu) | RETOUR EN ARRIÈRE | Remonte le temps : tu retrouves la vie que tu avais il y a 4 secondes et repousses l'adversaire. |
| 5 | DOC MARROW | SUTURE | POINT DE SUTURE (soigne un peu) | CHIRURGIE ÉCLAIR | Recoud tes blessures : tu regagnes environ 40 % de ta vie et ta jauge de Stand se remplit. |
| 6 | BRUTUS KANE | GRANITE | CHARGE DE GRANIT (charge en avant) | POING DE GRANIT | Fonce et écrase l'adversaire d'un poing de granit (40 dégâts, grosse projection). |
| 7 | NOX VESPER | ÉCLIPSE | PAS D'OMBRE (téléportation dans le dos de l'adversaire) | ÉCLIPSE TOTALE | Disparaît et réapparaît dans ton dos : trois coups puis une projection. |
| 8 | DOCTEUR ORAGE | FOUDRE MÈRE | BOULE DE FOUDRE (boule d'énergie) | TEMPÊTE | Trois coups de foudre tombent successivement sur l'adversaire. Il doit bouger ou sauter. |
| 9 | ZÉPHYRINE | CYCLONE | LAMES DE VENT (trois projectiles en éventail) | TORNADE RASANTE | Une tornade rase le sol et projette l'adversaire. Saute par-dessus. |
| 10 | IGNACE BRAISE | HAUT-FOURNEAU | BOULET DE FEU (projectile en arc qui explose au sol) | MUR DE FLAMMES | Un mur de flammes avance au ras du sol. Saute pour l'éviter. |
| 11 | GLACIA NORD | HIVER ÉTERNEL | GLAÇON (projectile rapide) | GEL ÉTERNEL | Fige l'adversaire dans la glace 2,4 s. Il ne peut plus bouger, il est projeté au dégel. |
| 12 | VOLT KÉROS | ÉTINCELLE | ÉTINCELLE (boule d'énergie) | DÉCHARGE | Paralyse l'adversaire 2,2 s d'une décharge électrique : il ne peut plus bouger. |
| 13 | ORCHIDÉE LAM | VENIN D'ORCHIDÉE | SPORE VÉNÉNEUSE (piège posé au sol) | VENIN LENT | Empoisonne l'adversaire 7 s : il perd de la vie en continu et tu en récupères une partie. |
| 14 | SANGUIN REX | SOIF ROUGE | GOUTTES DE SANG (boule d'énergie) | SAIGNÉE | Un rayon sombre qui te rend 80 % des dégâts infligés en vie. |
| 15 | PERLE ABYSSE | MARÉE NOIRE | BULLE D'EAU (projectile en arc qui explose au sol) | EAU LOURDE | Ralentit l'adversaire de moitié pendant 7 s : il bouge et frappe au ralenti. |
| 16 | GRAVIT HELM | POIDS MORT | PIÈGE LOURD (piège posé au sol) | GRAVITÉ ÉCRASANTE | Plaque l'adversaire au sol : 26 dégâts et près de 2 s à terre pour le frapper. |
| 17 | ARGUS PRISM | MIROIR BRISÉ | ÉCLAT DE MIROIR (projectile rapide) | RENVOI | Un miroir te protège 4 s : les coups reçus de face sont renvoyés à l'adversaire. |
| 18 | TURBO LÉO | VITESSE LIMITE | CHARGE TURBO (charge en avant) | ACCÉLÉRATION | Accélère 6,5 s : tu bouges et frappes une fois et demie plus vite. |
| 19 | BASTIEN MURE | MURAILLE | COUP MONTANT (coup montant) | FORTERESSE | Une muraille t'entoure 3,2 s : tu es invincible et ta jauge de Stand se remplit. |
| 20 | STELLA POLARIS | ÉTOILE FILANTE | ÉTOILES (trois projectiles en éventail) | PLUIE D'ÉTOILES | Six étoiles filantes à tête chercheuse. Esquive pour en éviter. |
| 21 | OSSIAN GRAVE | SQUELETTE ROI | OS LANCÉ (projectile rapide) | RAFALE DES MORTS | Se jette sur l'adversaire et le martèle d'une longue rafale de poings fantômes. |
| 22 | MAGNUS PÔLE | AIMANT | CROCHET MAGNÉTIQUE (coup montant) | ATTRACTION FATALE | Attire l'adversaire contre toi puis le martèle d'une rafale. |
| 23 | AYAME SORA | LAME DU VENT | TROIS LAMES (trois projectiles en éventail) | MILLE LAMES | Apparaît dans ton dos et enchaîne quatre coups de lame avant de projeter. |
| 24 | DJANGO CALIBRE | SIX COUPS | TIR RAPIDE (projectile rapide) | SIX COUPS | Six balles dorées à tête chercheuse tirées coup sur coup. |
| 25 | FRIDA PUMA | COBRA ROYAL | SERPENT EN EMBUSCADE (piège posé au sol) | MORSURE ROYALE | Un venin plus violent : 5 s de poison, plus de dégâts par seconde. |
| 26 | BARON SABLE | DÉSERT VIVANT | BOULE DE SABLE (projectile en arc qui explose au sol) | MUR DE SABLE | Un mur de sable rase le sol et projette l'adversaire. Saute par-dessus. |
| 27 | HELIOS AURÉ | SOLEIL FINAL | SPHÈRE SOLAIRE (boule d'énergie) | RAYON SOLAIRE | Un énorme rayon doré (42 dégâts). Saute pour l'éviter. |
| 28 | NÉMÉSIS NEUF | RÉVERBÉRATION | ÉCHO (téléportation dans le dos de l'adversaire) | ÉCHO MORTEL | Un écho te protège 5 s et renvoie 120 % des dégâts reçus de face. |
| 29 | PIXEL RIVA | GLITCH | SAUT DE GLITCH (téléportation dans le dos de l'adversaire) | ERREUR FATALE | Se téléporte dans ton dos et frappe deux fois avant de projeter. |
| 30 | KONRAD IRON | TITAN | UPPERCUT DU TITAN (coup montant) | POING DU TITAN | Se rue sur l'adversaire et l'écrase d'un poing géant (44 dégâts). |

Tous les personnages et les Stands sont originaux.
