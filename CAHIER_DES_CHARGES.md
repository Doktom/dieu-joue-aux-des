# 🎲 Dieu Joue aux Dés — Cahier des charges (V1)

> *« Dieu ne joue pas aux dés »*, disait Einstein. Ici, si.

Simulateur contemplatif de civilisations. Le joueur est le démiurge : il règle les lois d'un monde, le lance, et regarde l'histoire s'écrire de l'An 1 à l'An 3000. Il peut rester spectateur ou intervenir.

## 1. Technique et déploiement
- Un seul fichier `index.html` (Canvas 2D + JavaScript, aucune dépendance).
- Données de jeu en JSON intégrées au fichier (techs, âges, gouvernements, traits, dogmes, espèces, événements).
- Sauvegarde / chargement de partie en fichier `.json`, plus une sauvegarde automatique dans le navigateur.
- Graine (seed) pour rejouer le même monde.
- Hébergement : dépôt GitHub public + GitHub Pages.

## 2. Monde et carte
- Grille de tuiles procédurale : océan, eaux peu profondes, plage, plaine, forêt, jungle, désert, steppe, collines, montagne, toundra, neige, rivières.
- Ressources rares : fer, chevaux, épices, or, bois précieux, poisson.
- Zoom (molette) et déplacement (glisser).
- Territoires colorés par civilisation, villes en sprites pixel qui évoluent avec l'âge.

## 3. Temps
- 1 tick = 1 an, de l'An 1 à l'An 3000.
- Vitesses : pause, ×1, ×4, ×16, ×60, ×200 (années par seconde).
- Frise chronologique avec les événements majeurs.
- Écran de fin : classement, records, statistiques, export de la chronique.

## 4. Civilisations
- 4 à 12 au départ ; nouvelles par sécession / guerre civile ; disparition possible.
- Villes avec population, territoire qui s'étend autour.
- 2 traits culturels parmi : guerrière, marchande, mystique, bâtisseuse, savante, expansionniste, isolationniste.
- Gouvernements : Tribu, Chefferie, Monarchie, Théocratie, Féodalité, République, Empire, Démocratie, Dictature, Technocratie. Changement par réforme ou révolution.
- Stabilité : baisse avec famine, défaite, malédiction, taille excessive → révolutions, sécessions.
- Âges : Tribal, Antiquité, Médiéval, Renaissance, Industriel, Moderne, Futur.

## 5. Économie
- Nourriture (croissance), production (armées, nouvelles villes), richesse (trésor, recherche, commerce).
- Commerce entre civilisations en contact et en paix.
- Famines, âges d'or, crises.

## 6. Technologie
- ~40 techs réparties par âge, avec bonus concrets. Passage d'âge quand assez de techs de l'âge sont acquises.
- Découvertes fortuites.

## 7. Religions
- Naissance spontanée (prophète), dogmes (pacifisme, prosélytisme, guerre sainte, ascétisme, animal sacré, savoir sacré…).
- Propagation ville à ville, schismes, religion d'État, théocraties.

## 8. Diplomatie et guerre
- Relations de -100 à +100 : alliance, paix, rivalité, guerre, vassalité.
- Armées en sprites qui marchent vers les villes ennemies, sièges, conquêtes, traités de paix.

## 9. Faune (réaliste)
- Gibier : cerf, bison, sanglier, chevaux sauvages, aurochs.
- Prédateurs : loup, ours, lion, tigre.
- Bêtes légendaires (rares, très puissantes) : mammouth laineux, smilodon, ours des cavernes.
- Stats par espèce : puissance, agressivité, reproduction.
- Interactions : chasse (nourriture), attaques de villages, surchasse → extinction, domestication (chevaux → cavalerie, aurochs → élevage), animaux sacrés, grandes chasses (prestige).

## 10. Rôle du dieu
- Paramètres initiaux : graine, taille du monde, part d'eau, nombre de civilisations.
- Lois du monde (modifiables en direct) : fertilité, agressivité des peuples, fréquence des catastrophes, rythme du progrès, densité / agressivité / puissance de la faune.
- Pouvoirs divins (clic sur la carte) : séisme, sécheresse, peste, déluge, récolte miraculeuse, prophète, héros, bénédiction, malédiction, invocation d'animaux.

## 11. Interface (français)
- Carte au centre ; chronique à gauche ; civilisations et fiche détaillée à droite ; barre de temps et frise en bas ; palette des pouvoirs divins.
- Fenêtre de statistiques (courbes population / puissance / richesse).

## 12. Style
- Pixel art moderne : rendu net, palette riche, relief ombré, eau animée, interface sombre à panneaux translucides.

## Hors V1 (pistes)
- Monde sans fin, cartes en provinces, éditeur de terrain, légendes de personnages détaillées, export de l'histoire en page illustrée.
