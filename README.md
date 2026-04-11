# Targeted Design - Interactive Org Chart

## For Investment Presentations

---

## 🚀 How to Use

### Open the Presentation
```bash
# Option 1: Open in browser directly
open presentation/org-chart.html

# Option 2: Start a local server
cd presentation
python3 -m http.server 8080
# Then open http://localhost:8080/org-chart.html
```

### During Presentation

1. **Click any team member** - Their profile slides in from the right
2. **Click the X or press Escape** - Close the profile
3. **Click "Fullscreen" button** - Enter fullscreen mode for presentations
4. **Click "Fullscreen" again** - Exit fullscreen

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Interactive Cards** | Click any person to see full details |
| **Slide-in Panel** | Professional detail panel with mission, responsibilities, vibe |
| **Fullscreen Mode** | Perfect for projection in meetings |
| **Keyboard Support** | Press Escape to close detail panel |
| **Dark Theme** | Professional look for investment meetings |

---

## 👥 Team Members Included

| Name | Title |
|------|-------|
| Alex Sterling | CEO |
| Nova Reyes | COO |
| Levi Jones | Co-Founder (Human) |
| Jordan Taylor | Executive Assistant |
| Sage Mitchell | Head of Research |
| River Castillo | Head of Sales |
| Iris Chen | Head of Design |
| Quinn Foster | Head of QA |
| Echo Hayes | CFO |
| Atlas Warren | Head of R&D |

---

## 🎨 Customization

### Edit Team Data
Open `org-chart.html` and find the `teamData` object in the `<script>` section. Edit any field:

```javascript
const teamData = {
    alex: {
        name: "Alex Sterling",
        title: "Chief Executive Officer",
        mission: "...",
        responsibilities: [...],
        vibe: "...",
        // etc.
    },
    // ... other team members
};
```

### Change Colors
Edit the CSS variables in the `<style>` section:

```css
/* Main gradient background */
background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);

/* Accent colors */
color: #00d9ff;  /* Cyan */
color: #00ff88;  /* Green */
```

---

## 📱 Browser Support

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

---

## 🎯 For Investors

**This shows:**
- Complete executive team structure
- Clear role definitions
- AI-first approach (9 AI agents, 1 human)
- Professional presentation ready

**Key Talking Points:**
- Traditional agency: 8 employees = $600K+/year
- Targeted Design: 8 AI agents + 1 human = $426/year
- 99.9% cost reduction in human capital

---

_Created: April 9, 2026_
_Alex Sterling (CEO) | Targeted Design_