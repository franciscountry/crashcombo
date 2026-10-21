# crashcombo

Source for crashcombo.com, served by GitHub Pages from the root of `main`.

## Custom domain (when ready)

1. At the registrar, point the domain at GitHub Pages:
   - apex `crashcombo.com`: A records to 185.199.108.153, 185.199.109.153,
     185.199.110.153, 185.199.111.153 (AAAA: 2606:50c0:8000::153 through 8003::153)
   - `www`: CNAME to `franciscountry.github.io`
2. Repo Settings, Pages, Custom domain: enter `crashcombo.com`. GitHub commits a
   `CNAME` file for you.
3. Once the certificate is issued, tick "Enforce HTTPS".
