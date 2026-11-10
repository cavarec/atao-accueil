# atao.dev — page d'accueil

Page statique présentant les applications (Cahier, VoxLab) et les réalisations
Cloudflare. Pour ajouter un projet, éditer `public/index.html` (section
« Réalisations »), puis `git push`. Images dans `public/img/`.

Déploiement : Cloudflare → Workers & Pages → Import a repository, projet
nommé `atao-accueil`, commande de build vide, commande de déploiement
`npx wrangler deploy`.
