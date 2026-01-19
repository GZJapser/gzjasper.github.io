# Wellness Pup 🐕

Your adorable Maltese puppy companion that reminds you to stand up and stretch during work hours!

## Features

✨ **Realistic Maltese Puppy Design** - Life-like illustration with fluffy white fur, expressive eyes, and sweet personality  
📅 **Smart Workday Scheduling** - Automatic Mon-Fri detection with customizable work hours  
🔔 **Intelligent Reminders** - 2-hour intervals with lunch break handling (11:30 AM - 1:30 PM)  
⚙️ **Fully Customizable** - Adjust work days, hours, and reminder frequency  
📱 **PWA Support** - Install on iPhone home screen like a native app  
🎨 **Premium Design** - Delicate, modern UI with smooth animations  

## Quick Start

### Option 1: Use Locally
1. Open `index.html` in your browser
2. Allow notifications when prompted
3. Start staying healthy!

### Option 2: Deploy Online (Recommended for iPhone)

#### Deploy to GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files from the `wellness-reminder` folder
3. Go to Settings → Pages
4. Select "main" branch and save
5. Your app will be live at `https://yourusername.github.io/repository-name`

#### Deploy to Netlify (Free)
1. Go to [netlify.com](https://www.netlify.com/)
2. Drag and drop the `wellness-reminder` folder
3. Your app will be live instantly with a custom URL

#### Deploy to Vercel (Free)
1. Go to [vercel.com](https://vercel.com/)
2. Import the project
3. Deploy with one click

## Installing on iPhone

Once deployed online:

1. **Open in Safari** - Navigate to your deployed URL
2. **Tap Share Button** - The square icon with an arrow pointing up
3. **Add to Home Screen** - Scroll down and tap this option
4. **Tap Add** - Confirm in the top right
5. **Done!** - The app icon will appear on your home screen

The app will now work like a native iPhone app with:
- Full-screen experience
- Offline functionality
- Push notifications (with permission)
- Fast loading from cache

## Configuration

### Work Schedule
- **Work Days**: Monday - Friday (customizable)
- **Start Time**: 9:00 AM (customizable)
- **Lunch Break**: 11:30 AM - 1:30 PM (customizable)
- **End Time**: 5:30 PM (customizable)

### Reminder Settings
- **Interval**: 2 hours (1, 2, or 3 hours available)
- **Sound**: Enabled (can be toggled off)

All settings are saved locally and persist between sessions.

## File Structure

```
wellness-reminder/
├── index.html          # Main app HTML
├── styles.css          # Styling and animations
├── app.js              # Core functionality
├── sw.js               # Service worker for PWA
├── manifest.json       # PWA manifest
├── maltese-mascot.svg  # Maltese puppy illustration
├── maltese-stretch.svg # Stretching puppy for notifications
└── README.md           # This file
```

## Browser Support

- ✅ Safari (iOS 11.3+)
- ✅ Chrome (Desktop & Mobile)
- ✅ Edge
- ✅ Firefox

## Privacy

- All data stored locally on your device
- No external servers or tracking
- No data collection
- Works completely offline after first load

## License

Free to use for personal wellness! 🐾

---

Made with ❤️ and cute Maltese puppies
