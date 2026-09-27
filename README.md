# joao-afonso-p.github.io

Redirects `https://joao-afonso-p.github.io/` to <https://joaoafonsopereira.com>, which is built and
deployed from [`joao-afonso-p/website`](https://github.com/joao-afonso-p/website).

Two things here are deliberate, and both keep the project sites (such as `/app-contas/` and
`/beachiness/`) exactly where they are:

- **No custom domain.** A custom domain on this user-site repo would apply to every project site on
  the account and move them to the new origin, stranding the data they keep in browser storage.
- **No `404.html`.** Only the root page redirects. Nothing here can intercept a path that belongs
  to another project site.
