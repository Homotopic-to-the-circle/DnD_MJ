# MJ · Feuille de Perso

Application du MJ pour la campagne : joueurs et codes, catalogue d'objets, envois, rencontres (monstres, PV, initiative).

**Application MJ : https://homotopic-to-the-circle.github.io/DnD_MJ/**

App des joueurs : https://homotopic-to-the-circle.github.io/DnD_Character/

## Installer

Ouvre l'adresse dans Chrome (Android) → menu ⋮ → **Installer l'application**. Le code MJ est demandé au premier lancement.

Pour récupérer une nouvelle version : onglet **Campagne** → **Mettre à jour l'application**.

Ce dépôt est généré à partir du même code que l'app des joueurs ; ne pas le modifier à la main.

---

# Aide-mémoire création de persos (version complète, MJ)

Tout ce qui n'est pas automatique entre AideDD et la feuille de perso, à vérifier à chaque création et à chaque montée de niveau. La version courte pour les joueurs est dans le [README de l'app joueur](https://github.com/Homotopic-to-the-circle/DnD_Character#bon-à-savoir-à-lire-une-fois).

## Créer et importer

1. Crée le perso sur le créateur AideDD jusqu'au bout, puis **Terminé !** pour afficher la fiche finale.
2. Lance le favori « Export AideDD » : le résumé doit dire **XML OK**. Sans ça, la montée de niveau sera impossible plus tard.
3. **Vérifie le nom** : AideDD garde parfois le nom du perso précédent (cas « Merlin »). Corrige-le dans AideDD avant l'export, ou dans l'app (onglet Fiche, mode crayon).
4. **iPhone** : importe dans l'app installée sur l'écran d'accueil, pas dans Safari. Les deux ne partagent pas leurs données.
5. Relie le perso au cloud avec le code du MJ (Fiche → Sauvegarde en ligne). Sans code, la fiche n'existe que sur ce téléphone.
6. **Les scores de caractéristiques ne se modifient pas dans l'app** : ils doivent être justes dans AideDD.

## Ce qu'AideDD n'applique pas

AideDD ne compte pas certains dons. Corrige à la main, une fois par perso, en mode crayon :

| Cas | Où corriger | Comment |
| --- | --- | --- |
| Don **Doué** (3 compétences) | Caracs | Touche le losange de chaque compétence choisie. Le bonus et la Perception passive s'ajustent. |
| Don **Résilient** (une sauvegarde) | Caracs | Touche le losange du jet de sauvegarde choisi. L'export ne dit pas lequel. |
| **Expertise** non comptée | Caracs | Touche deux fois le losange (rien → maîtrise → expertise en double losange → rien). L'expertise déjà comptée par AideDD s'affiche d'office. |
| Initiative, Vitesse, PV max qui ne collent pas (don Vigilant, Mobile, Robuste…) | Combat | Tape la bonne valeur. Champ vide = valeur d'AideDD. Le PV max sert aussi au Repos long. |
| CA différente (bouclier, objet magique…) | Combat | Tape la bonne CA. Champ vide = valeur d'AideDD. |
| Avantage à un jet de sauvegarde | Caracs | Bouton « av. » à côté du jet. |

Les maîtrises de compétences restent manuelles exprès : une maîtrise ajoutée à tort serait pire qu'un clic.

## Armes

Les armes d'AideDD ont les bons calculs (styles de combat compris). Celles ajoutées depuis la liste sont calculées par l'app, avec des limites.

**Armes ajoutées depuis la liste** (Combat, mode crayon, ou bouton « + aux attaques » dans le Sac) :

- Caractéristique : Finesse → la meilleure entre FOR et DEX ; arme à Munitions → DEX ; sinon FOR (armes de lancer comprises).
- Maîtrise selon les règles 2024 : armes courantes pour tous ; armes de guerre pour Barbare, Guerrier, Paladin, Rôdeur ; Roublard (Finesse ou Légère) ; Moine (Légère) ; Clerc Ordre divin (Protecteur) ; Druide Ordre primitif (Gardien) ; Barde Collège de la Vaillance dès le niveau 3 ; don Formation aux armes de guerre.
- Maîtrise non détectée ou erronée : losange **Maîtrise** sous l'arme.

**À corriger à la main sur ces armes-là** :

| Cas | Correction |
| --- | --- |
| Style Archerie | +2 à l'attaque des armes à distance |
| Style Duel | +2 aux dégâts (une seule arme en main) |
| Arme magique +1, +2, +3 | Attaque et dégâts |
| Moine : arme de moine avec DEX ou dé d'Arts martiaux | Attaque et dégâts (l'app prend la FOR hors Finesse) |
| Occultiste, Pacte de la lame | Maîtrise + CHA à la place de FOR/DEX |
| Polyvalente à deux mains | Dégâts à deux mains dans la note |

