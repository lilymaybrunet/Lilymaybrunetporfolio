Portfolio — Lily-May Brunet
============================

Contenu du dossier
-------------------
index.html          Page d'accueil / présentation
photographie.html   Page photo
peinture.html        Page peinture
crochet.html         Page crochet
css/style.css        Toute la mise en page et les couleurs
js/main.js            Menu mobile + générateur des visuels d'espace réservé

Remplacer les visuels par tes vraies images
--------------------------------------------
Chaque œuvre est actuellement représentée par une illustration abstraite
générée automatiquement (pour que tu puisses juger la mise en page avant
d'avoir toutes tes photos). Pour mettre une vraie image à la place :

1. Ouvre le fichier HTML de la page concernée (ex. photographie.html)
2. Repère un bloc comme celui-ci :

   <div class="frame" data-art="photo" data-seed="1"></div>

3. Remplace-le par :

   <div class="frame">
     <img src="images/mon-fichier.jpg" alt="Description de l'œuvre">
   </div>

4. Crée un dossier "images" à côté de index.html et dépose tes fichiers dedans.

Modifier les couleurs
-----------------------
Toutes les couleurs sont définies en haut de css/style.css, dans ":root".
Change les valeurs hexadécimales (--gold, --berry, --teal, --bg, --ink...)
pour ajuster la palette sans toucher au reste du code.

Ajouter ou enlever des œuvres
--------------------------------
Dans chaque page, une œuvre = un bloc <article class="work">...</article>.
Copie-colle un bloc existant pour en ajouter un, ou supprime-le pour l'enlever.
La classe "wide" sur certains blocs leur donne un format plus large — à
utiliser avec parcimonie pour garder du rythme dans la grille.

Mettre le site en ligne
--------------------------
Ce dossier est un site statique : aucun serveur particulier n'est requis.
Tu peux le déposer tel quel sur Netlify, GitHub Pages, Vercel ou n'importe
quel hébergeur mutualisé classique.
