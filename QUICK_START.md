# 🚀 Quick Start Guide - Pomodoro Timer

## Instant Setup (30 seconds)

### Option 1: Local File (Recommended)
1. Download `index.html` to your computer
2. Double-click the file
3. Your browser will open the app
4. Done! Start focusing immediately

### Option 2: Drag & Drop
1. Download `index.html`
2. Drag the file into any open browser window
3. The app loads instantly
4. Start your first pomodoro!

---

## First Time Setup

### 1. Allow Notifications (Optional but Recommended)
- When prompted, click **"Allow"** to enable browser notifications
- You'll be notified when each pomodoro session completes
- Can be toggled later in Settings

### 2. Set Your Preferences
1. Click the **⚙️ Settings** icon (top right)
2. Adjust timer durations if needed:
   - Work session: 25 minutes (default)
   - Short break: 5 minutes
   - Long break: 15 minutes
3. Set your daily pomodoro goal (default: 8)
4. Toggle dark mode with the **🌙** icon

### 3. Add Your First Task
1. Click the task input field or press **N**
2. Type: "Complete project proposal"
3. Press **Enter** or click **+**
4. Your task appears in the list!

### 4. Start Your First Pomodoro
1. Click on your task to make it active (turns blue)
2. Press **Space** or click the **▶ Start** button
3. Focus for 25 minutes
4. Take a 5-minute break when the timer ends
5. Repeat!

---

## Quick Tips

### Maximize Productivity
- ✅ Work on ONE task per pomodoro
- ✅ Eliminate distractions before starting
- ✅ Take breaks seriously - they're part of the technique
- ✅ Track all your tasks, even small ones
- ✅ Review your daily stats to see progress

### Keyboard Power User
- **Space** - Start/Pause (fastest way!)
- **Escape** - Reset timer
- **N** -Add new task quickly
- **Enter** (in task input) - Save task

### Best Practices
1. **Morning**: Add all your tasks for the day
2. **Before each pomodoro**: Select which task to focus on
3. **During pomodoro**: No checking email, phone, or social media
4. **During breaks**: Stand up, stretch, hydrate
5. **End of day**: Review stats, clear completed tasks

---

## Hosting Options

### For Personal Use
Just open the HTML file locally - no hosting needed!

### For Sharing/Team Use

#### Option A: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload `index.html`
3. Go to Settings → Pages
4. Select main branch
5. Share the URL: `https://yourusername.github.io/repo-name`

#### Option B: Netlify (Free)
1. Go to netlify.com
2. Drag and drop `index.html`
3. Get instant URL like `https://random-name.netlify.app`
4. (Optional) Connect custom domain

#### Option C: Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. In folder with `index.html`, run: `vercel`
3. Follow prompts
4. Get production URL

#### Option D: Your Own Server
Simply upload `index.html` to your web server. Works anywhere:
- Apache
- Nginx
- Any static hosting service
- Even a Raspberry Pi!

---

## Troubleshooting

### Timer not starting?
- Make sure you clicked Start or pressed Space
- Check browser console for errors (F12)
- Try refreshing the page

### Notifications not working?
- Click the 🔔 icon in browser address bar
- Select "Allow notifications"
- Check Settings → Enable "Browser Notifications"

### Tasks not saving?
- Ensure localStorage is enabled in your browser
- Check you're not in Incognito/Private mode
- Try clearing browser cache and reload

### Stats reset?
- Stats reset daily at midnight
- This is intentional to track daily progress
- Historical data feature coming in future versions

### Dark mode stuck?
- Check localStorage isn't full
- Try the toggle button again
- Clear site data and reload

---

## Advanced Usage

### Backup Your Data
1. Open browser Dev Tools (F12)
2. Go to Console tab
3. Type: `localStorage.getItem('pomodoroState')`
4. Copy the JSON output
5. Save to a text file

### Restore Data
1. Open Dev Tools Console
2. Paste your backup JSON
3. Type: `localStorage.setItem('pomodoroState', 'YOUR_JSON_HERE')`
4. Refresh page

### Reset Everything
1. Open Settings
2. Scroll to bottom
3. Click "Clear All Data" (coming soon)
OR
4. Open Dev Tools Console
5. Type: `localStorage.clear()`
6. Refresh page

---

## Mobile Setup

### iOS (iPhone/iPad)
1. Open `index.html` in Safari
2. Tap Share button
3. Select "Add to Home Screen"
4. Name it "Pomodoro Timer"
5. Now opens like a native app!

### Android
1. Open `index.html` in Chrome
2. Tap ⋮ menu
3. Select "Add to Home screen"
4. Accept the prompt
5. Find app icon on home screen

---

## Browser Recommendations

**Best Experience:**
- Chrome 90+ (recommended)
- Edge 90+
- Firefox 88+

**Works Well:**
- Safari 14+
- Opera 76+
- Brave (based on Chrome)

**Not Recommended:**
- Internet Explorer (not supported)
- Very old browser versions

---

## Performance Tips

### For Smooth Operation
- Close unused browser tabs
- Don't run intensive tasks while timer is active
- Keep browser updated
- Use hardware acceleration (usually on by default)

### Low-End Devices
- Disable animations in browser settings if laggy
- Close other applications
- Use a lightweight browser like Firefox

---

## Need Help?

### Resources
- Read the full README.md for detailed documentation
- Check browser console (F12) for error messages
- Ensure you're using a modern browser

### Common Questions

**Q: Can I use this offline?**  
A: Yes! Once loaded, works completely offline.

**Q: Does it work on mobile?**  
A: Absolutely! Fully responsive design.

**Q: Will my data sync across devices?**  
A: Not yet. Currently localStorage-based (local only). Cloud sync planned for future.

**Q: Can I customize the tomato emoji?**  
A: Currently no, but you can edit the HTML file if you know basic code!

**Q: Is my data private?**  
A: 100% private. Everything stays on your device. No servers, no tracking, no analytics.

---

**🍅 You're all set! Start your first pomodoro and build that focus muscle!**

Remember: The Pomodoro Technique is simple, but powerful. Consistency is key. Happy focusing!
