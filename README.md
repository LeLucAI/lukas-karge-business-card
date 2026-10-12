# Dr. Lukas Karge Business Card

Static personal website for GitHub Pages. Dark, portrait-led design inspired by phils-ventures.com, with About, Ventures and Contact sections.

## Local preview

Run `python3 -m http.server 4173` and open `http://localhost:4173`. No build step or external runtime dependencies are required. The Anton typeface is self-hosted in `assets/fonts` with its SIL Open Font License.

## Links

- LinkedIn: <https://www.linkedin.com/in/lukas-karge-231903b3/>
- Email: <lukas.karge@obsphera.ai>
- Schedule meeting: <https://calendly.com/lukaskarge>
- Obsphera.ai: <https://obsphera.ai>
- pixlbox.io: <https://pixlbox.io>
- Swarm.ai / TUM PF: <https://www.asg.ed.tum.de/pf/home/>

## Publish With GitHub Pages

1. Create a GitHub repo for this directory.
2. Push the repo to GitHub.
3. In the repo settings, enable Pages with `GitHub Actions` as the source.
4. The workflow in `.github/workflows/pages.yml` will deploy the static site.

After publishing, use the final GitHub Pages URL for:

- NFC card target
- QR code target
- Apple Wallet pass back URL

## Calendly

The page currently points to `https://calendly.com/lukaskarge`. Replace that URL in `index.html` and `lukas-karge.vcf` if your actual Calendly event link is different.
