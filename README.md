# ASTRA — Custom New Tab

ASTRA is a minimal, modern, and customizable new tab page designed to make browsing feel cleaner and more focused.

It displays the current time, date, local timezone, search bar, useful shortcuts, theme switching, and a distraction-free focus mode.

## Features

- Live digital clock
- Current date display
- Automatic timezone detection
- Google search functionality
- Quick links to:
  - YouTube
  - GitHub
  - Figma
  - Discord
- Dark and light themes
- Theme preference saved using local storage
- Focus mode for a distraction-free experience
- Command palette using `Ctrl + K` or `Cmd + K`
- Keyboard shortcut for focus mode using `F`
- Responsive design for desktop and mobile
- Custom CSS with no website builder
- No backend or database required

## Preview

ASTRA uses a clean dark interface with subtle background effects, large typography, and simple controls.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Local Storage API

## How to Run

1. Download or clone this repository.

2. Open the project folder.

3. Open `index.html` in your browser.

No installation or setup is required.

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + K` | Open command palette |
| `Cmd + K` | Open command palette on Mac |
| `F` | Toggle focus mode |
| `Esc` | Close command palette |
| `Enter` | Select a command |

## Project Structure

```text
ASTRA/
│
├── index.html
└── README.md
```

## Customization

You can customize ASTRA by editing the CSS variables inside `index.html`.

```css
:root {
  --bg: #0a0a0c;
  --text: #f5f3ef;
  --muted: #77777f;
  --line: #24242a;
  --card: #111115;
  --accent: #d6ff4b;
}
```

You can also change the shortcut links, logo, colors, fonts, and displayed text.

## Future Improvements

- Custom background image support
- Weather widget
- To-do list
- Notes section
- More shortcut customization
- Search engine selection
- Productivity statistics
- Browser extension version

## License

This project is open source and available for personal and educational use.
