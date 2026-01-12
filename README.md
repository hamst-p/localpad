# Localpad

A simple, privacy-focused memo pad that runs entirely in your browser.

## Features

- **No Server** - Everything runs locally in your browser
- **No Database** - Data stored in browser's LocalStorage
- **No Tracking** - Zero analytics or data collection
- **No Login** - Just open and start writing
- **Offline Ready** - Works without internet connection

## How to Use

1. Open `memo.html` in your browser
2. Write your memo (first line becomes the title)
3. Press `Save Memo` or use keyboard shortcut
4. Your memos are automatically saved locally

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `⌘ + Enter` (Mac) | Save memo |
| `Ctrl + Enter` (Windows/Linux) | Save memo |

## Input Format

```
Shopping List
Milk
Eggs
Bread
```

The first line becomes the **title**, and the rest becomes the **content**.

## Data Storage

All memos are stored in your browser's LocalStorage under the key `memo-pad-memos`. Data persists until you clear your browser data or manually delete memos.

## Tech Stack

- Pure HTML, CSS, JavaScript
- No external dependencies (except Google Fonts)
- Single file application

## Browser Support

Works on all modern browsers:
- Chrome / Edge
- Firefox
- Safari

## License

MIT
