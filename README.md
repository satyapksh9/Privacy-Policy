# Android app privacy policy

This repository hosts the **HTML privacy policy** for the Android app. Replace `privacy-policy.html` with your final file (or edit it in place), then push to GitHub.

## Host the policy

After pushing, enable **GitHub Pages** (optional) so you get a stable public URL for the Play Console:

1. Repository → **Settings** → **Pages**
2. **Source**: Deploy from branch `main`, folder `/ (root)`
3. **Custom domain**: leave this **empty** unless you own a real domain (e.g. `policy.example.com`).  
   Do **not** enter `satyapksh9.github.io`, any path, or `https://…` — that field is only for [domains you control](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages). Putting a full `github.io/.../file.html` URL there triggers a [format error](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site/troubleshooting-custom-domains-and-github-pages#github-repository-setup-errors).
4. After the site builds, open your policy at:  
   `https://satyapksh9.github.io/Privacy-Policy/privacy-policy.html`  
   (The middle segment must match your **exact** repository name, including capital letters.)

Use that full HTTPS link in Google Play — **not** the Custom domain box in Settings.

## Push this folder to a new GitHub repo

1. Log in (one time):

   ```bash
   gh auth login
   ```

2. Create the repo and push (run from this directory):

   ```bash
   cd /Users/satya/Privacy-Policy
   gh repo create android-app-privacy-policy --public --source=. --remote=origin --push
   ```

   To use a different name, change `android-app-privacy-policy`.

**Without `gh`:** create an empty repo at [github.com/new](https://github.com/new), then:

```bash
git remote add origin https://github.com/satyapksh9/<repo-name>.git
git push -u origin main
```

## Files

| File | Purpose |
|------|---------|
| `privacy-policy.html` | Policy page (replace with your content) |
