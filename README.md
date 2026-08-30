# Budget Tracker PWA

Personal budget tracker with real-time sync between devices.

## Setup Instructions

### Deploy to GitHub Pages

1. Open a terminal/command prompt
2. Navigate to this folder:
   ```
   cd C:\Users\swicjeff\Documents\Personal\budget-tracker-pwa
   ```
3. Initialize git and push:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/jeffreyswick8/budget-tracker.git
   git push -u origin main
   ```
4. Go to https://github.com/jeffreyswick8/budget-tracker/settings/pages
5. Under "Source", select **Deploy from a branch**
6. Select **main** branch and **/ (root)** folder
7. Click **Save**
8. Wait 1-2 minutes, then visit: **https://jeffreyswick8.github.io/budget-tracker/**

### Install on Phone

**iPhone:**
1. Open Safari and go to https://jeffreyswick8.github.io/budget-tracker/
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Name it "Budget" and tap Add

**Android:**
1. Open Chrome and go to https://jeffreyswick8.github.io/budget-tracker/
2. Tap the three-dot menu
3. Tap "Add to Home screen" or "Install app"
4. Confirm

### That's it!
Both phones will see the same data in real-time via Firebase sync.
The green dot next to "Budget Tracker" means you're connected.
Red dot means offline (data saves locally and syncs when reconnected).
