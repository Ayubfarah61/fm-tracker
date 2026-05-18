# Ayub Farah Portfolio

Single-page portfolio site prepared for GitHub Pages.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `ayub-farah-portfolio`.
2. Upload everything in this folder to the repository root.
3. In GitHub, go to `Settings` -> `Pages`.
4. Set the source to `Deploy from a branch`, then choose `main` and `/root`.
5. Save. The site will be available at `https://YOUR-GITHUB-USERNAME.github.io/ayub-farah-portfolio/`.

## Custom Domain

When you have your domain, create or edit a file named `CNAME` in this folder and put only the domain inside it, for example:

```text
www.yourdomain.com
```

Then update the domain provider DNS:

- For `www`: add a `CNAME` record pointing to `YOUR-GITHUB-USERNAME.github.io`.
- For the root domain: add GitHub Pages `A` records in your DNS provider.

After DNS updates, return to GitHub `Settings` -> `Pages`, enter the custom domain, and enable HTTPS.
