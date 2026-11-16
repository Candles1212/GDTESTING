# GDTESTING

## Metro Dash — Endless Runner

A self-contained browser game built with HTML, CSS, and JavaScript. No frameworks, packages, build step, or external assets are required.

### Run locally
Open `index.html` in a modern browser.

### Controls
- **Left / Right:** change lanes (arrow keys or A/D)
- **Up:** jump (arrow up, W, or Space)
- **Down:** slide (arrow down or S)
- **Mobile:** swipe on the game area or use the on-screen controls
- **Escape:** pause / resume

### Features
- Three-lane endless runner with increasing speed
- Coins, barriers, overhead signs, and roadblocks
- Jumping, sliding, collision detection, and scoring
- Best score saved locally in the browser
- Responsive layout and touch controls
- No external dependencies

### GitHub Pages
In the repository settings, open **Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. The game will be available at the Pages URL GitHub provides.

This is an original arcade game using generic endless-runner mechanics; it does not include Subway Surfers characters, artwork, music, or branding.


## Download the Android APK

The repository includes a GitHub Actions workflow that builds a debug APK.

1. Open the **Actions** tab.
2. Select **Build Metro Dash APK**.
3. Open the latest successful run.
4. Under **Artifacts**, download **Metro-Dash-APK**.
5. Extract the ZIP and install `app-debug.apk` on your Android device. Android may ask you to allow installation from your browser or file manager.

You can also start a build manually from **Actions → Build Metro Dash APK → Run workflow**. Builds are generated automatically when the game or Android configuration changes.