Une arme retouchée à la main garde ta saisie pour toujours : elle n'est plus recalculée aux montées de niveau, à toi de la suivre.

**Autres règles** :

- Arme d'AideDD supprimée (✕) : elle ne revient pas aux montées suivantes. Pour la récupérer, ajoute-la depuis la liste.
- Arme d'AideDD renommée (« Épée longue +1 ») : elle garde ton nom et reste mise à jour.
- Choisir une autre arme dans la liste sur une ligne d'AideDD la remplace définitivement.
- Les attaques et le Sac sont indépendants : supprimer d'un côté ne touche jamais l'autre.

## Sorts

- **Ajouter un sort** (Sorts, mode crayon) : tape le début du nom et choisis-le. Niveau, incantation, portée, Concentration, Rituel et Matériel se remplissent. Un nom libre reste possible, à compléter toi-même.
- Les sorts ajoutés dans l'app sont gardés aux montées de niveau. Un sort d'AideDD que tu retires reste retiré.
- Un sort qu'AideDD ne donne plus au nouveau niveau disparaît, sauf s'il a été ajouté à la main.
- **Sorts préparés** : losange à gauche du sort, en mode crayon. Les non préparés passent en fin de liste.
- **Emplacements** : réglés par AideDD ; modifiables en mode crayon. Occultiste : la Magie de pacte reste cliquable dans ses capacités.
- DD et attaque de sort : ceux d'AideDD, non modifiables dans l'app.
- Pas de note par sort (exprès) : utilise les notes du perso.

## Capacités, ressources et objets

- Les capacités avec un nombre d'utilisations (« Second souffle (2) ») deviennent des cases à cocher. Une capacité sans nombre : bouton **Cases** en mode crayon pour en faire une ressource.
- Le maximum d'une ressource se corrige en mode crayon ; une ressource maison s'ajoute en bas de la liste.
- Repos long : PV au max, toutes les cases décochées, épuisement −1, concentration retirée. Le repos court n'existe pas : décoche à la main.
- Objets du Sac : tape le début du nom et choisis dans la liste (équipement + objets magiques) pour avoir le bon lien. Les quantités se règlent avec − / +.
- Harmonisation : 3 objets au maximum, gérée par le MJ (✦) pour les objets qu'il envoie.
- Notes par ligne : sur les capacités, ressources, traits et dons, en mode crayon.

## Monter de niveau et revenir en arrière

1. Onglet Fiche → **Télécharger le .xml**. Il contient les objets harmonisés.
2. Sur le créateur AideDD : importe ce .xml, monte de niveau, puis **Terminé !**
3. Relance le favori « Export AideDD » et colle le résultat dans **Mettre à jour le personnage**.
4. L'app prévient si le nom ou la classe diffèrent, ou si le niveau baisse : c'est probablement le mauvais export.

Ce que la mise à jour fait :

- Garde cases cochées, notes, sorts ajoutés, objets, maîtrises cochées et valeurs corrigées à la main.
- Reprend les nouvelles valeurs d'AideDD pour les armes non retouchées, recalcule les armes ajoutées depuis la liste, ajoute les nouvelles armes.
- Remet les PV au nouveau maximum s'ils étaient au maximum.
- **Refais les corrections de la section « Ce qu'AideDD n'applique pas »** si un nouveau don les concerne (nouveau Doué, Résilient…).

**Revenir à la version précédente** (onglet Fiche) annule la dernière mise à jour : niveau, stats et armes reviennent à l'état d'avant, sauf ce que tu as retouché à la main depuis.

## Ce que l'app ne gère pas

- **Multiclasse** : non prévu, la maîtrise des armes ne regarde que la classe principale.
- **Effets temporaires** (Rage, sorts de buff, bénédiction) : rien ne s'ajoute automatiquement aux jets. Les états (Empoisonné, À terre…) sont affichés, sans effet sur les calculs.
- **Jets de concentration** : l'app rappelle d'en faire un après des dégâts, le jet reste à faire.
- **Repos court** : pas de bouton, décoche les cases à la main.
- **Dés de vie et épuisement** : compteurs à gérer à la main.
- **Initiative des monstres** (app MJ) : pas dans la liste AideDD, à entrer soi-même. Les PV moyens, eux, se remplissent.
