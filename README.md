# NYU ACS Reading Group Website

A modern GitHub Pages website for tracking Advanced Computer Science reading group topics and resources.

## Features

- **Topic Tracking**: Visual cards for covered and upcoming reading topics
- **Reading Resources**: Easy access to papers, notes, and discussion summaries
- **Search Functionality**: Find topics by title, description, or tags
- **Responsive Design**: Works on all devices
- **Dynamic Content**: JavaScript-powered for easy updates

## Setup

1. **Enable GitHub Pages**:
   - Go to repository settings → Pages
   - Select "Deploy from a branch" → `main` branch → `/ (root)`
   - Site will be available at: `https://[username].github.io/nyu-acs-website/`

## File Structure

```
nyu-acs-website/
├── index.html          # Main website
├── styles.css          # Styling
├── script.js           # Content management
└── september_2025/     # Reading group resources
    ├── guidelines/     # Reading group guidelines
    ├── readings/       # Reading lists
    ├── discussions/    # Discussion notes
    ├── templates/      # Note templates
    ├── schedule/       # Meeting schedule
    └── [topic folders]/
```

## Usage

### Add Reading Topics
Edit `script.js` or use browser console:
```javascript
addNewTopic("Title", "Description", ["tags"], "Date");
```

### Mark Topic Complete
```javascript
markTopicAsCompleted("Topic Title");
```

### Add Resources
1. Create folders in `september_2025/`
2. Add reading notes, discussion summaries, templates
3. Update `resources` array in `script.js`

## Development

1. Clone repository
2. Open `index.html` in browser
3. Make changes
4. Push to GitHub

---

**Built for NYU ACS Reading Group**
