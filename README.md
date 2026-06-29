# Slotted

> **Le support de jeux qui s'adapte à ta console, pas l'inverse.**

Slotted est un générateur de supports de rangement pour jeux vidéo imprimables en 3D. Choisis ta console, le nombre de jeux à ranger, puis télécharge un fichier prêt à trancher — sans cote à reprendre, sans modèle générique qui ne correspond jamais tout à fait à ton boîtier.

**Pas de compte. Pas d'installation. Pas de backend.** Tout tourne directement dans le navigateur.

---

# 📖 Le principe

Un support de rangement classique pour jeux vidéo se résume à peu de choses : un socle plat, des séparateurs et une paroi de fond pour empêcher les boîtiers de glisser.

Le problème, c'est que chaque console possède son propre format de boîtier. Un jeu PS5 et un jeu Switch n'ont ni la même largeur, ni la même épaisseur. Un modèle figé pour l'un ne conviendra donc jamais parfaitement à l'autre.

Slotted règle ce problème en générant le modèle à la demande à partir de mesures réelles.

1. **Choisis ta plateforme et ta console** — PlayStation, Nintendo, Xbox ou Sega, du PS1 à la PS5, de la DS à la Switch 2.
2. **Indique le nombre de jeux** à ranger.
3. **Télécharge le fichier `.STL`**, déjà dimensionné à l'épaisseur exacte de ton boîtier et prêt à être ouvert dans ton slicer habituel.

La largeur du support, sa profondeur et l'espacement entre chaque jeu sont recalculés automatiquement. Aucune mesure n'est à reprendre manuellement.

---

# 🎮 Consoles prises en charge

| Plateforme      | Modèles                                               |
| --------------- | ----------------------------------------------------- |
| **PlayStation** | PS1 · PS2 · PS3 · PS4 · PS5 · PSP · PS Vita           |
| **Nintendo**    | Switch · Switch 2 · Wii · Wii U · GameCube · DS · 3DS |
| **Xbox**        | Xbox · Xbox 360 · Xbox One · Xbox Series              |
| **Sega**        | Saturn · Dreamcast                                    |

Chaque modèle utilise les dimensions réelles de son boîtier. Aucune valeur générique n'est réutilisée d'une console à l'autre.

---

# 🖨️ Pensé pour être imprimé

Le modèle généré est volontairement simple : un socle plat avec des séparateurs bas, sans surplomb ni zone nécessitant des supports d'impression.

Les épaisseurs ont été optimisées pour conserver une bonne solidité tout en réduisant le temps d'impression et la quantité de matière utilisée. Sur un support typique, on passe d'environ **2 h 30** à **1 h 15 – 1 h 30***.

La profondeur du support est également calculée automatiquement à partir des dimensions réelles du boîtier sélectionné.

---

# 🖥️ Comment fonctionne l'aperçu 3D

Le configurateur affiche un aperçu qui se reconstruit en temps réel à chaque modification.

Il n'utilise **ni WebGL**, **ni Three.js**, ni aucun moteur 3D externe. Chaque point du modèle est projeté manuellement sur une image 2D puis recalculé à chaque image.

Ce choix permet de conserver un projet léger, sans dépendances, tout en affichant un aperçu fidèle au modèle réellement exporté.

Il peut arriver que certaines arêtes semblent se croiser ou qu'une face clignote brièvement pendant la rotation. Il s'agit uniquement d'un artefact du rendu en fil de fer : le fichier `.STL` généré reste parfaitement correct.

---

# 🚀 Utilisation

Le projet est constitué de deux pages HTML autonomes, sans dépendance et sans étape de build.

* `index.html` — page de présentation
* `configurateur.html` — générateur de supports

---

* L'estimation de **1 h 15 à 1 h 30** est basée sur le modèle **PS5 (6 emplacements)** imprimé sur une **Bambu Lab A1** avec des paramètres standards. Le temps d'impression peut varier selon la console, le nombre d'emplacements, l'imprimante et les réglages utilisés.

---

<div align="center">

**Fait pour être imprimé.**

**Enzo445 × NEXA**

</div>
