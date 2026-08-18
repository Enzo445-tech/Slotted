# Slotted. 

> Le support de jeux qui s'adapte à ta collection.

Slotted est un configurateur gratuit qui crée un support de rangement adapté à ta console et au nombre de jeux que tu possèdes. Choisis un format, indique le nombre d'emplacements et télécharge un fichier STL prêt à imprimer.

**Gratuit · Sans compte · Sans installation · Sans supports d'impression** 

[Créer mon support](https://enzo445-tech.github.io/Slotted/configurateur.html) · [Découvrir le site](https://enzo445-tech.github.io/Slotted/) · [Rejoindre le Discord](https://discord.gg/hqb5MYpvVc)

> [!NOTE]
> Slotted est actuellement en bêta publique. Les principaux formats sont testés progressivement et les tolérances peuvent légèrement varier selon l'imprimante, le filament et les réglages utilisés.

## Comment ça marche ?

1. **Choisis ta console** parmi les formats disponibles.
2. **Indique le nombre de jeux** à ranger, de 2 à 16.
3. **Vérifie le support dans l'aperçu 3D** interactif.
4. **Télécharge le STL** et ouvre-le dans ton logiciel de tranchage habituel.

La largeur, la profondeur et l'espacement sont calculés automatiquement à partir du format sélectionné. Aucune mesure ni modélisation 3D n'est nécessaire.

## Pourquoi Slotted ?

- **Rapide à imprimer** : un support PS4 de 6 jeux s'imprime en environ 56 minutes sur une Bambu Lab A1.
- **Économique** : la forme utilise peu de matière et ne nécessite aucun support d'impression.
- **Stable** : le socle plein maintient les boîtiers correctement sur une étagère.
- **Compact** : le support dépasse le moins possible tout en permettant de placer les jeux dans les deux sens.
- **Simple** : tout fonctionne directement dans le navigateur, sans compte et sans logiciel supplémentaire.

## Formats compatibles

| Famille | Formats |
| --- | --- |
| **PlayStation** | PS1 · PS2 · PS3 · PS4 · PS5 · PSP · PS Vita |
| **Nintendo** | Switch · Switch 2 · Wii / Wii U · 3DS · DS · GameCube |
| **Xbox** | Première génération · Xbox 360 · Xbox One · Xbox Series |
| **Sega** | Saturn · Dreamcast |

Chaque format utilise ses propres dimensions de boîtier. Le configurateur ajuste automatiquement le support au modèle choisi.

## Exemple réel

Configuration utilisée comme référence pour mesurer le temps d'impression :

| Paramètre | Valeur |
| --- | --- |
| Support | PS4 · 6 jeux |
| Dimensions | 113,4 × 137,2 mm |
| Temps d'impression | 55 min 28 s (≈ 56 min) |
| Imprimante | Bambu Lab A1 |
| Matériau | PLA Basic Bambu Lab |
| Remplissage | 15 % |
| Supports | Aucun |

Le temps réel dépend de l'imprimante, du profil de tranchage, du filament et du nombre d'emplacements.

## Aperçu 3D maison

Slotted possède son propre moteur graphique léger. Il reconstruit le support en temps réel dans le navigateur à chaque changement de console ou de capacité.

L'aperçu n'utilise ni WebGL, ni Three.js, ni moteur 3D externe : les points du modèle sont projetés sur un canvas 2D, ce qui permet au configurateur de rester rapide et autonome.

L'affichage en fil de fer peut parfois produire de petits croisements visuels pendant la rotation. Cela n'affecte pas le fichier STL exporté.

## Utilisation locale

Le projet est constitué de deux pages HTML autonomes et ne demande aucune étape de compilation :

- `index.html` : page de présentation ;
- `configurateur.html` : configurateur et générateur STL.

Pour l'essayer localement, télécharge le dépôt puis ouvre `index.html` dans un navigateur récent.

## Retours et contributions

Un boîtier semble trop serré, trop large ou mal dimensionné ? Ouvre une [issue GitHub](https://github.com/Enzo445-tech/Slotted/issues) ou partage ton retour sur [Discord](https://discord.gg/hqb5MYpvVc) en précisant la console, l'imprimante, le filament et le profil utilisés.

## Licence

Slotted est distribué sous licence [Creative Commons Attribution–NonCommercial 4.0 International](LICENSE.md).

L'utilisation personnelle, la modification et le partage avec attribution sont autorisés. La vente des fichiers ou des pièces imprimées n'est pas autorisée.

---

<div align="center">

**Fait pour être imprimé.**

Enzo445 × NEXA

</div>
