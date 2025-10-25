# OrthoScale

> GitHub ne permet pas d’exécuter des formulaires ou du JavaScript dans le README. Pour que les utilisateurs puissent utiliser l’application directement, publiez la page via GitHub Pages et ajoutez un lien ici.

### Utiliser l’application en ligne (GitHub Pages)
1. Ouvrez votre dépôt sur GitHub → `Settings` → `Pages`.
2. Dans "Build and deployment" :
   - Source : "Deploy from a branch"
   - Branch : `main` / dossier `/ (root)`
   - Cliquez sur "Save".
3. Après quelques minutes, votre site sera disponible à l’adresse :
   - `https://<votre-utilisateur>.github.io/OrthoScale/`

Ajoutez ce lien ci‑dessous pour un accès direct :

- Lien : `https://<votre-utilisateur>.github.io/OrthoScale/`
- Badge : `[![Ouvrir l'app](https://img.shields.io/badge/Ouvrir%20l%27app-OrthoScale-blue)](https://<votre-utilisateur>.github.io/OrthoScale/)`

> Remplacez `<votre-utilisateur>` par votre nom d’utilisateur GitHub.

### Alternative rapide (sans Pages)
Si vous ne pouvez pas activer Pages tout de suite, utilisez un aperçu HTML direct :

`https://htmlpreview.github.io/?https://raw.githubusercontent.com/<votre-utilisateur>/OrthoScale/main/index.html`

> Remplacez `<votre-utilisateur>` par votre nom d’utilisateur GitHub.

### Capture d’écran
![Aperçu de l’application](./121_50_web.png)

### Développement local
- Ouvrez `index.html` directement dans votre navigateur (double‑clic) ou servez le dossier avec un serveur statique.
- Exemple (Node.js) : `npx serve .` puis ouvrez l’URL affichée.

### FAQ
**Pourquoi le formulaire ne s’affiche pas / ne fonctionne pas dans le README ?**
- GitHub traite le README en Markdown et filtre les éléments interactifs/JS pour des raisons de sécurité. Les formulaires et scripts ne sont pas exécutés dans le README. La solution officielle est d’héberger la page via GitHub Pages et de lier le site depuis le README.
