# Portfolio de Thierry Lam — V1

Portfolio personnel en React, TypeScript et Vite. Cette version est volontairement statique : pas de serveur ni de base de données nécessaires.

## Prérequis

- Node.js LTS installé
- npm (inclus avec Node.js)

Vérifie l'installation dans un terminal :

```bash
node -v
npm -v
```

## Lancer le site en local

1. Ouvre un terminal dans le dossier du projet.
2. Installe les dépendances :

```bash
npm install
```

3. Démarre le serveur de développement :

```bash
npm run dev
```

4. Ouvre l'adresse locale indiquée dans le terminal (généralement http://localhost:5173).

Le serveur se recharge automatiquement lorsque tu modifies les fichiers.

## Fichiers à connaître

- `src/App.tsx` : contenu et composants de la page.
- `src/styles.css` : couleurs, typographies, mise en page et responsive.
- `index.html` : titre et description SEO.
- `public/` : endroit prévu pour les images et le CV PDF.

## Personnaliser en premier

1. Vérifie les descriptions et les technologies de chaque projet dans `src/App.tsx`.
2. Remplace les illustrations CSS par des captures réelles quand tu en as.
3. Vérifie les liens LinkedIn et GitHub.
4. Ajoute ton CV PDF dans `public/cv-thierry-lam.pdf` puis ajoute un lien de téléchargement dans la navigation ou la section Contact.
5. Confirme les dates de formation et d'expérience avant publication.

## Vérifier la version de production

```bash
npm run build
npm run preview
```

La commande `npm run build` crée le dossier `dist/`. Le build doit terminer sans erreur avant le déploiement.

## Publication gratuite

Tu peux déployer le dossier construit avec un service d'hébergement statique comme Cloudflare Pages ou Vercel. Connecte le dépôt Git, puis configure la commande de build `npm run build` et le dossier de sortie `dist`.

Le nom de domaine personnalisé est facultatif : commence par l'URL gratuite fournie par l'hébergeur, puis décide plus tard si tu souhaites acheter un domaine.

## Avant mise en ligne

- Confirmer toutes les informations personnelles et professionnelles.
- Remplacer les visuels provisoires par des captures autorisées.
- Vérifier chaque lien depuis un téléphone et un ordinateur.
- Ajouter un CV PDF seulement si tu souhaites le rendre public.
- Si tu ajoutes des statistiques, des cookies non essentiels ou un formulaire tiers, réévaluer les obligations de confidentialité applicables.


## Remplacer les visuels des projets

Dépose tes images dans `public/projects/` avec les noms indiqués dans `public/projects/README.txt`. Les images sont affichées sur la liste des projets et leurs pages de détail. Format conseillé : paysage 16:9. Si les images ne sont pas présentes, les illustrations CSS restent visibles.
