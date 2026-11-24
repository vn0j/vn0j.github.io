# vn0j.dev

Personal portfolio, deployed with GitHub Pages.

## Local preview

Open `index.html` in a browser or use any static file server. There is no
build step; the scroll reveals and progress bar are vanilla JavaScript.

## Custom domain

After registering `vn0j.dev`, set it as the custom domain in the repository's
Pages settings and add a `CNAME` file containing `vn0j.dev`. At Name.com, add:

- Apex (`@`): `A` records `185.199.108.153`, `185.199.109.153`,
  `185.199.110.153`, and `185.199.111.153`.
- `www`: `CNAME` record to `vn0j.github.io`.

Remove only conflicting web-host records for `@` and `www`; leave mail-related
MX/TXT records alone. Enable HTTPS in the repository's Pages settings after
DNS has propagated. Until then, the site is available at
`https://vn0j.github.io`.
