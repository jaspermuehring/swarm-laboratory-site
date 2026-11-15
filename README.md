# Swarm Laboratory public website

Public website and privacy policy for Swarm Laboratory.

A buildless public identity website for a private research application. Only these independently authored public files belong here; never copy research code, runs, private reasoning, credentials, or private configurations into this repository.

## Publication status and policy maintenance

The operator approved the public contact, identity, and data-use commitments on November 14, 2026. The privacy policy is effective November 14, 2026. Retain an accurate effective date on future revisions.

Contact: jasper.muehring@gmail.com. Operator: Independently operated Swarm Laboratory research project.

### Integration prerequisites, not website publication blockers

Google document operations, credential protection, and automated document permissions are planned, not implemented. Before enabling them, verify provider terms/settings, permitted user-facing use cases, affirmative consent for external transfers and human inspection, secure handling, and Google-compatible retention/deletion. Ordinary research logging must not become indefinite retention of Google content by default. The policy is a commitment, not Google approval or a compliance certification. Non-sensitive drive.file limits file access but does not waive applicable user-data obligations.

Official review references:
- https://developers.google.com/terms/api-services-user-data-policy
- https://developers.google.com/workspace/workspace-api-user-data-developer-policy
- https://developers.google.com/workspace/drive/api/guides/api-specific-auth
## Files and local review

- index.html: project scope, research focus, planned authorized integration.
- privacy.html: approved data-use commitments and accurate current/planned distinctions.
- styles.css: responsive shared styling; no remote fonts, scripts or framework.
- README.md: deployment and maintenance (this file).
- .nojekyll: serve plain static files without a Jekyll build.

Open index.html and privacy.html directly in a browser for review. No server, installation, JavaScript, or build is required. Check phone and desktop widths, keyboard navigation and visible focus. Automated static checks do not replace browser or legal review.

## Publish to the EXISTING website repository — manual only

Do not run these commands in the private Swarm-Laboratory directory. The preparation step has not authenticated, initialized Git, committed, pushed, or published anything.

The safest route works even if the existing public repository already contains commits:

1. Confirm the publication date and apply the effective-date instruction above. Review the five public files before upload.
2. In your browser, sign in yourself and open https://github.com/jaspermuehring/swarm-laboratory-site . Confirm the owner and repository name.
3. Use Add file > Upload files. Upload ONLY index.html, privacy.html, styles.css, README.md, and .nojekyll at the repository root. Show hidden files if needed to select .nojekyll. Review existing files and the proposed changes; do not remove unrelated files. Commit through GitHub after your review.
4. Open Settings > Pages. Under Build and deployment choose Deploy from a branch. Select the repository's actual default branch (normally main), choose /(root), then Save. If already configured, verify the settings instead of changing them unnecessarily.
5. Wait for the Pages deployment to succeed in Actions/Pages. Verify the two URLs below return the intended pages over HTTPS, and test navigation and CSS on mobile and desktop.
6. Only after publication and policy approval, enter the homepage and privacy URLs in Google Auth Platform. Follow any domain ownership or verification requirements Google presents; creating these files alone does not establish OAuth production approval. A custom domain may require separate setup if Google's verification flow cannot be satisfied with the project-hosted URL.

Expected homepage: https://jaspermuehring.github.io/swarm-laboratory-site/
Expected privacy: https://jaspermuehring.github.io/swarm-laboratory-site/privacy.html
Intended Google Cloud project: swarm-laboratory-research (identifier only; this site changes no cloud settings).

Official publishing instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
Google user data policy: https://developers.google.com/terms/api-services-user-data-policy

## Maintenance

Review the policy before every change to Google scopes, operations, model providers, data destinations, retention, or access controls. Keep a truthful effective date and obtain any required renewed notice/consent. Keep all navigation and asset links relative for project hosting. Do not add analytics, forms, third-party fonts, or trackers without corresponding review. GitHub hosting processes visitor data independently of this static site's code. Public Git history can retain removed material: inspect changes BEFORE upload. This directory is under OneDrive Documents and may be synchronized; it contains public website material only.
