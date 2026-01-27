# 📚 Word Wall Generator

A free, browser-based tool to create printable vocabulary cards with English, Spanish, and Chinese translations, plus educational images from Wikimedia Commons.

## ✨ Features

- **Multilingual**: Automatic Spanish and Chinese translations
- **Educational Images**: Free images from Wikimedia Commons
- **Customizable**: Edit translations, add custom images, choose colors
- **Print-Ready**: Two landscape cards per page (11" x 8.5")
- **No Backend Required**: 100% client-side, runs anywhere
- **Completely Free**: No API keys or registration needed

## 🚀 Quick Start

### Option 1: Use Locally
1. Download `word-wall-generator-public.html`
2. Open in any web browser
3. Enter your words and click "Generate Cards"
4. Print or save as PDF

### Option 2: Deploy to Web

#### GitHub Pages (Recommended)
```bash
# 1. Create a new repository
# 2. Upload word-wall-generator-public.html as index.html
# 3. Enable GitHub Pages in Settings > Pages
# 4. Your site will be live at: https://yourusername.github.io/word-wall
```

#### Netlify
1. Go to https://app.netlify.com/drop
2. Drag and drop the HTML file
3. Get instant URL: `yoursite.netlify.app`

#### Vercel / Cloudflare Pages
Similar process - just upload the HTML file!

## 📖 How to Use

1. **Enter Topic**: e.g., "Geoscience", "Chemistry", "Biology"
2. **Choose Color**: Pick a border color for your cards
3. **Add Words**: One word per line (10 words recommended)
4. **Generate**: Click "Generate Cards" (takes ~30 seconds per 10 words)
5. **Customize**:
   - Hover over text → Click ✏️ to edit translations
   - Hover over images → Click 🖼️ for custom URL, 🔄 for different image
6. **Print**: Click "Print/Save PDF" and save or print

## 🎨 Example Word Lists

### Geoscience
```
Crust
Mantle
Core
Plate
Lithosphere
Volcano
Earthquake
Magma
```

### Chemistry
```
Atom
Molecule
Element
Compound
Reaction
Catalyst
```

## 🛠️ Technical Details

- **Translation API**: MyMemory (free, no key required)
- **Image Source**: Wikimedia Commons API (free, educational use)
- **Fallback Images**: Lorem Picsum (placeholder service)
- **Size**: Single 27KB HTML file
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## 🔧 Customization

The HTML file contains all code and can be easily modified:

- **Add more fallback translations**: Edit the `fallbackTranslations` object (line ~390)
- **Change colors**: Modify CSS gradient (line ~13)
- **Adjust card layout**: Edit `.card` styles (line ~450+)
- **Add more languages**: Extend `translateText()` function

## 📝 License

MIT License - Free to use and modify for personal or commercial use.

## 🙏 Credits

- **Images**: Wikimedia Commons contributors
- **Translations**: MyMemory Translation API
- **Created by**: Eldon Chou (2026)

## 🐛 Known Limitations

- Translation quality varies (use edit button to fix)
- Image relevance depends on Wikimedia availability
- Requires internet connection for translations and images
- Print formatting may vary slightly by browser

## 💡 Tips

- Use specific topics (e.g., "Earth Science" not just "Science")
- Review translations before printing - some may need editing
- Custom image URLs work great for specific diagrams
- Save your word lists in a text file for reuse

## 🆘 Troubleshooting

**Images not loading?**
- Check internet connection
- Try clicking the 🔄 refresh button
- Use custom image URL (🖼️)

**Translations look wrong?**
- Click the ✏️ edit button to fix manually
- Common scientific terms are pre-loaded with correct translations

**Print formatting issues?**
- Use Chrome or Firefox for best results
- Select "Landscape" orientation when printing
- Set margins to "None" in print dialog

## 📧 Support

For issues or suggestions, create an issue on GitHub or contact the creator.

---

**Ready to create educational word walls?** 🎓
Just open the HTML file and start building!
