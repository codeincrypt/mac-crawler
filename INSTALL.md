# Download and install

Requires macOS 14 or later (Apple Silicon or Intel).

1. Go to the [Releases page](https://github.com/codeincrypt/mac-crawler/releases/tag/v0.1.0) and download `MacCrawlers-0.1.0.dmg`.
2. Open the DMG and drag **Mac Crawlers** onto **Applications**.
3. Open **Mac Crawlers** from Applications.
   - If macOS says it can't verify the developer, right-click the app, choose **Open**, then **Open** again.
   - Or, from Terminal: `xattr -dr com.apple.quarantine "/Applications/Mac Crawlers.app"`
4. Allow **Screen Recording** and **Accessibility** when asked, then quit and reopen the app once.

The app has no Dock icon or window. Look for the spider's face in the notch (or the menu bar), and click it to start.

## Settings

Right-click the notch face, or click the menu-bar icon, to open the menu. Settings are saved on this Mac and kept between launches.

| Setting | Options | What it does |
|---|---|---|
| **Animal** | Spider (default), Centipede | Which creature crawls. A spider has 8 legs; a centipede has a 15-segment body with a pair of legs on each segment. The face in the notch changes to match. |
| **Size** | Small, Medium (default), Large | Scales the creature: Small is 75%, Medium 100%, Large 130%. |
| **Effects** | Calm, Normal (default), Wild | How much glitching happens on the words it touches. Calm makes fewer, slower effects and fewer threads. Wild makes many, fast, with more threads and a higher limit on effects on screen at once. |
| **Chase the cursor** | on (default) | The creature runs after the mouse pointer while it moves. |
| **Crawl by itself after 10 s idle** | on (default) | With no mouse or keyboard input for 10 seconds it comes out on its own, and goes back when you move. |
| **Keep Mac awake while crawling** | on (default) | The display and Mac do not sleep while the creature is out. |
| **Keep Mac awake always** | off (default) | Keeps the Mac awake all the time, even when the creature is in the notch. |
| **Launch at login** | on after first run | Starts the app when you log in. |

The menu also has **Release / Recall** (shortcut `⌃⌥S`), shortcuts to the **Screen Recording** and **Accessibility** permissions, and **Quit**.
