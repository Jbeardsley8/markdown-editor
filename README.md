# Markdown Live Editor

A lightweight web app that lets you write and preview Markdown in real time, with built‑in formatting tools and a handy cheatsheet.

## Features

* **Live Preview:** Instant rendering of Markdown as you type.
* **Formatting Tools:** Reset, Export (download `.md`), and Prettier-based Format buttons.
* **Font Size Toggle:** Cycle through four font sizes for comfortable editing.
* **Scroll Sync:** Editor and preview panes stay in sync.
* **Interactive Cheatsheet:** Quick reference for common Markdown syntax.

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/markdown-live-editor.git
   cd markdown-live-editor
   ```

2. **Open `index.html`**

   * Simply open the `index.html` file in your browser.
   * No build step or server required.

3. **Use the editor**

   * Type Markdown in the left pane. Your formatted document appears instantly on the right.
   * Click **✨ Format** to run Prettier on your Markdown.
   * Click **⬇️ Export** to download your content as `document.md`.
   * Click **🖊 Font M** to toggle font sizes.
   * Click **♻️ Reset** to clear the editor and local storage.

## Customization

* **Styling:** All CSS lives in the `<style>` block at the top of `index.html`. Adjust variables under `:root` for easy theme tweaks.
* **Markdown Parser:** Uses [markdown-it](https://github.com/markdown-it/markdown-it). You can enable plugins by editing the initialization in the `<script>` section.
* **Formatter:** Powered by [Prettier](https://prettier.io/). To adjust formatting rules, modify the options passed in the `formatBtn` click handler.

## License

This project is licensed under the MIT License. Feel free to use, modify, and share!
