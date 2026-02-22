# 🎨 Music App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Music-6C5CE7?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Energy](https://img.shields.io/badge/Energy-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Music Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Electric Purple | `#6C5CE7` | `hsl(248, 53%, 63%)` | Primary brand, creativity | ████ |
| Vibrant Green | `#00A86B` | `hsl(156, 100%, 33%)` | Playlists, fresh content | ████ |
| Deep Black | `#0A0A0A` | `hsl(0, 0%, 4%)` | Background, immersion | ████ |
| Pure White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Text, icons | ████ |
| Electric Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Links, interactive | ████ |
| Coral Orange | `#FF6B4A` | `hsl(14, 100%, 64%)` | Highlights, CTAs | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Electric Purple** | Creativity, Magic | Brand identity |
| **Vibrant Green** | Fresh, New | New releases, playlists |
| **Deep Black** | Immersive, Sophisticated | Now playing screen |
| **Electric Blue** | Trust, Action | Links, buttons |
| **Coral Orange** | Energy, Play | Play buttons, highlights |

## 💻 Implementation

```css
:root {
  --music-primary: #6C5CE7;
  --music-primary-dark: #5A4AC7;
  --music-accent: #00A86B;
  --music-background: #0A0A0A;
  --music-surface: #1A1A1A;
  --music-text: #FFFFFF;
  --music-link: #4A90E2;
  --music-highlight: #FF6B4A;
}

.now-playing {
  background: var(--music-background);
  color: var(--music-text);
  min-height: 100vh;
}

.play-button {
  background: var(--music-primary);
  color: white;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 4px 20px rgba(108, 92, 231, 0.4);
  transition: transform 0.2s;
}

.play-button:hover {
  transform: scale(1.1);
}

.playlist-item {
  background: var(--music-surface);
  border-radius: 8px;
  padding: 12px;
  margin: 4px 0;
  border-left: 3px solid transparent;
}

.playlist-item:hover {
  border-left-color: var(--music-primary);
}

.new-badge {
  background: var(--music-accent);
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 10px;
  font-weight: bold;
}
