<div align="center">
  <img src="images/banner.webp" width="660">

  # Exploirateurs de bruines

  Système de jeu pour [Encounter+](https://itunes.apple.com/us/app/encounter+/id1170693487?ls=1&mt=8)

  ![Version](https://img.shields.io/badge/version-1.0.0-blue)
  ![Encounter+](https://img.shields.io/badge/Encounter%2B-%E2%89%A5%205.1.0-green)
  ![Langues](https://img.shields.io/badge/langues-FR%20%7C%20EN-lightgrey)
</div>

> [!NOTE]
> Ce système ne contient pas de contenu du jeu (règles, ressources, images…). Il fournit la structure nécessaire au système : les fiches, les vues, le thème et les réglages. Le contenu doit être saisi manuellement dans la bibliothèque d'Encounter+. 

## Qu'est-ce que *Exploirateurs de bruines* ?

*Exploirateurs de bruines* est un jeu de rôle de fantasy post-apocalyptique créé par [Vivien Féasson](https://vivienfeasson.com) et publié par les éditions de L'Averse. Vous incarnez des enfants perdus dans la Ville, un labyrinthe sous une pluie qui ne s'arrête jamais, où rôdent les sirènes, des monstres qui prennent toutes les formes pour croquer les gaminots. Pour survivre, les enfants ont bâti des enclaves, et les Exploirateurs sont ceux qui osent en sortir pour aller fouiller les bruines, ces quartiers que personne n'a réussi à dompter, en quête de boustifaille et de trésors.

Le jeu a un ton enfantin, drôle et inquiétant à la fois. Les règles sont légères : six Résistances notées de 1 à 20 (on réussit un test en faisant au plus son score au D20), des classes, de l'usure sur l'équipement, et un Maître ou une Maîtresse Déluge (MD) qui bricole quand les règles ne suffisent plus. Il emprunte des idées à *The Black Hack* et à *Macchiato Monsters*, et il invite à recycler de vieux « donjons » pour inventer de nouvelles bruines. On le rapproche donc volontiers du mouvement OSR (*Old School Renaissance*).

## Installation

1. Téléchargez `edb.system` dans sa [dernière version](https://github.com/BriocheMasquee/edb/releases/latest).
2. Ouvrez le fichier avec Encounter+ (Réglages, puis Import). Le système s'installe et devient le système principal.

## Réglages du système

**Initiative.** Le jeu n'a pas de système d'initiative : les Exploirateurs agissent, puis MD réagit. Un système d'initiative est néanmoins implémenté dans l'application. Choisissez la formule dans les réglages du système (groupe « Initiative »), avant le début de la partie :

| Type d'initiative | Valeur |
|---|---|
| Selon la règle (par défaut) | Exploirateurs 1, bestioles 0. Le MD ajuste à la main. |
| Test « Tu m'attraperas pas ! » | Exploirateurs : 7 si le test réussit, 0 sinon. Bestiole : sa vitesse. |
| Valeur de vitesse | Bestiole : sa vitesse. Exploirateurs : celle d'un gaminot. |

Les vitesses vont de la tortue (1) au guépard (6).

**Cartes.** Le jeu compte les distances en cases. Dans les réglages de chaque carte, mettez l'échelle à `1` et l'unité à `sq` ou `cases`.

**Images.** Les réglages du système (groupe « Interface ») permettent de choisir l'image affichée dans les listes et dans le suivi de combat : icône, image ou jeton.

## Utiliser la fiche personnage

**Niveau** : laissé vide, il compte pour le niveau 1. Les compétences spécifiques à d'autres niveaux apparaissent automatiquement à partir du niveau 2.

**Résistances** : le bouton **Test** lance un D20, réussi si le dé est inférieur ou égal au score. Un sélecteur permet de choisir le type de lancer (normal, avec avantage ou désavantage). Une règle alternative d'avantage/désavantage est sélectionnante en éditant la fiche (onglet Caracs). Le journal affiche **1** pour une réussite et **0** pour un échec.

**Points de vie** : saisissez les points de vie actuels, maximum et le dé de vie. Toucher le cadre des PV ouvre la gestion des PV d'Encounter+. 

**Célébrité** : la fiche indique combien il manque de point de célébrité avant de monter de niveau. La remise à zéro au passage de niveau se fait manuellement.

**Objets** : un bouton lance les dégâts d'une arme. Le menu d'usure tire le dé d'usure et permet de changer de dé (de D12 à D4). Les cases à cocher comptent les utilisations restantes des équipements et des provisions.

**Encombrement** : la fiche calcule le total et signale encombré (4 à 6), surchargé (7 à 9) et écrasé (10 et plus).


## Crédits et licences

*Exploirateurs de bruines* est un jeu des éditions de L'Averse©. Concept, textes et publication : Vivien Féasson. Conception artistique, illustrations et mise en page : Willy Cabourdin.

Polices : [Merriweather](fonts/OFL-Merriweather.txt), [Oswald](fonts/OFL-Oswald.txt) et [Covered By Your Grace](fonts/OFL-Covered%20By%20Your%20Grace.txt), sous licence SIL Open Font License.
