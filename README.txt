# YOUR NAME — Music Site

## SETUP

1. **Add your MP3:**
   - Drop your MP3 file into the `Songs/` folder
   - Rename it to `track.mp3`  
     OR edit `songs-manifest.json` and change `"file"` to your actual filename
   - Change `"name"` in the manifest to your track's display name

2. **Change the site name:**
   - Open `index.html` and `player.html`
   - Find every place that says `YOUR NAME` and replace it with your actual name

3. **Change login credentials:**
   - Open `index.html`
   - Find this line: `const CREDENTIALS = { username: 'admin', password: 'music123' };`
   - Change `admin` and `music123` to whatever you want

4. **Host it:**
   - Upload the entire folder to any web host (GitHub Pages, Netlify, etc.)
   - Make sure the `Songs/` folder and your MP3 go up with it

## FILES
```
musicsite/
├── index.html          ← Login page
├── player.html         ← Music player
├── style.css           ← All styles
├── songs-manifest.json ← Points to your MP3
└── Songs/
    └── track.mp3       ← YOUR MP3 GOES HERE
```

## FEATURES
- Black & white aesthetic with glitch animations
- Film grain noise overlay + scanlines
- Working login (session-based)
- Auto-plays your track on login
- Circular audio visualizer
- Progress bar (click to seek)
- Volume slider
- Play/pause, loop, mute controls
- Spinning rings animate while playing
