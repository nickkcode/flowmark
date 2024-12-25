# Flowmark

![Flowmark Logo](https://via.placeholder.com/100x50?text=Flowmark)

Flowmark is a Chrome extension that transforms your new tab page into an elegant and organized space for managing bookmarks. With a user-friendly interface and powerful search functionality, it ensures quick and effortless access to your favorite web pages.

---

## Features

- **Bookmark organization**: Categorize and display your bookmarks like apps for easy access.
- **Search bar**: Quickly find bookmarks with an intuitive search bar.
- **Customizable layout**: Arrange bookmarks to suit your preferences.
- **Clean UI**: Minimalistic and distraction-free interface.
- **Lightweight**: Designed for speed and efficiency.

---

## Installation

1. Download or clone the repository:
   ```bash
   git clone https://github.com/yourusername/flowmark.git
   cd flowmark
   ```

2. Open Chrome and navigate to `chrome://extensions/`.

3. Enable **Developer mode** (toggle switch in the top-right corner).

4. Click on **Load unpacked** and select the project folder.

5. Flowmark is now installed and ready to use. Open a new tab to see it in action.

---

## Project Structure

```
flowmark/
├── src/             # Source files for the extension
│   ├── popup/       # Popup HTML, CSS, and JS
│   ├── newtab/      # New tab page HTML, CSS, and JS
│   └── utils/       # Utility functions
├── icons/           # Extension icons
├── manifest.json    # Chrome extension manifest file
└── README.md        # Documentation
```

---

## Usage

1. Open a new tab in Chrome.
2. Add, edit, or delete bookmarks directly from the new tab page.
3. Use the search bar to find bookmarks instantly.
4. Customize the layout to suit your workflow.

---

## Development

1. Make changes to the source files in the `src/` directory.
2. Reload the extension in Chrome:
   - Go to `chrome://extensions/`.
   - Click the **Reload** button for Flowmark.
3. Test your changes by opening a new tab.

### Building the Extension

If you want to package the extension:

1. Zip the project folder.
2. Navigate to `chrome://extensions/`.
3. Click on **Pack extension** and upload the zipped file.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any inquiries or support, please contact [nickkcode@gmail.com](mailto:nickkcode@gmail.com).

---
