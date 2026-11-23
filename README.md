# Westchester Cockapoos

One-page puppy site for westchestercockapoos.com (West Chester, Ohio). Plain HTML, no build step.

- **Site file:** `public/index.html`. Photos go in `public/images/` (see the README there).
- **Hosting:** Sevalla static site `westchester-cockapoos` (Kinsta's sister company; free tier).
  It deploys from this repo, which is **public**, with publish directory `public`.
- **Deploying:** pushes do NOT auto-deploy (the repo is connected by public URL, not the GitHub app).
  After `git push`, open the site in Sevalla and click **Deploy now → Deploy**.
- **DNS:** Namecheap BasicDNS. A `@` and A `www` point at Sevalla, plus four TXT verification
  records. Keep the two `_acme-challenge` records, because they renew the SSL certificate.
- **Inquiry form:** Web3Forms. Its access key sits in the page and is public by design.
  Submissions are emailed to the account owner; the inbox is at app.web3forms.com.
