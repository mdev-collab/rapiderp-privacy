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

## Where the URL goes

**Play Console → App content → Privacy policy.** It must stay reachable for as
long as the app is listed — if it goes dark, Google can flag the listing.

## Keeping it accurate

The policy describes what the app actually collects. If any of these change,
update `index.html` to match — and re-check the **Data safety** form in the
Play Console, which must agree with this page:

- Google sign-in data (name, email, avatar URL)
- Session / install analytics events
- Expo push tokens
- Business data staying on-device only
