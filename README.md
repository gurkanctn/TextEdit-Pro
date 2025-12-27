Text Edit Pro is a very simple text editor.

I needed a way to copy and save text to my mobile device (phone), and it usually takes a few extra steps (open the notes app, export as txt, go to file manager, rename the file to html, etc.) 

So I came up with the Text Edit Pro.

It's not a fancy editor, but it's quite practical.

Try it below:
https://gurkanctn.github.io/TextEdit-Pro/index.html

disclaimer: Prompted by a human, coded by an AI (DeepSeek in this case).

---

## 🛠️ Development

This is a single HTML file with no external dependencies (except Font Awesome CDN for icons). Everything is self-contained.

### Key Components

1. **User Interface**
   - Responsive toolbar with touch-friendly buttons
   - Full-screen text area
   - Status indicators
   - Modal dialogs

2. **File Operations**
   - Download-based saving (works across all browsers)
   - File input for opening files
   - Recent files tracking

3. **PWA Features**
   - Web app manifest
   - Service worker for offline caching
   - Install prompts

### To Modify

Since everything is in one file, you can:
1. Open the HTML file in any text editor
2. Modify styles in the `<style>` section
3. Change functionality in the `<script>` section
4. Update the manifest in the JSON section

## 🔒 Privacy & Security

- **No tracking**: No analytics, no data collection
- **No cloud**: Everything stays on your device
- **No permissions**: No special browser permissions required
- **Local only**: Files never leave your device

## ❓ FAQ

<details>
<summary><strong>Q: Where are my saved files stored?</strong></summary>
A: Files are saved to your device's Downloads folder. The exact location depends on your browser settings.
</details>

<details>
<summary><strong>Q: Can I edit files from Google Drive or iCloud?</strong></summary>
A: Yes! Open the file from your cloud storage, edit it, then save it back. The file will download to your Downloads folder.
</details>

<details>
<summary><strong>Q: Does it work completely offline?</strong></summary>
A: Yes! Once loaded, the app works 100% offline. You can even install it as a PWA for permanent offline access.
</details>

<details>
<summary><strong>Q: What's the file size limit?</strong></summary>
A: There's no hard limit, but very large files (10+ MB) might slow down the editor. It's best for typical text files.
</details>

<details>
<summary><strong>Q: Can I use it on desktop?</strong></summary>
A: Absolutely! It works on desktop browsers too, with full keyboard shortcut support.
</details>

<details>
<summary><strong>Q: How do I transfer files between devices?</strong></summary>
A: Since files save locally, you'll need to manually transfer them (email, cloud storage, USB) between devices.
</details>

## 📝 License

This project is provided as-is, free to use and modify for any purpose. No attribution required.

## 🤝 Contributing

Since this is a single HTML file, you can:
1. Fork the project
2. Make improvements
3. Create a pull request with your enhanced version

## ⚠️ Limitations

- Files are saved to Downloads folder (not arbitrary locations)
- No folder browsing (standard file picker only)
- No file watching (doesn't detect external changes)
- No syntax highlighting (plain text only)

## 📞 Support

If you encounter issues:
1. Check that your browser is up to date
2. Try a different browser (Chrome works best)
3. Ensure you have storage permissions enabled
4. Clear browser cache and reload

---

**Enjoy your simple, private, offline text editor!** ✨

<p align="center">
  <sub>Built with ❤️ for offline productivity</sub>
</p>
