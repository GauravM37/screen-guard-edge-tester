# Screen Guard Edge Tester

A lightweight, offline-friendly browser tool for estimating how many display pixels are hidden by a screen protector, bezel, or display frame.

## Live Demo

After enabling GitHub Pages, the site will be available at:

`https://<your-github-username>.github.io/<repository-name>/`

## Features

- Edge testing for **Top, Bottom, Left, and Right**
- Bright green edge line
- **+1 px / -1 px** adjustment
- Direct pixel-value input
- Fullscreen mode
- Live pixel count and percentage
- Viewport and Screen API information
- Device Pixel Ratio (DPR) display
- Fullscreen warning
- Responsive to viewport/orientation changes
- No external libraries or dependencies
- No server or backend required

## Recommended Testing Conditions

For the most accurate results:

- Use **Google Chrome**.
- Keep browser zoom at **100%**.
- Use **Fullscreen** mode before measuring.
- Set the display brightness high enough to clearly see the green line.

## How to Use

1. Open the page.
2. Read the welcome screen and press **Start Testing**.
3. Press **Fullscreen**.
4. Select an edge.
5. Enter a pixel value directly or use **+1 / -1**.
6. Adjust until the green line reaches the visible boundary you want to measure.
7. Record the displayed value.
8. Repeat for all four edges.

## Important Notes

The tool uses browser-provided viewport and display information. Browser behavior can vary across Android devices, especially around fullscreen, display scaling, rounded corners, punch-hole cameras, notches, and system UI.

The displayed pixel count is intended as a practical screen-protector alignment/coverage measurement, not a hardware-level display diagnostic.

## Project Structure

```text
screen-guard-edge-tester/
├── index.html
├── README.md
├── LICENSE
└── .nojekyll
```

## Deploy to GitHub Pages

### 1. Create the repository

On GitHub, create a new repository, for example:

`screen-guard-edge-tester`

For a GitHub Free account, use a **public repository** for GitHub Pages. citeturn154224search5

### 2. Copy the files

Put these files in the repository root:

- `index.html`
- `README.md`
- `LICENSE`
- `.nojekyll`

GitHub Pages looks for `index.html` at the top level of the selected publishing source. citeturn154224search7

### 3. Push with Git

```bash
git init
git add .
git commit -m "Initial release v7.0"
git branch -M main
git remote add origin https://github.com/<your-github-username>/screen-guard-edge-tester.git
git push -u origin main
```

### 4. Enable GitHub Pages

In the repository:

`Settings` → `Pages`

Under **Build and deployment**:

- **Source:** `Deploy from a branch`
- **Branch:** `main`
- **Folder:** `/ (root)`

Then click **Save**. This is the standard branch-based GitHub Pages setup documented by GitHub. citeturn154224search8

### 5. Open the site

For a repository named `screen-guard-edge-tester`, the project-site URL will normally be:

`https://<your-github-username>.github.io/screen-guard-edge-tester/`

GitHub Pages turns a repository into a live website without separate hosting. citeturn154224search4

## HTTPS

GitHub Pages sites on `github.io` are served over HTTPS automatically, and GitHub provides an option to enforce HTTPS from the Pages settings. citeturn154224search0

## License

This project is provided under the MIT License. See `LICENSE`.
