LINKEDIN / SOCIAL PREVIEW UPDATE

This package intentionally does NOT contain index.html, so it cannot overwrite your current light V5 website.

1. Upload social-preview.png into the existing GitHub folder:
   assets/social-preview.png

2. Open the CURRENT live index.html in GitHub and click Edit.

3. In the <head> section, keep your existing charset/viewport tags.
   Replace the existing og:* and twitter:* social metadata with the contents of HEAD_SNIPPET.txt.
   If your current page has no such tags, paste the snippet immediately before </head>.

4. Commit directly to main.

5. Wait for GitHub Pages to deploy. Then verify this direct image opens:
   https://tanveeroakasa.github.io/transportation-ai-portfolio/assets/social-preview.png

6. Return to LinkedIn Featured -> Add a link, paste the portfolio URL, and click Try again.

Important:
LinkedIn may cache an older failed preview. If it still fails immediately after deployment, retry later or use LinkedIn's Post Inspector to request a re-scrape.
