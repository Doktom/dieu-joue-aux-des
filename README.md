# 🎲 Dieu Joue aux Dés

> *« Dieu ne joue pas aux dés »*, disait Einstein. Ici, si.

Simulateur contemplatif de civilisations en pixel art. Tu es le démiurge : règle les lois du monde, lance les dés, et regarde l'histoire s'écrire de l'An 1 à l'An 3000. Empires, schismes, guerres, pestes, révolutions, mammouths et smilodons.

**▶ Jouer : https://doktom.github.io/dieu-joue-aux-des/**

## Contrôles
- **Glisser** : déplacer la carte · **Molette** : zoom
- **Espace** : pause · **1-5** : vitesse (×1 à ×200 ans/seconde)
- **Pouvoirs divins** : choisir un pouvoir puis cliquer sur la carte · **Échap** : annuler
- **⚖ Lois** : modifier fertilité, agressivité, catastrophes, progrès et faune en direct
- **💾 / 📂** : sauvegarder / charger une partie (fichier JSON)

## Technique
Un seul fichier `index.html`, sans dépendance. Toutes les données du jeu (techs, gouvernements, religions, espèces…) sont en JSON dans la balise `<script id="gamedata">` et peuvent être modifiées librement.

Voir [CAHIER_DES_CHARGES.md](CAHIER_DES_CHARGES.md).
