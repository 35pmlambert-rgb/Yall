# How to Build Hammer Bounce Brawler as a Standalone .exe

## Step 1: Download Nw.js
1. Go to https://nwjs.io/
2. Download **nwjs-v0.85.0-win-x64.zip** (or latest version for Windows)
3. Extract it to a folder on your computer

## Step 2: Prepare Game Files
1. Download these files from the GitHub repo:
   - `index.html`
   - `package.json`

2. Place them in a folder called `game` on your desktop

## Step 3: Copy to Nw.js Folder
1. Copy your `game` folder contents (index.html, package.json) 
2. Paste into the **nwjs folder** you extracted earlier

## Step 4: Test It
1. In the nwjs folder, double-click `nw.exe`
2. Your game should launch!

## Step 5: Create the .exe
1. **Windows only**: Use **NW.js Builder** or follow this method:
   - Download: https://github.com/evshiron/nwjs-builder-phoenix
   - Or use this simple method:
     - Zip your game files: `index.html` + `package.json`
     - Rename to `game.nw`
     - Open command prompt in nwjs folder
     - Run: `copy /b nw.exe + game.nw game.exe`
     - Your `game.exe` is ready!

## Alternative (Easiest): Use PyInstaller + CEFPython
If you want a simpler method, I can create a Python wrapper that builds the .exe automatically.

## Questions?
If you get stuck, let me know and I can provide more detailed steps!
