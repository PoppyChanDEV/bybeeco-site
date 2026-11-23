# BybeeCo website

Static website for **BybeeCo LLC** and the proposed **Valuark** acquisition analysis product.

## Pages

- `/` — BybeeCo company homepage
- `/valuark/` — Valuark concept and early-access list
- `/deal-xray/` — legacy route redirect to Valuark
- `/valuark/privacy.html` — early-access privacy notice

## Hosting

Designed for GitHub Pages. After reviewing and merging the site PR, open **Settings → Pages** and select **Deploy from a branch → main → /(root)**. GitHub should display a project preview URL, typically `https://poppychandev.github.io/bybeeco-site/`.

**Do not configure the custom domain `bybeeco.net` until the new site is reviewed and the old domain is ready to migrate.** Relative links work from the project preview URL.

## Early-access form

Signup buttons link to the Microsoft Forms response URL supplied by BybeeCo. Before publicly announcing the website:

1. Open the form in a private browsing session and confirm outsiders can respond.
2. Submit and delete a test response.
3. Check consent wording and the early-access privacy notice.
4. Check the website on mobile and desktop.
5. Confirm the proposed $29/month price and all copy are accurate.

## Scope

This site is an **interest test**, not functioning acquisition analysis software. The financial dashboard is hypothetical and clearly labeled as illustrative. There are no AI APIs, payment integrations, advertising trackers, or financial data collection on the website. Cloudflare Web Analytics is included for website traffic measurement. The product signup itself is handled by Microsoft Forms.

Contact: chandler@bybeeco.net

## Analytics verification

Cloudflare Web Analytics beacon is installed on the homepage, product page, and privacy page. After merging, open the Pages preview and navigate between the two public pages, then confirm page activity appears in the Cloudflare Web Analytics dashboard. Analytics reports may not populate immediately, and some browser privacy tools can block measurement.

## Naming transition (Valuark)

Valuark is the **working** brand name pending formal trademark clearance and domain checks. BybeeCo LLC remains the parent company. The former Deal X-Ray URLs redirect via HTML meta-refresh so bookmarks continue to work. The Microsoft Forms signup has been updated to Valuark per the owner's confirmation.

Before promotion, verify that the live form uses the new name and that its email consent wording still matches the published privacy notice. Do not purchase a Valuark domain or represent the trademark as cleared based on web search alone.
