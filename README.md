# analytt-website

Basic GitHub Pages starter for this repository.

## Site URL

- Live URL: `https://atleanalytt.github.io/analytt-website/`
- GitHub Pages settings: repository -> `Settings` -> `Pages`

Project-site URL format:

- `https://<username>.github.io/<repo-name>/`

## Custom domain (GitHub Pages)

1. Buy or use a domain from your registrar.
2. In this repo, go to `Settings` -> `Pages`.
3. Under **Custom domain**, enter your domain (for example `www.example.com`) and save.
4. Configure DNS at your registrar:
   - For subdomain (`www.example.com`): create a `CNAME` record pointing to `atleanalytt.github.io`.
   - For apex/root (`example.com`): create `A` records pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
5. Wait for DNS propagation (can take minutes to hours).
6. Back in `Settings` -> `Pages`, enable **Enforce HTTPS** when available.

## Deploy updates

Push changes to `main` and GitHub Pages rebuilds automatically.

## Run locally

From the repository root:

```bash
python3 -m http.server 4173
```

Then open:

- `http://127.0.0.1:4173`
