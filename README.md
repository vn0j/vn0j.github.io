# vn0j.dev

Personal portfolio, deployed with GitHub Pages.

## Local preview

Open `index.html` in a browser. The page is static and needs no build step.

## Domain

The `CNAME` file sets `vn0j.dev`. At Name.com, point the domain to GitHub Pages:

- Apex (`@`): `A` records `185.199.108.153`, `185.199.109.153`,
  `185.199.110.153`, and `185.199.111.153`.
- `www`: `CNAME` record to `vn0j.github.io`.

Remove conflicting `A`, `AAAA`, or `CNAME` records for these hosts before
adding the GitHub Pages records. Enable HTTPS in the repository's Pages
settings after DNS has propagated.
