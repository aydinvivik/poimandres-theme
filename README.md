<p align="middle">
  <img src="assets/dots.png" />
  <img src="assets/screencap.png" />
  <img src="assets/screencap-bright.png" />
</p>

Poimandres is a minimal, frameless dark-theme inspired mostly by [blueberry](https://github.com/peymanslh/vscode-blueberry-dark-theme). This theme tries to focus on semantic meaning instead of color variety. You'll find that it colors things like errors, voids, throws and deletes in red, types are slighty darker so that the spotlight is on the code, green new's, etc.

It comes in four variants: basic, brighter (storm), and two non-italic variants.

The screencap above uses the following settings:

```json
{
  "workbench.colorTheme": "poimandres",
  "workbench.iconTheme": "quill-icons-minimal",
  "workbench.productIconTheme": "icons-carbon",
  "editor.renderIndentGuides": false,
  "editor.renderWhitespace": "none",
  "editor.minimap.renderCharacters": false,
  "editor.fontSize": 13.5,
  "editor.fontFamily": "Menlo",
  "window.zoomLevel": 0.5,
}
```

#### Contribute

    git clone https://github.com/drcmda/poimandres-theme
    cd poimandres-theme
    npm install
    npm run dev

Go to `Run and Debug`, click the ▶ icon, any change you make in `src/theme.js` will now be reflected when you save.
