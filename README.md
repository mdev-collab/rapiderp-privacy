# Rapid ERP — Privacy Policy

The public privacy policy for the **Rapid ERP** Android app (`com.rapiderp.app`),
required by the Google Play Console.

`index.html` is a self-contained static page — no build step, no external assets.

## Deploying

### Railway
Railway detects `package.json`, installs [`serve`](https://www.npmjs.com/package/serve),
and runs `npm start` to serve this directory on `$PORT`. Add a public domain in
**Settings → Networking → Generate Domain** to get the URL.

### GitHub Pages (free alternative, no server)
**Settings → Pages → Source: `main` / root.** Serves `index.html` at
`https://<user>.github.io/rapiderp-privacy/`. Nothing else needed — `package.json`
is ignored by Pages.

## Before publishing

Fill in these placeholders in `index.html`:

| Placeholder | What goes there |
| --- | --- |
| `[YOUR LEGAL NAME OR COMPANY]` | Your name or registered business name |
| `[YOUR-CONTACT-EMAIL]` | A monitored address — Google requires a working privacy contact |
| `[COUNTRY]` | The country your business operates from |

Whichever URL you end up with goes into **Play Console → App content → Privacy policy**.
It must stay reachable for as long as the app is listed.
