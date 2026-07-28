# Stay — legal pages

Public hosting for the [Stay](https://github.com/kevinginta/stay) app's legal
documents, which Google Play requires to be reachable on the open web.

- `index.html` — Privacy Policy
- `delete-account.html` — Account deletion instructions

**Do not edit these files here.** They are generated from
`src/lib/legal-content.ts` in the app repo, which is also what the in-app
screen renders. Change the text there, run `npm run build:legal`, and copy the
output across — otherwise the hosted and in-app copies drift apart.
