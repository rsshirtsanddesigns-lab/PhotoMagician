# PhotoMagician
Total Package — A browser-based photo editing tool.

## How to View Your Project

### Option 1 — Open directly in your browser (simplest)
1. Download or clone this repository to your computer.
2. Navigate to the project folder.
3. Double-click **`index.html`** — it will open in your default web browser.

### Option 2 — Use VS Code Live Server (recommended for development)
1. Install [Visual Studio Code](https://code.visualstudio.com/).
2. Install the **Live Server** extension (search "Live Server" in the Extensions panel).
3. Open the project folder in VS Code.
4. Right-click `index.html` and choose **"Open with Live Server"**.
5. Your browser will open automatically at `http://127.0.0.1:5500`.

### Option 3 — Use a local web server via the terminal
```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .
```
Then open `http://localhost:8080` in your browser.

### Option 4 — GitHub Pages (share with others)
1. Go to your repository on GitHub.
2. Click **Settings → Pages**.
3. Under *Source*, select **Deploy from a branch**, choose `main` and `/ (root)`.
4. Click **Save**. Your site will be live at `https://<your-username>.github.io/PhotoMagician/`.

## Features
- 📁 Upload any image (JPG, PNG, GIF, WebP)
- 🎨 Apply filters: Grayscale, Sepia, Invert, Vivid, Blur
- 💾 Download the edited image
