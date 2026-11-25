# Agehesha.github.io

Official website of the independent game developer **Agehesha**, served by GitHub Pages at
<https://agehesha.github.io/>.

| Path | Content |
|------|---------|
| `/` | Developer home page, Metro Empire, support contact |
| `/privacy/` | Privacy Policy (English) — link this in Google Play Console and AdMob |
| `/404.html` | Not-found page |
| `/app-ads.txt` | Authorized ad sellers for AdMob (publisher `pub-9379315583702570`) |

Plain static HTML and CSS: no build step, no external fonts, scripts, analytics or cookies.
`.nojekyll` turns off Jekyll so every file is served as is.

## app-ads.txt (AdMob)

`app-ads.txt` is published (25.11.2026) for publisher `pub-9379315583702570`. To change it or set it up again:

1. AdMob → Apps → View all apps → **app-ads.txt** → *How to set up app-ads.txt* — copy the line AdMob shows.
   It looks like `google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0`, with **your own** publisher ID.
2. Save it as `app-ads.txt` in the root of this repository (next to `index.html`), commit and push.
3. Check that <https://agehesha.github.io/app-ads.txt> opens as plain text.
4. In Google Play Console → Store presence → Store settings → **Website**: `https://agehesha.github.io`
   (exactly this host, without a path). AdMob reads the file from the root of that host;
   allow up to 24 hours for verification.
