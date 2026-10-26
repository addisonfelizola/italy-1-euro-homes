# Italy €1 Homes website

A static site with no build step: `index.html` plus three guide pages (`guides.html`, `how-1-euro-houses-work.html`, `costs-deposits-and-renovation.html`, `can-foreigners-buy-1-euro-house.html`), `styles.css`, `sitemap.xml`, and `robots.txt`.

## Put it on GitHub Pages

1. Create a free GitHub account if you don't have one, then click **New repository**.
2. Name it, for example `italy-1-euro-homes`. Set it to **Public** (GitHub Pages is free for public repositories). Don't add a README or license from the GitHub form, so the upload stays simple.
3. Click **uploading an existing file**, drag in all of the files above, and commit. Uploading only `index.html` breaks the guide links.
4. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder to **/ (root)**, and save.
5. After about a minute the site is live at `https://addisonfelizola.github.io/italy-1-euro-homes/`.

To change the site later, edit `index.html` on GitHub (or upload a new copy) and commit. GitHub republishes automatically.

## Before you share the link

- The site is public and search engines can index it. Anything published stays visible until you delete or change it.
- The three services (notice review, remote scouting, renovation planning) should stay marked as planned until an Italian lawyer confirms they are permitted, and until local partners are in place for scouting and planning.
- The "How we work" section states the no-commission, no-brokerage model. Change it if the model changes. Do not add commission links or referral fees.
- Only use buyer names, photos, or property details with written consent.

## Custom domain (optional)

Buy a domain, then in **Settings → Pages → Custom domain** enter it and follow GitHub's DNS instructions. GitHub will create the CNAME file for you.

## Search setup (do this after the site is live)

1. Replace every `addisonfelizola` with your GitHub username, and change `italy-1-euro-homes` if you named the repository differently. These appear in the canonical links, the sitemap, and robots.txt. On GitHub, use the repository's find-and-replace or edit each file.
2. Verify the site in Google Search Console (add the URL, then use the HTML tag or DNS method). Submit `sitemap.xml` under Sitemaps. Bing Webmaster Tools works the same way.
3. Keep the guides accurate. Update the "Last reviewed" date and the sources when the rules change.
4. Share the guides where they genuinely help people, such as relevant community forums or groups, following each group's rules. Don't buy links or post the same message everywhere.

Search engines take weeks to months to rank new sites. Ranking depends on time, on other sites linking to yours, and on the quality of the content.
