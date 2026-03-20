# Android app privacy policy

This repository hosts the **HTML privacy policy** for the Android app. Replace `privacy-policy.html` with your final file (or edit it in place), then push to GitHub.

## Host the policy

After pushing, enable **GitHub Pages** (optional) so you get a stable public URL for the Play Console:

1. Repository → **Settings** → **Pages**
2. **Source**: Deploy from branch `main`, folder `/ (root)`
3. Your policy URL will look like:  
   `https://satyapksh9.github.io/<repo-name>/privacy-policy.html`

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
