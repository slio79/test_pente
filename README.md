# Analyse de courbes

Outil autoporteur (un seul fichier HTML, sans dépendance, utilisable hors ligne) pour analyser des courbes issues d'un fichier CSV.

## Utilisation

Ouvrir `Analyse_Courbes.html` dans Chrome ou Edge, puis charger un fichier CSV (bouton ou glisser-déposer).

## Fonctionnalités

- Détection automatique du format **US** (`,` / `.`, dates mm/jj, AM/PM) ou **FR** (`;` / `,`, dates jj/mm, 24 h) ; fusion des colonnes Date + Heure.
- Choix de l'abscisse et de plusieurs ordonnées (affichage superposé ou empilé).
- Période affichée réglable par curseurs avec boutons − / + au point près, zoom à la souris.
- Courbe de tendance linéaire (y = a·t + b) sur une courbe, avec **plusieurs zones de calcul** simultanées (jusqu'à 8), réglables par curseurs dans le panneau ou par poignées sur le graphique.
- Résultats par zone : pente, ordonnée à l'origine, R², variation, écart-type résiduel, nombre de points.
- Exports : graphique en JPEG 3200 × 1800 (16:9), CSV des points affichés (format source, FR ou US), CSV des résultats par zone.

Les données restent sur le poste : rien n'est envoyé sur Internet.
