# Portfolio Amadou Ly

Site vitrine statique (HTML/CSS/JS) présentant le profil, les projets, les compétences et le parcours d'Amadou Ly, pour une recherche de stage en Data Science / Intelligence Artificielle.

## Voir le site en local

Ouvrir `index.html` dans un navigateur, ou utiliser l'extension **Live Server** de VS Code (clic droit sur `index.html` → "Open with Live Server") pour un rechargement automatique.

## Mettre à jour le contenu

- **Remplacer le CV** : déposer le nouveau PDF dans `assets/documents/` et mettre à jour le lien dans la section Contact de `index.html`.
- **Corriger un texte** : modifier directement le texte dans `index.html` (chaque section est identifiée par un commentaire, ex. `<!-- ================= PROFIL ================= -->`).
- **Ajouter un projet** : dupliquer un bloc `<article class="figure">...</article>` dans la section `#projets` et adapter le titre, la liste et les tags.
- **Ajouter le lien LinkedIn** : dans la section Contact, remplacer le texte "(lien à venir)" par un lien `<a href="...">`.

## Enregistrer une modification (Git)

```
git add .
git commit -m "Description du changement"
git push
```

## Publication

Le site est publié via GitHub Pages depuis ce dépôt. Après un `git push` sur la branche principale, la version publique se met à jour automatiquement (peut prendre quelques minutes).
