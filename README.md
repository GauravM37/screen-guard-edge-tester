# Screen Guard Edge Tester

A lightweight, offline-friendly browser tool for estimating how many display pixels are hidden by a screen protector, bezel, or display frame.

## Live Demo

After enabling GitHub Pages, the site will be available at:

`https://gauravm37.github.io/screen-guard-edge-tester/
`

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
