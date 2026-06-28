# -podcast-explorer-wavecast
Team Project:  Podcast Explorer - Wavecast

**FUTM-SWE-221 | Group 17 Project**

A web app for searching and browsing podcasts using the free iTunes Search API.
No API key required. No backend. No build step. Open `index.html` and it works.

---

## Folder Structure

```
wavecast/
│
├── index.html          ← Entry point. Open this in a browser to run the app.
│
├── css/
│   ├── reset.css       ← Browser default style reset (margins, box-sizing etc.)
│   ├── style.css       ← Layout, topbar, views, tokens (CSS variables), typography
│   └── components.css  ← Card styles (featured, grid, list), episodes, saved view
│
└── js/
    ├── data.js         ← Static data: topic list, artwork colors, mock episode fallback
    ├── utils.js        ← Pure helper functions: getInitials, escapeHtml, truncate etc.
    ├── api.js          ← All iTunes API calls: searchPodcasts, lookupPodcast, fetchEpisodes
    ├── render.js       ← HTML generation: renderResults, renderEpisodes, renderSaved etc.
    └── app.js          ← Main controller: state, event listeners, navigation, init
```
