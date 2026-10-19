# Kevin Xiang — Engineering Portfolio

A responsive, dependency-free portfolio webpage designed for GitHub Pages.

## Preview locally

Open `main.html` in a browser, or run a local server:

```powershell
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Personalize before publishing

Edit `main.html` and search for these markers:

- `EDIT:` — replace the experience placeholders and social links.
- `Electrical & Electronic Engineering · 2026` — update the graduation year.
- `Ongoing` and `Next` in the Experience section — add real dates, roles, organizations, and outcomes.
- `https://github.com/` and `https://www.linkedin.com/` — replace with your actual profile URLs.

For stronger project evidence, add a `Selected work` section or replace the capability cards with 2–3 real case studies. Each case study works best with:

1. The problem and why it mattered.
2. Your specific role and constraints.
3. The technical approach and key trade-offs.
4. A measured result, demo, or artifact.

## Publish with GitHub Pages

### Option A — personal site

1. Create a GitHub repository named `<your-github-username>.github.io`.
2. Push this folder’s contents to the `main` branch.
3. The site appears at `https://<your-github-username>.github.io/`.

### Option B — project site

1. Create any repository and push this folder’s contents to `main`.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. The site appears at `https://<your-github-username>.github.io/<repository-name>/`.

`index.html` forwards visitors to `main.html`, which contains the complete site.
