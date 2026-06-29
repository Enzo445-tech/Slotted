# Slotted

**Le support de jeux qui s'adapte à ta console, pas l'inverse.**

Slotted est un générateur de supports de rangement pour jeux vidéo, imprimables en 3D. Choisis ta console, le nombre de jeux à ranger, et télécharge un fichier prêt à trancher — sans cote à reprendre, sans modèle générique qui ne correspond jamais tout à fait à ton boîtier.

Pas de compte, pas d'installation, pas de backend. Tout tourne dans le navigateur.

---

## Le principe

Un support de rangement classique pour jeux vidéo, ça se résume à peu de choses : un socle plat, des petites parois pour séparer chaque boîtier, et une paroi de fond pour les empêcher de glisser. La difficulté, c'est que chaque console a son propre format de boîtier — un jeu PS5 et un jeu Switch n'ont ni la même épaisseur, ni la même largeur. Un modèle figé pour l'un ne conviendra jamais parfaitement à l'autre.

Slotted règle ce problème en générant le modèle à la demande, à partir de mesures réelles :

1. **Choisis ta plateforme et ta console** — PlayStation, Nintendo, Xbox ou Sega, du PS1 à la PS5, de la Game Boy à la Switch 2.
2. **Indique le nombre de jeux** à ranger.
3. **Télécharge le fichier .STL**, déjà dimensionné à l'épaisseur exacte de ton boîtier, prêt à être ouvert dans ton logiciel de découpe (slicer) habituel.

La largeur du support, la profondeur, l'espacement entre chaque jeu : tout est recalculé automatiquement à chaque changement. Il n'y a aucune mesure à reprendre à la main.

## Consoles prises en charge

| Plateforme | Modèles |
|---|---|
| **PlayStation** | PS1 · PS2 · PS3 · PS4 · PS5 · PSP · PS Vita |
| **Nintendo** | Switch · Switch 2 · Wii / Wii U · 3DS · DS · GameCube |
| **Xbox** | 1ère génération · 360 · One · Series |
| **Sega** | Saturn · Dreamcast |

Chaque modèle a son épaisseur de boîtier mesurée individuellement — ce n'est pas une estimation générique appliquée à toutes les consoles.

## Pensé pour être imprimé

Le modèle généré est volontairement simple : un socle plat avec des parois basses, sans surplomb ni zone qui nécessiterait des supports d'impression. Les épaisseurs ont été optimisées pour rester solides tout en réduisant le temps d'impression et la quantité de matière utilisée — sur un support typique, on passe d'environ 2h30 à 1h15-1h30 par rapport à une première version plus massive.

Aucun réglage de profondeur à deviner non plus : elle se calcule automatiquement à partir de la taille réelle du boîtier choisi.

## Comment fonctionne l'aperçu 3D

Le configurateur affiche un aperçu du modèle qui se reconstruit en direct à chaque réglage. Il n'utilise ni WebGL ni de moteur 3D externe (pas de Three.js, pas de dépendance à charger) : chaque point du modèle est projeté à la main sur une simple image 2D, recalculé image par image. C'est un choix délibéré — moins de poids, moins de risques de chargement cassé, et un aperçu qui reste fidèle à la géométrie réellement exportée.

Cette approche "fait main" a une contrepartie : il peut arriver que l'aperçu affiche un effet visuel inattendu pendant la rotation (une arête qui semble se croiser un instant, une face qui clignote à un certain angle). C'est un artefact du rendu en fil de fer, pas un défaut du modèle — le fichier `.STL` téléchargé reste toujours exact, quel que soit ce qu'affiche l'aperçu à l'écran.

## Utilisation

Le projet est constitué de deux pages HTML autonomes, sans dépendance ni étape de build :

- `index.html` — page de présentation
- `configurateur.html` — l'outil de génération à proprement parler

---

Fait pour être imprimé — **Enzo445 × NEXA**
