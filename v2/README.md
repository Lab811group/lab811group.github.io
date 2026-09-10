# Lab811 — SIU web-review candidate

Website: https://lab811group.github.io/

This version is prepared for review by SIU Web Communications.

## Changes made for review

- Removed the decorative Lab811 circular mark so the site does not present a secondary logo.
- Removed the homepage graphic and all placeholder member graphics.
- Added a prominent link to Southern Illinois University above the group navigation on every page.
- Added a skip-to-content link and main-content landmark on every page.
- Removed JavaScript and third-party Google Fonts.
- Added visible keyboard focus styles and responsive text-only navigation.
- Added required footer elements:
  - site-maintainer email link
  - SIU Equal Opportunity Employer link
  - SIU Web Privacy Policy link
  - current-year SIU Board of Trustees copyright
  - last-updated date
- Added an Accessibility link.
- Kept the site static: no forms, database, analytics, cookies, login, or collection of sensitive information.

## One item to confirm with SIU Web Communications

SIU Web Standards specify that official University web pages should use the official SIU web logo,
linked to https://siu.edu/, above the fold. The current review candidate uses a plain-text
"Southern Illinois University" institutional link instead of inventing or altering a University logo.

After Web Communications confirms which official web-logo asset they want used, save the approved
asset in `img/` and replace the institutional text link with that approved logo.

Do not create a custom SIU-styled logo for Lab811; SIU's published standards prohibit secondary logos.

## Maintainer email

The footer currently uses `yupeng@siu.edu`, the contact address available in the prior site
draft. Replace this with Prof. Zhang's preferred SIU email before final production if desired.

## Deployment

Copy these files into the local `lab811group.github.io` repository, commit, and push to `main`.
GitHub Pages should redeploy automatically.
