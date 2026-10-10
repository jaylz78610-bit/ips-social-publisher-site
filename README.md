# SMH — Social Media Hub website

A responsive, informational static website for SMH — Social Media Hub, an independent Windows desktop application developed and operated by an individual developer. The site uses plain HTML, CSS, and minimal JavaScript with no framework, package manager, build step, backend, database, or external dependency.

## Files

- `index.html` | product overview, intended workflow, platform availability, and architecture
- `privacy.html` | publication-draft privacy policy reflecting verified current behavior
- `terms.html` | publication-draft terms with proportionate, unapproved warranty and liability wording
- `styles.css` | shared responsive styles
- `script.js` | mobile navigation, current year, and lightweight reveal behavior
- `favicon.svg` | local vector favicon

## Preview locally

You can open `index.html` directly in a browser. For the most reliable local preview, serve the folder over HTTP.

Using Python:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000/>. Stop the server with `Ctrl+C`.

No installation or build command is required.

## Review before publication

The public HTML contains no unresolved TODO markers or hidden placeholders. The Privacy Policy and Terms of Service remain publication drafts and do not claim professional legal approval.

The following matters still require review before the policies are described as final:

- Determine, with advice appropriate to the places where the product will be offered, whether the individual operator's legal identity must be disclosed. SMH is a public-facing brand, not a registered company, and the developer's full personal legal name is intentionally not included in the current website.
- Obtain qualified review of the draft warranty and liability language. No governing-law jurisdiction, court, or arbitration forum has been selected, and the Terms intentionally omit an optional choice-of-law clause.
- Confirm that the October 10, 2026 effective dates remain appropriate for the intended publication. Those dates are not deployment dates or claims of legal approval.

Current operational limitations are disclosed directly rather than left as placeholders: credentials use unencrypted local JSON files excluded from Git; SQLite records have no automatic expiration; in-app disconnection, revocation, and history deletion are unavailable; failed temporary media may remain without a guaranteed maximum period; the exact manual deletion procedure is not formalized; and the media-delivery provider, region, access controls, and complete logging behavior have not been verified for the public policy.

The confirmed public contact for privacy, terms, support, and security concerns is **SMH Support** at [jaylz78610@gmail.com](mailto:jaylz78610@gmail.com). Platform descriptions are deliberately conditional. LinkedIn approval remains pending, and TikTok Direct Post is planned but not implemented or approved for public use.

## Deploy to GitHub Pages

The static files are technically compatible with publication from the repository root at `https://github.com/jaylz78610-bit/ips-social-publisher-site`, with the GitHub Pages base path `/ips-social-publisher-site/`. All page and asset references are relative. No deployment has been performed, and this local directory must be initialized or connected to Git before it can be pushed.

1. Complete the legal and factual review described above; keep the policy pages identified as drafts until that review is complete.
2. Commit the files to the repository’s default branch.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and the **`/ (root)`** folder, then save.
6. Wait for GitHub Pages to report a successful deployment and open the provided URL.
7. Recheck navigation, legal-page links, mobile layout, and the final public wording.

If the repository belongs to an organization, its Pages visibility and custom-domain options depend on the organization’s GitHub plan and policies.

## Content and security notes

- This website is informational only. It contains no authentication, OAuth flow, upload form, or application download.
- Never commit API keys, client secrets, OAuth tokens, signing keys, passwords, or backend configuration.
- Social publishing remains subject to platform permissions, account eligibility, API availability, and platform review.
- Legal text in this project is a practical publication draft. The absence of placeholder markers does not mean that the legal identity or draft terms have been professionally approved.
