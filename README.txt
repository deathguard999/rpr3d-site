RPR3D GitHub Pages deploy package

Prepared for:
GitHub username: deathguard999
Recommended repo name: rpr3d-site

Files:
- index.html
- CNAME
- .nojekyll

Deploy steps:
1. Create a public GitHub repository named rpr3d-site
2. Upload these files to the root of the repository
3. Go to Settings > Pages
4. Under Source choose: Deploy from branch
5. Branch: main, Folder: / (root)
6. Save
7. Wait for GitHub Pages to publish

Expected preview URL before domain is connected:
https://deathguard999.github.io/rpr3d-site/

Custom domain:
www.rpr3d.no

DNS records to set at your domain provider:
CNAME
Host: www
Value: deathguard999.github.io

A records for apex domain rpr3d.no:
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

After DNS is set:
- In GitHub Pages, make sure custom domain is www.rpr3d.no
- Enable Enforce HTTPS
