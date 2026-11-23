# Ghammas Grill & Oven - online menu

Static site: index.html + intro.mp4 (+ data.json, img/, video/ created by the admin panel).

## Deploy (GitHub Pages)
Settings > Pages > Deploy from a branch > main / (root).

## Admin panel
1. Create a token: GitHub > Settings > Developer settings > Personal access tokens > Fine-grained tokens.
   Repository access: only this repository. Permissions > Contents: Read and write.
2. Open the site, tap Admin (footer), enter the admin password.
3. Tap Admin settings, enter owner/repository and the token, Save.
   Edit dishes with the Edit buttons. Every Save commits data.json to the repository;
   the site updates about 1 minute later.
The token is stored only in your browser. Never put it in the code.
