# Siyu Xiang — AI Communication Engineering Portfolio

A responsive, dependency-free portfolio webpage designed for GitHub Pages.

The page features Siyu Xiang's portrait and his undergraduate thesis, *Design of a Dual-Band Monopole Antenna for Wi-Fi and Bluetooth Applications*, completed in the AI Communication Engineering program at Zhejiang Gongshang University.

## Preview locally

Open `main.html` in a browser, or run a local server:

```powershell
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Personalize before publishing

Edit `main.html` and search for these markers:

- `EDIT:` — update social links and add future roles as your experience grows.
- `AI Communication Engineering · Zhejiang Gongshang University` — update the headline if needed.
- `2022–2026` and `Next` in the Experience section — refine dates and future goals.
- `https://github.com/` and `https://www.linkedin.com/` — replace with your actual profile URLs.

The portrait is stored at `assets/siyu-xiang.jpg`. The original `personal information/` folder is excluded from Git because the thesis filing form contains a student ID and private declarations.

The thesis section currently presents the verified title and program details. For stronger project evidence, add the methods, simulation setup, measurements, and final antenna results from the full thesis. A case study works best with:

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
