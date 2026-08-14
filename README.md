<p align="center"><img src="logo.png" width="160" alt="Kitch Projection"></p>

<h1 align="center">Kitch Projection</h1>

<p align="center"><b>Une touche. Aucune transition visible.<br>La salle ne voit jamais votre ordinateur. Point.</b></p>

<h3 align="center">⬇️&nbsp;&nbsp;<a href="../../releases/latest">Télécharger l'installateur</a></h3>

---

## Le noir entre deux vidéos, ça se voit du dernier rang

Vous avez déjà vu ça : la vidéo se termine, et pendant une demi-seconde le public aperçoit une barre de lecture, un bureau, un curseur. L'illusion tombe. Le régisseur retient son souffle et cherche la barre d'espace.

**Kitch Projection est fait pour que ce moment n'existe pas.** Deux lecteurs travaillent en alternance : pendant que l'un joue, l'autre a déjà chargé la suite, en pause sur sa première image. Vous appuyez sur Espace, et l'image change. Rien d'autre. Pas de clignotement, pas de logo, pas de fenêtre.

C'est le seul geste de la soirée.

## Écrit pour la régie, pas pour le montage

⌨️ **Une seule touche à connaître** — Espace enchaîne. Les flèches ← → rattrapent si un comédien saute une réplique
🎭 **Un spectacle se range en chapitres** — actes, tableaux, scènes, imbriqués autant qu'il le faut
🔁 **Un mode répétition** — sommaire cliquable, saut direct à un chapitre, sans jamais rien montrer à la salle
✂️ **Un éditeur vidéo intégré** — couper à l'image près, sans ouvrir un autre logiciel la veille de la première
🖼️ **Des compositions multi-calques** — plusieurs vidéos et images sur un même écran, avec ligne de temps et déformation par les coins
🎚️ **Un mixage par média et par calque** — le son se règle une fois, il tient toute la série
📺 **Un retour projecteur** — voir ce que voit la salle, sur l'écran de la régie
↩️ **Ctrl+Z sur tout** — chaque geste de préparation est annulable

## Ce qui compte quand il y a du monde dans la salle

- **Si le disque se remplit**, l'enregistrement s'arrête proprement et vous prévient — il ne meurt pas au milieu
- **Si vous appuyez sur Échap par réflexe**, une question vous le demande deux fois. La touche du réflexe ne peut pas arrêter le spectacle
- **Si la projection tombe sur l'écran de la régie**, la régie passe derrière au lieu de se superposer à la diffusion
- **Aucune boîte de dialogue ne s'ouvre jamais sur l'écran de projection**

## Éprouvé sérieusement — et dit sans exagérer

Cette génération 2.0 passe **32 contrôles automatiques** à chaque modification : conduite, chapitres, mapping, audio, sauvegarde, écrans multiples. Ils lancent le vrai logiciel, cliquent, mesurent, et rendent un verdict binaire.

Elle a aussi passé un **marathon d'endurance de 20 minutes** — 480 enchaînements, 40 compositions de vingt calques — pour vérifier qu'un spectacle de deux heures ne dérive pas. Une fuite mémoire de 13,8 Mo par minute y a été trouvée, traquée sur un cliché mémoire jusqu'à sa cause exacte, puis fermée : le logiciel retient aujourd'hui **0 Mo** au même test.

> **Ce qu'elle n'a pas encore fait : jouer devant un public.**
> La 2.0 est une réécriture complète, et la salle est un juge que personne ne remplace. Éprouvez-la en répétition avant de compter dessus le soir d'une première. Les essais sur vidéoprojecteur réel et enceinte Bluetooth sont la prochaine étape.

## Ce qu'il vous faut

| | |
|---|---|
| 🖥️ | Un PC **Windows 10/11** (64 bits) |
| 📽️ | Un vidéoprojecteur ou un second écran — *facultatif, tout marche sur un seul écran* |
| 🎬 | Vos vidéos et vos images |

Rien d'autre à installer : le moteur vidéo et tout le nécessaire sont dans l'installateur.

## Télécharger

**[→ Dernière version, un seul fichier](../../releases/latest)**

> ⚠️ **L'avertissement bleu de Windows est normal.** Kitch Projection n'est pas signé numériquement : au premier double-clic, SmartScreen dira « Windows a protégé votre ordinateur ». Cliquez **« Informations complémentaires »** puis **« Exécuter quand même »**. Cet avertissement apparaît pour toute application indépendante — il ne dit rien de la sûreté du programme.

L'installation ne demande **pas** de droits administrateur.

## Les premières minutes

1. **Ajouter des fichiers…** — ou glissez vos vidéos directement dans la liste
2. **▶ LANCER LE SPECTACLE** — l'image part sur le vidéoprojecteur, sinon en plein écran
3. **Espace** — la séquence suivante
4. **Échap** — arrêter, après confirmation

Vos spectacles s'enregistrent par le menu **Projet** (fichiers `.kitch`). Réglages et journal vivent dans `%AppData%\Kitch Projection\` et **survivent à une désinstallation**.

## Deux générations, aucune bagarre

La **1.x** est la génération précédente, celle qui a réellement servi en représentation. La **2.0** s'installe **à côté** d'elle : identifiant différent, dossier différent, aucun fichier partagé. Gardez les deux le temps de prendre confiance — la 2.0 sait même relire les projets préparés avec la 1.x.

---

<p align="center"><i>Un souci ? <a href="../../issues">Ouvrez un ticket</a> — joignez <code>%AppData%\Kitch Projection\journal-2.txt</code> et dites ce que vous étiez en train de faire.</i></p>

<p align="center"><sub>Contient VLC (LGPL), FFmpeg (GPL) et des polices sous licence OFL. Les textes de licence sont livrés avec le logiciel, et la fenêtre <b>? → À propos</b> les affiche.</sub></p>
