# Lake Timp Rentals Closed Page

Static replacement site for `laketimprentals.com` while Lake Timp Rentals is not operating.

## What this does

- Shows a single closed-business landing page.
- Includes no booking links, scripts, calendars, payment forms, or Wix embeds.
- Includes a `CNAME` file for GitHub Pages custom-domain setup.
- Uses the supplied screenshot as a muted background reference asset.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the repository.
3. In GitHub, open **Settings -> Pages**.
4. Set **Source** to deploy from the default branch.
5. Confirm the custom domain is `laketimprentals.com`.

## DNS for the custom domain

For the apex domain `laketimprentals.com`, point DNS to GitHub Pages:

```text
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
```

For `www.laketimprentals.com`, add:

```text
CNAME www   <your-github-username>.github.io
```

After DNS resolves, enable **Enforce HTTPS** in GitHub Pages.
