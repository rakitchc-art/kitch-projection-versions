# Kitch Projection — versions publiées

Lecteur vidéo de représentation théâtrale pour Windows. Il enchaîne vidéos,
images et compositions sur un vidéoprojecteur, à la barre d'espace, sans jamais
montrer un bureau Windows ou une fenêtre de logiciel à la salle.

Ce dépôt ne contient **que les versions à installer**. Le code source est privé.

## Télécharger

👉 **[Dernière version](../../releases/latest)**

Téléchargez le fichier `KitchProjection2-<version>-installateur.exe` et
double-cliquez dessus.

### « Windows a protégé votre ordinateur »

C'est normal, et ce n'est pas un virus : le logiciel n'est pas encore signé
électroniquement, et Windows se méfie par principe de tout programme qu'il ne
connaît pas encore.

1. Cliquez sur **Informations complémentaires**
2. Puis sur **Exécuter quand même**

L'installation ne demande pas de droits administrateur.

## Prise en main

| Geste | Effet |
|---|---|
| **Ajouter des fichiers…** | ajoute vos vidéos et images (le glisser-déposer marche aussi) |
| **▶ LANCER LE SPECTACLE** | démarre la diffusion sur le vidéoprojecteur |
| **Barre d'espace** | lance la séquence suivante — le seul geste nécessaire en représentation |
| **← →** | reculer / avancer d'une séquence, pour se rattraper |
| **Échap** | arrête le spectacle, après confirmation |

Les projets s'ouvrent et s'enregistrent par le menu **Projet** (fichiers
`.kitch`). Réglages et journal vivent dans `%AppData%\Kitch Projection\` et
survivent à une désinstallation.

## Un problème ?

Ouvrez un ticket dans l'onglet **Issues**, en joignant si possible le journal :

```
%AppData%\Kitch Projection\journal-2.txt
```

Précisez ce que vous étiez en train de faire au moment du problème : c'est
l'information qui manque le plus souvent.

## Les deux générations

- **2.0** — génération actuelle, réécrite de fond en comble. C'est ce qui est
  publié ici.
- **1.x** — génération précédente, celle qui a servi en représentation
  jusqu'ici. Toujours utilisable, elle s'installe à côté de la 2.0 sans
  conflit : les deux logiciels ne partagent aucun fichier.

## Composants tiers

VLC (LGPL), FFmpeg (GPL) et les polices embarquées (OFL) sont livrés avec le
logiciel. Les textes de licence sont dans le dossier `licences\` de
l'installation, et la fenêtre **? → À propos** les affiche.
