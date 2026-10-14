# Etsy Keyword Generator

A free tool by Courtney Nichole for new Etsy sellers. Visitors answer 6 quick questions about their product, customer, and buyer moment, and get 50+ keyword phrases to check in eRank or EverBee before using them in titles and tags.

Everything lives in one file, `index.html`. There is nothing to install or build.

## Put it online with GitHub Pages

1. Create a new **public** repository on GitHub (for example `keyword-generator`).
2. Click **Add file → Upload files**, drag in `index.html` and this `README.md`, then click **Commit changes**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then click **Save**.
5. Wait a minute or two, then refresh the Pages screen. Your link will appear at the top, in this format:
   `https://YOUR-USERNAME.github.io/keyword-generator/`

## Use your own domain (optional)

To serve it from something like `tools.courtneynichole.net`:

1. In **Settings → Pages → Custom domain**, enter the subdomain and click **Save**.
2. At your domain provider, add a **CNAME** record:
   - Name/host: `tools`
   - Value/target: `YOUR-USERNAME.github.io`
3. Once the DNS check passes, tick **Enforce HTTPS**.

## Making changes

Edit `index.html` on GitHub (pencil icon), commit, and the live page updates within a minute or two.

Things you might want to change, all near the top of the `<script>` section:

- **Products and their other names:** `TYPES`
- **Who it's for:** `RECIPIENTS`
- **Moments / occasions:** `MOMENTS`
- **Style words:** `STYLES`
- **Related angles for design subjects** (e.g. flowers → floral, botanical, plant lover): `THEMES` and `THEME_ALIAS`
- **Trademark warning words:** `TM_WORDS`
- **Phrase count:** `MIN_PHRASES` (minimum) and `TARGET` (aim)

Links to update if they ever change:

- Community button: `https://courtneynichole.net/community`
- eRank affiliate link: `https://erank.com?fpr=courtney-644a45`
- EverBee affiliate link: `https://www.everbee.io/?via=courtney-richer`
