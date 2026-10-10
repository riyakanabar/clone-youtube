# YouTube Homepage Clone

A static, responsive recreation of a YouTube-style video browsing homepage built with HTML and CSS. The page includes a fixed top header, a compact navigation sidebar, and a grid of sample video cards.

## Features

- Header with menu and logo, search input, search and voice-search buttons, a Create button, notification badge, and profile image
- Sidebar navigation links for Home, Shorts, Subscriptions, and You
- Nine sample video cards with thumbnails, durations, channel images, titles, author names, and view/date details
- Responsive video grid: two columns on screens up to 750px, three columns from 751px to 1499px, and four columns at 1500px and wider
- Hover styling for video cards and sidebar links, plus tooltips on search, voice search, and notifications
- Roboto typography loaded from Google Fonts

## Run locally

No build tools, package installation, or server are required. Open `youtube.html` in a web browser.

## Project structure

```text
.
├── youtube.html                 # Page markup and sample video content
├── channel-pictures/            # Channel avatars and profile image
├── icons/                       # SVG logos and interface icons
├── styles/
│   ├── general.css              # Global page styles
│   ├── header.css               # Fixed header and controls
│   ├── sidebar.css              # Sidebar navigation
│   └── video.css                # Responsive video grid and cards
└── thumbnails/                  # Sample video thumbnail images
```

## Limitations

This is a front-end layout demo. The search field, navigation items, and buttons are visual interface elements; there is no JavaScript, video playback, search, or account functionality. Google Fonts requires an internet connection; the page falls back to Arial if Roboto is unavailable.

## Credits

Created as an HTML and CSS practice project. YouTube branding and sample content are used for interface demonstration.
