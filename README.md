# Espace de prévisualisation

Petit site statique destiné à héberger des interfaces HTML indépendantes.

## Publication

Chaque push sur `main` déclenche GitHub Actions et publie le contenu du dépôt sur GitHub Pages.

Après le premier déploiement, le site sera disponible à :
https://craftounet.github.io/Testchatgpt/

Si GitHub Pages n'est pas encore activé pour ce dépôt, ouvrir **Settings → Pages**, choisir **GitHub Actions** comme source, puis relancer le workflow.

## Modification

Modifier `index.html`, pousser les changements sur `main` et attendre la fin du workflow **Publier le site sur GitHub Pages**.
