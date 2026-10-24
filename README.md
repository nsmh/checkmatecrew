# Checkmate Crew — Little Grandmasters Chess

A static, browser-based chess practice website. It includes computer play, same-device two-player chess, tutorial mode, and starter level-based puzzle challenges.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `checkmatecrew`.
2. Upload **all files in this folder** to the repository root. `index.html` must be at the root, not inside another folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. In **Settings → Pages → Custom domain**, enter `checkmatecrew.online` and save. The included `CNAME` file contains this domain.
6. At your domain registrar's DNS settings, configure the apex domain records recommended by GitHub Pages. Common GitHub Pages IPv4 A records are `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. If you use `www.checkmatecrew.online`, add a CNAME record for `www` pointing to your GitHub Pages hostname (for example, `YOUR-USERNAME.github.io`). Replace the placeholder with your actual GitHub username.
7. Wait for DNS to propagate. Return to **Settings → Pages** and enable **Enforce HTTPS** when the option becomes available.

Do not put a password, API key, or other secret in this repository. This project is a static site and does not require a backend for its current features.

## Files

- `index.html` — website, styling, chessboard, and client-side JavaScript.
- `CNAME` — custom domain for GitHub Pages.
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing.

## Important current limitations

- Puzzle levels are starter move challenges, not yet a complete tactical puzzle library.
- Puzzle progress is not saved persistently across visits.
- The site does not include online multiplayer; friend mode is for two players sharing one device.
