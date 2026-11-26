# ELG Signup

A mobile-friendly signup page for Employee-Led Groups (ELGs).

Scan the QR code on the flyer, enter your alias, check the groups you're interested in, and submit. Each group has a "More info" button that shows its description.

## How it works
- `index.html` is the signup page, hosted with GitHub Pages.
- Submissions go to a Google Sheet through a Google Apps Script web app.
  - The "Submissions" tab lists each alias and the groups they chose.
  - Each group has its own tab listing the aliases that signed up.

## Live page
https://mhwiad.github.io/ELG-signup/

## Updating the group list
Edit the `ELGS` list near the top of the script in `index.html`.
