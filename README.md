# Personal Portfolio — GitHub Pages Template

A clean, dark-themed academic/researcher personal page inspired by [inoryy.com](http://inoryy.com/).

## 🚀 Quick Start

1. Create a new GitHub repo named `yourusername.github.io`
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source: Deploy from branch → main**
4. Your site will be live at `https://yourusername.github.io` in ~1 min

## ✏️ Customise

Open `index.html` and search for the following placeholders:

| Placeholder | Replace with |
|---|---|
| `Your Name` | Your full name |
| `Your Institute / Company` | Where you work/study |
| `you@example.com` | Your email |
| `yourusername` | Your GitHub / Twitter / LinkedIn handle |
| `YOURKEY` | Your Google Scholar user key |
| Blog post cards | Your actual posts |
| Project cards | Your GitHub projects |
| Talks list | Your presentations |
| Teaching list | Your TA courses |

### Adding a Photo

1. Create an `img/` folder and put `avatar.jpg` inside it
2. In `index.html`, replace the `<div class="avatar-placeholder">` block with:
   ```html
   <img src="img/avatar.jpg" alt="Your Name">
   ```

### Adding a CV

Put your PDF at `files/cv.pdf` and the nav link will work automatically.

## 📁 Recommended File Structure

```
yourusername.github.io/
├── index.html
├── img/
│   └── avatar.jpg
└── files/
    └── cv.pdf
```

## License

MIT — use freely.
