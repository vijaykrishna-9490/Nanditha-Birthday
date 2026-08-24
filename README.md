# 🎁 Happy Birthday Nanditha - Interactive Birthday Website

A beautiful, fully interactive birthday website with animations, passcode protection, countdown, gift selection, and more!

## ✨ Features

### 🎉 Complete Journey
1. **Home Page** - Beautiful gift box with animations
2. **Passcode Protection** - Enter code `2508` to unlock
3. **Image Reveal** - Tap to see special photo
4. **Countdown** - 5-second countdown with confetti
5. **Birthday Wish** - Personalized message for Nanditha
6. **Gift Decision** - Accept the gift (Yes/No)
7. **Gift Selection** - Choose from:
   - 💌 Love Letter with photo
   - 🌹 Build Your Custom Bouquet
   - 🎀 Special Gift Box
8. **Beautiful Animations** - Floating stars, hearts, balloons throughout

### 🎨 Design Features
- ✨ Smooth page transitions
- 🎊 Confetti effects
- 💫 Floating decorative elements
- 🌈 Beautiful gradient backgrounds
- 📱 Fully responsive (mobile-first design)
- 🎭 Interactive buttons with hover effects
- 🎵 Engaging animations on every page

## 🚀 Quick Start

### Option 1: Deploy to Vercel (Recommended)

1. **Create a GitHub Repository:**
   - Go to GitHub.com and create a new repository
   - Name it something like `nanditha-birthday`
   - Clone it to your computer

2. **Add Files:**
   ```bash
   # Copy all files to your repository:
   # - index.html
   # - package.json
   # - vercel.json (create this)
   ```

3. **Create vercel.json:**
   ```json
   {
     "buildCommand": "echo 'build complete'",
     "outputDirectory": ".",
     "regions": ["sfo1"]
   }
   ```

4. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit: Birthday website for Nanditha"
   git push origin main
   ```

5. **Deploy on Vercel:**
   - Go to https://vercel.com
   - Sign up with GitHub (if not already)
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Your website is now live! 🎉

### Option 2: Run Locally

```bash
# Simply open the index.html file in your browser
# Or use a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📋 Website Flow

```
Home (Click Gift) 
  ↓
Passcode Page (Enter: 2508)
  ↓
Image Reveal Page
  ↓
Countdown (5...)
  ↓
Birthday Wish Page
  ↓
Accept Gift? (Yes/No)
  ├─ No → Why message → Back to gifts
  ├─ Yes → Gift Selection
     ├─ Letter → Love Letter with Photo
     ├─ Bouquet → Build Your Custom Bouquet
     └─ Gift Box → Special Surprise
```

## 🎨 Customization

### Change the Passcode
In `index.html`, find the passcode check:
```javascript
if (passcode === '2508') {  // Change 2508 to your code
```

### Personalize the Letter
Find the letter section in the `LetterPage` function and edit:
```javascript
<p>
    Happy birthday to the most amazing person in my life! 
    // Edit this message
</p>
```

### Change Background Colors
All gradient backgrounds use Tailwind colors. Example:
```javascript
background: 'linear-gradient(to bottom, #fce7f3, #faf5ff)'
// Change to: background: 'linear-gradient(to bottom, #your-color, #your-color)'
```

### Add Photo to Letter
Replace the placeholder in the `LetterPage`:
```javascript
<div style={{
    background: 'white',
    borderRadius: '1rem',
    padding: '1rem',
    marginBottom: '1.5rem',
    // Add an <img> tag here
}}>
```

## 🛠️ Technologies Used

- **React 18** - UI framework
- **React DOM** - DOM rendering
- **HTML5** - Structure
- **CSS3** - Animations & styling
- **Tailwind CSS** - Utility classes
- **JavaScript** - Interactivity

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🎯 Perfect For

- Birthdays 🎂
- Anniversaries 💕
- Special occasions 🎉
- Confessions 💘
- Any celebration! 🎊

## 🚀 Deployment Links

Once deployed on Vercel, you'll get a URL like:
```
https://nanditha-birthday.vercel.app
```

Share this link with Nanditha to open the website!

## 💡 Tips

1. **Mobile First**: This website is optimized for mobile viewing
2. **Full Screen**: Ask Nanditha to open it on a phone for the best experience
3. **Share the Link**: Send the Vercel link via WhatsApp, Telegram, Email, etc.
4. **Test Before Sharing**: Open the local version first to make sure everything works
5. **Passcode Hint**: Make the hint (currently "Think about something special...") meaningful to you both

## 🎁 Additional Features

Each page includes:
- ⭐ Floating stars and hearts
- 💝 Birthday elements (cakes, gifts, balloons)
- ✨ Smooth animations
- 🎨 Beautiful gradients
- 🎯 Interactive buttons

## 📞 Support

If you need to modify anything:
1. Edit the `index.html` file
2. Save changes
3. Commit and push to GitHub
4. Vercel will auto-deploy

## 🎉 That's It!

You now have a beautiful, interactive birthday website for Nanditha! 

**Enjoy! 💕✨🎊**

---

Made with ❤️ for Nanditha's Birthday
