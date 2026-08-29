# Portfolio Amadou Ly

Projet : portfolio professionnel statique en HTML, CSS et JavaScript (une seule page, sections ancrées).
Public : recruteurs et entreprises pour un stage de 6 mois en Data Science / Intelligence Artificielle (disponibilité à partir de 2027).

## Priorités
- Clarté du message (profil, projets, compétences, parcours, contact).
- Responsive mobile (testé dès 360 px).
- Accessibilité (navigation clavier, contrastes, structure sémantique).
- Chargement rapide (pas de dépendance lourde, deux polices Google Fonts uniquement).

## Structure
- `index.html` — page unique, sections `#profil`, `#projets`, `#competences`, `#experience`, `#contact`.
- `rapport-immobilier-nancy.html` — page de rapport détaillé (autonome, sa propre palette/typo Newsreader+Public Sans) pour le projet immobilier Nancy, avec graphiques SVG générés depuis des données réelles. Liée depuis la carte projet et depuis GitHub Pages directement (pas de dépendance à un Artifact externe).
- `assets/css/style.css` — tous les styles de `index.html`. Palette sobre (blanc cassé + accent indigo), pas de fond quadrillé.
- `assets/js/main.js` — comportement du menu mobile uniquement.
- `assets/images/` — `portrait.png` (hero), `prix_reels_vs_predits.png` (projet immobilier Nancy).
- `assets/documents/` — CV, mémoire et slides de recherche, notebook et dataset du projet immobilier.

## Projets (vérifiés comme réels, appartenant à Amadou Ly)
- **Nombres de Salem de trace −3** — mémoire de recherche M1 (co-écrit avec Ancelle Priscille Nahimana, dir. Jean-Marc Sac-Épée). Fichiers : `Memoire_Nombres_de_Salem.pdf`, `Presentation_Nombres_de_Salem.pdf`.
- **Prédiction des prix immobiliers à Nancy** — données réelles DVF (data.gouv.fr), 2021-2024, ~8 700 transactions après nettoyage. Metz n'a pas de données DVF publiques (régime du Livre Foncier en Alsace-Moselle) ; Nancy a été choisie comme ville la plus proche disposant de données complètes. Régression linéaire vs Random Forest sur le prix log-transformé, avec longitude/latitude comme variables de localisation. Fichiers : `prediction_prix_immobilier_nancy.ipynb`, `nancy_dvf_clean.csv`, `prix_reels_vs_predits.png`. Ne jamais présenter ces données comme concernant Metz.
- Ne jamais réintroduire de projet générique/inventé (ex. classification de maladies cardiovasculaires, dashboard Power BI) sans fichier source réel fourni par le propriétaire.

## Règles
- Conserver l'identité visuelle validée (palette verte/encre, police Fraunces + IBM Plex).
- Ne pas ajouter de dépendance sans accord (pas de framework CSS/JS).
- Ne pas supprimer de contenu existant sans validation.
- Expliquer les fichiers modifiés après chaque tâche.
- Tester les liens et l'affichage mobile après chaque modification.
- Avant toute modification importante : proposer un plan court et attendre validation.

## Contact
- Email : lyamadou0212@gmail.com (confirmé par le propriétaire du site — le CV mentionne ly643092@gmail.com, mais lyamadou0212@gmail.com est l'adresse à utiliser)
- Téléphone : 07 59 86 12 92
- LinkedIn : https://www.linkedin.com/in/amadou-ly-b8559b348/
- GitHub : https://github.com/lyamadou0212-oss
- CV : `assets/documents/CV_Amadou_LY.pdf`

## À vérifier
- Confirmer que le numéro de téléphone personnel peut rester public sur un site indexé.
