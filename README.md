# ✦ Les Archives des Veilles — Visionneuse interactive

Visionneuse interactive développée pour accompagner la bibliothèque numérique **Les Archives des Veilles**.

## ✧ Présentation

Cette application permet de consulter les infographies des Archives des Veilles dans un environnement de lecture immersif, adapté aux ordinateurs, tablettes et smartphones.

Elle est reliée à la bibliothèque numérique accessible à l'adresse **https://lesarchivesdesveilles.fr/**, où chaque exploration dispose de sa propre fiche documentaire.

## ✧ Fonctionnalités

- Navigation entre les infographies d'une exploration.
- Zoom à la molette sur ordinateur et zoom tactile sur mobile.
- Déplacement des images agrandies.
- Navigation par balayage horizontal.
- Réinitialisation du zoom.
- Mode plein écran.
- Interface responsive adaptée aux différents écrans.
- Chargement dynamique des infographies selon le numéro d'archive.
- Récupération des images depuis Google Drive.
- Retour vers la fiche documentaire de l'exploration.

## ✧ Organisation

Chaque exploration est identifiée par un numéro d'archive.

Le fichier `archives.json` associe ce numéro au dossier `Publication` correspondant sur Google Drive.

La visionneuse récupère les planches numérotées, les classe dans leur ordre de lecture et les affiche sans nécessiter la création d'une nouvelle page HTML pour chaque exploration.

Les archives composées d'une seule infographie de synthèse sont présentées directement sur leur fiche documentaire dans la bibliothèque principale.

## ✧ Publication des archives

Un assistant local développé en **Python**, avec Tkinter et Pillow, facilite la préparation des nouvelles publications.

Il assure notamment la conversion des illustrations au format WebP et la génération du fragment JSON nécessaire pour référencer chaque nouveau dossier Google Drive.

Les fichiers sont ensuite ajoutés manuellement à la visionneuse et à Google Drive.

## ✧ Technologies

**HTML5 · CSS3 · JavaScript · JSON · GitHub Pages · Google Drive API**

L'assistant de publication utilise également **Python · Tkinter · Pillow**.

## ✧ Évolutions envisagées

- Amélioration progressive du confort de lecture.
- Enrichissement de la bibliothèque et de ses explorations.
- Simplification des opérations de publication et de maintenance.

## ✧ Les Archives des Veilles

Une bibliothèque d'explorations, de récits et de perceptions, présentés à travers des synthèses et des infographies illustrées.

Les contenus rapportent des perceptions et des hypothèses issues des explorations ; ils ne constituent pas des faits établis.

---

© 2026 Les Archives des Veilles.
