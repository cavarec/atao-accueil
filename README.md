# atao.dev — page d'accueil

Page statique listant les applications. Pour ajouter un projet, dupliquer un
bloc `<a class="card">` dans `public/index.html`, puis `git push`.

Déploiement : Cloudflare → Workers & Pages → Import a repository, projet
nommé `atao-accueil`, commande de build vide, commande de déploiement
`npx wrangler deploy`.
