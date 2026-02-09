# 🔥 EVIL INSULT ARCADE — HELL MODE 🔥

A demonic, hellscape-themed web application that summons evil insults from the depths of the internet. Features animated fire backgrounds, floating embers, voice synthesis, and explosive visual effects.

![Theme](https://img.shields.io/badge/theme-hellscape-ff2400)
![API](https://img.shields.io/badge/api-evilinsult.com-ff6a00)
![Status](https://img.shields.io/badge/status-burning-ffd000)

## 🎮 Features

- **Animated Hellscape Background**: Multi-layered fire animation with breathing flames and 30+ floating embers
- **Evil Insult Generator**: Fetches creative insults from the Evil Insult API
- **Text-to-Speech**: Demonic voice reads each insult aloud (optional)
- **Hell Particle Explosions**: Emoji particles burst across the screen after each insult
- **Score Tracking**: Persistent high score saved in localStorage
- **Audio Effects**: Optional cackling laugh track
- **Responsive Design**: Works on desktop and mobile devices
- **Retro Arcade Aesthetic**: Pixel font styling with glowing neon effects

## 🎯 How to Use

1. Open `evilinsults.pages.dev` in any modern web browser
2. Click **"SUMMON INSULT"** to fetch your first insult
3. After the first summon, the button changes to **"BURN ME MORE!"**
4. Toggle **VOICE** to enable/disable text-to-speech
5. Toggle **CACKLE** to enable/disable explosion effects and laughter
6. Watch your score climb and try to beat the high score!

## 🔧 Technical Details

### Technologies Used
- Pure HTML5, CSS3, and JavaScript (no dependencies)
- Web Speech API for text-to-speech
- LocalStorage API for persistent high scores
- Evil Insult API for content generation

### API Endpoint
```
https://evilinsult.com/generate_insult.php?lang=en&type=json
```

**Response Format:**
```json
{
  "number": "123",
  "language": "en",
  "insult": "Your insult text here...",
  "created": "2018-10-24 06:52:02"
}
```

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ⚠️ Requires JavaScript enabled
- ⚠️ Text-to-speech availability varies by browser/OS

## 🎨 Visual Effects

### Animations
- **Fire Breathing**: 4-second pulsing flame effect
- **Flame Flicker**: 2-second alternating secondary flames
- **Floating Embers**: 30 particles with 8-second ascent
- **Grid Pulse**: 3-second hell grid glow
- **Button Pulse**: 2-second glowing effect
- **Title Flame**: 2.5-second flickering text

### Color Palette
```css
--hell-red: #ff2400
--lava-orange: #ff6a00
--sulfur-yellow: #ffd000
--ash-gray: #bfbfbf
--void-black: #050000
```

## ⚙️ Customization

### Adjust Cooldown Period
Change the cooldown between insults (default: 3 seconds):
```javascript
const COOLDOWN = 3000; // milliseconds
```

### Modify Ember Count
Change the number of floating embers (default: 30):
```javascript
for (let i = 0; i < 30; i++) {
  // ember creation code
}
```

### Change Explosion Particles
Add or remove emojis from the explosion effect:
```javascript
const emojis = ['🔥','💀','😈','🩸','🪦','⚰️','🕯️','👹','☠️'];
```

### Adjust Voice Settings
Modify the speech synthesis parameters:
```javascript
msg.rate = 1.05;   // Speed (0.1 to 10)
msg.pitch = 0.85;  // Pitch (0 to 2)
msg.volume = 0.9;  // Volume (0 to 1)
```

## 🎭 Easter Eggs

- Score persists across sessions using localStorage
- Wake Lock API prevents screen sleep during gameplay
- Responsive emoji selection for hell particles
- Backdrop blur effect on the main container
- Grid perspective transform for 3D floor effect

## 📝 Credits

- **Insults**: Powered by [EvilInsult.com API](https://evilinsult.com/)
- **Fonts**: 
  - Press Start 2P (Google Fonts)
  - Righteous (Google Fonts)
- **Concept**: Retro arcade meets hellscape aesthetics

## ⚠️ Disclaimer

This application generates offensive and insulting content for entertainment purposes only. The insults are fetched from a third-party API and do not reflect the views of the developer. Use responsibly and be mindful of your audience.

**Content Warning**: Contains profanity and offensive language.

## 📜 License

Free to use and modify. No attribution required.

---

**🔥 DESCENT INTO MADNESS AWAITS 🔥**

*Built with dark magic and CSS animations*
