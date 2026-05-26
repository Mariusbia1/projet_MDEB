# La Maison de l'Entreprise du Benin

Landing page responsive en HTML, CSS et JavaScript vanilla pour presenter la plateforme "La Maison de l'Entreprise du Benin".

## Structure

- `src/` : code source du site.
- `src/index.html` : structure de la page.
- `src/style.css` : design responsive, couleurs, cartes, hero, footer.
- `src/script.js` : menu mobile et activation des liens de navigation au scroll.
- `src/assets/images/` : visuels placeholder utilises par la page.
- `src/vercel.json` : configuration Vercel si le dossier racine du projet est `src`.
- `src/package.json` : script de build utilise par Vercel dans `src`.

## Fichiers

- `npm run dev` : lance un serveur local sur `http://localhost:8000`.
- `npm run build` : commande de validation pour Vercel.

## Ouvrir le projet

Ouvrez simplement `src/index.html` dans un navigateur moderne.

Vous pouvez aussi lancer un petit serveur local depuis ce dossier :

```bash
npm run dev
```

Puis ouvrez `http://localhost:8000`.

## Deploiement Vercel

1. Publiez ce dossier sur GitHub.
2. Sur Vercel, cliquez sur `Add New Project`.
3. Importez le depot GitHub.
4. Dans les reglages Vercel, choisissez `src` comme `Root Directory`.
5. Laissez `Output Directory` sur `.` si Vercel le demande.
6. Vercel lancera `npm run build` depuis `src/` et publiera directement ce dossier.
