# The NN Pod — Starter Website

A responsive static homepage with the supplied NN Pod logo, placeholder content, About and Games starter pages, and Pages CMS configuration.

## Preview
Open `index.html` in a browser. Some homepage content is loaded from `content/home.json`, which browsers may block when opened directly as a file. For a complete local preview, run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Free publishing
1. Create a GitHub repository and upload these files, including the hidden `.pages.yml` file.
2. In Cloudflare, create a Pages project connected to the GitHub repository. Use the static HTML setup: no build command, output directory `/` (repository root).
3. Open https://pagescms.org/ and sign in with GitHub. Authorize the repository and use the Pages CMS editor to manage `content/home.json`.
4. Grant team members appropriate GitHub repository access and Pages CMS access as supported by your configuration. Review permissions before inviting editors.
5. Cloudflare Pages redeploys when content is committed to the GitHub repository. Add a custom domain in Cloudflare Pages when ready; a GoDaddy-purchased domain can be used.

## Content editing
Pages CMS controls the latest episode, YouTube Shorts, social URLs and three homepage news/blog previews through `.pages.yml`. Use full HTTPS YouTube links. Empty fields show placeholders. This is a starter CMS configuration, not yet a complete multi-page article publishing system.

## Rights and imagery
The supplied NN Pod logo is included. No third-party Arsenal photographs have been embedded; obtain verified rights/attribution before adding any. The site is an independent fan project, not affiliated with Arsenal Football Club.

## Next steps
Add the real host names, biographies and photographs; confirmed social profile links; current YouTube videos; a full article collection for news/blog; and a future shop page when needed.
