# ProcessHub — Process Engineering Interactive Website

A responsive, polished single-page portfolio website combining all ten process engineering projects into one interface.

## Included features
- Responsive dark engineering dashboard design
- Font Awesome 6.7.2 icons and Google Fonts
- Animated hero visual, cards, scroll reveals and responsive navigation
- Search and category filters for all ten projects
- Interactive modal workspaces for each project
- Working browser-based calculators: mass balance, heat exchanger, pump and energy
- Demonstration simulations: PID response, tank level, process monitoring, AI-style risk scoring, anomaly thresholds and oil & gas process split
- Simulated operating trend chart and equipment overview
- No backend or build step required

## Run locally
Open `index.html` in a modern browser, or use VS Code Live Server.

## Deploy to GitHub Pages
1. Create a repository, e.g. `process-engineering-hub`.
2. Upload `index.html`, `styles.css`, `script.js` and this README.
3. In GitHub, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/root`, then save.
5. Wait for the published Pages URL to appear.

## Technical notes
- HTML5, CSS3 and vanilla JavaScript.
- Font Awesome is loaded from cdnjs; Google Fonts are loaded from Google Fonts. Internet access is required for these external assets.
- All interactive calculations run client-side.
- The dashboard values and trend chart are illustrative synthetic demo data.

## Engineering and safety disclaimer
This website is an educational portfolio demonstration, not validated engineering software. Equations and thresholds are simplified, example values are illustrative, and AI-related modules use transparent heuristics rather than a trained production model. Do not use outputs for plant operation, equipment sizing, process safety decisions, regulatory compliance or control of live assets. Real engineering work requires verified data, appropriate standards, uncertainty analysis, qualified review and site-specific validation.
