UNSERIOUS GAMES FREE SITE

Files included:
- index.html
- styles.css
- assets/logo.png

FASTEST FREE HOSTING OPTION: GitHub Pages

1. Create a new GitHub repository.
2. Upload everything from this folder.
3. In the repo, go to Settings > Pages.
4. Under Build and deployment, choose 'Deploy from a branch'.
5. Select the main branch and /(root).
6. Save.
7. Your site will be live on a github.io URL.

CONNECT YOUR OWN DOMAIN

Add these DNS records at your domain provider:
- CNAME record:
  Host: www
  Value: yourusername.github.io

For the root domain, GitHub Pages usually asks for A records pointing to:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Then add a file called CNAME in the root of the repo with:
www.yourdomain.com
or
yourdomain.com

If you want SSL, GitHub Pages can provision it once DNS is correct.
