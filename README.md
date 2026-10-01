# Pompom Hills Privacy & Data Information

Static legal-information website for **Pompom Hills Creative Intelligence**. The site is intended to provide the public Privacy Policy and User Data Deletion Instructions required for Meta App Review.

It contains only static HTML and CSS. There is no build process, backend, JavaScript, tracking, analytics or cookie functionality.

> This repository contains policy templates, not legal advice. Have the final text reviewed for the business and applicable jurisdiction before relying on it.

## Contact email

The published pages use the existing Pompom Hills support address:

```text
admin@pompomhills.com
```

Confirm that this inbox remains actively monitored before deployment. The visible email text and each `mailto:` link use the same address.

## Files

```text
index.html          Privacy Policy
 data-deletion.html User Data Deletion Instructions
styles.css          Shared responsive styling
README.md           Deployment and review instructions
.gitignore          Secret and local-file exclusions
```

## Local preview

The files work when opened directly in a browser. For a local HTTP preview, run this command from the repository directory:

```bash
python3 -m http.server 8080
```

Then open:

- `http://localhost:8080/`
- `http://localhost:8080/data-deletion.html`

Stop the local server when finished.

## Deploy with GitHub Pages

1. Create a public GitHub repository named `pompom-hills-privacy`.
2. Add these files at the repository root and push them to the `main` branch.
3. Open the repository on GitHub.
4. Go to **Settings** → **Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch **main** and folder **/ (root)**.
7. Click **Save**.
8. Wait for GitHub Pages to report a successful deployment.
9. Open both public URLs in a private/incognito browser window to confirm that no login is required.

No GitHub username is hardcoded in the site. Replace `USERNAME` below with the GitHub account or organisation that owns the public repository.

## Expected public URLs

Site root / Privacy Policy:

```text
https://USERNAME.github.io/pompom-hills-privacy/
```

User Data Deletion Instructions:

```text
https://USERNAME.github.io/pompom-hills-privacy/data-deletion.html
```

## URLs to enter in Meta App settings

**Privacy Policy URL**

```text
https://USERNAME.github.io/pompom-hills-privacy/
```

**User Data Deletion Instructions URL**

```text
https://USERNAME.github.io/pompom-hills-privacy/data-deletion.html
```

## Before-deployment checklist

- [ ] Confirm `admin@pompomhills.com` is actively monitored.
- [ ] Verify the “Last updated” dates.
- [ ] Confirm the final GitHub Pages URLs.
- [ ] Open both pages on desktop and mobile widths.
- [ ] Test navigation in both directions.
- [ ] Confirm the repository contains no secrets.
- [ ] Confirm `.env` files remain ignored.
- [ ] Confirm no Meta access token is committed.
- [ ] Confirm no Meta App Secret is committed.
- [ ] Confirm no private key or credential file is committed.
- [ ] Have the final policy wording reviewed for the business and applicable jurisdiction.

## Security

Never add any of the following to this repository:

- Meta App Secret
- Meta User Access Token
- Meta Page Access Token
- Instagram access token
- API credentials
- private keys
- `.env` files

The public legal website does not need access to any application credential.
