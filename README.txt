MESUTRONIC — NOTES DE FRAIS IPHONE
===================================

Fichiers à déposer ensemble à la racine d'un dépôt GitHub Pages :
- index.html
- modele-note-frais.xlsx
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

UTILISATION
1. Ouvrir l'URL GitHub Pages sur l'iPhone avec Safari.
2. Partager > Sur l'écran d'accueil.
3. Ouvrir l'app depuis l'icône.
4. Dans Réglages, saisir une seule fois la clé API Anthropic.
5. Photographier les justificatifs au fil du mois.
6. Vérifier/corriger les lignes proposées.
7. "Exporter dossier complet" génère un ZIP contenant :
   - la note de frais Excel au format MESUTRONIC ;
   - les photos numérotées 01, 02, 03... dans le même ordre que les lignes.

IMPORTANT
- Les photos et les données du mois sont conservées localement sur l'appareil via IndexedDB.
- La clé API reste dans le stockage local du navigateur ; elle n'est pas écrite dans GitHub.
- La lecture IA nécessite une connexion internet.
- Le modèle accepte jusqu'à 30 justificatifs par mois.
