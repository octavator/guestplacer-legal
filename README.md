# Guestplacer — support & legal pages

Hosted **Support**, **Privacy Policy** and **Terms of Use** pages for the Guestplacer mobile app,
published with GitHub Pages. The app itself lives in a separate (private) repository;
this repo holds only the public pages that the app and its store listings link to.

- Support → [`support.html`](./support.html)
- Privacy Policy → [`privacy.html`](./privacy.html)
- Terms of Use → [`terms.html`](./terms.html)

Live: https://octavator.github.io/guestplacer-legal/

Plain static HTML with one shared `style.css`. `.nojekyll` makes GitHub Pages serve the files as they are.
When the app's data handling changes (for example when in-app purchases are added), update
`privacy.html` and its effective date along with the store privacy answers.
