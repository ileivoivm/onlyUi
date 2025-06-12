# Postbotany UI

**Path Builder is Deployed**

The Path Builder tool for this project is deployed at:  
[https://polypathsui.up.railway.app/](https://polypathsui.up.railway.app/)

Feel free to visit and try it out.

---

**Test Page: ui.html**

The `ui.html` file in this directory is a test page for remote interaction with the Path Builder. Main features:

- **Three Buttons**:
  - `generate-seed`: Sends a "generate seed" command to the remote Path Builder.
  - `redraw`: Sends a "redraw" command to the remote Path Builder.
  - `view-seeds`: Reserved for future features.
- **iframe Embedding**: The page embeds the Path Builder via iframe for direct remote interaction.
- **Interaction**: The buttons use the postMessage API to send commands to the Path Builder inside the iframe for remote control.
- **Inspired by**: The interaction style is inspired by the demo video previously provided by verse.

---

**How to Use**

1. Enter this directory and start a local server (e.g., `npx serve` or `npx http-server`).
2. Open `ui.html` in your browser to see the three buttons and the embedded Path Builder.
3. Click the buttons to remotely trigger the corresponding Path Builder features.

---

**Dependencies & Deployment**

- This directory includes a `package.json` file. Run `npm install` to install dependencies.
- It is recommended to use `npx serve` for local static server, or deploy to Railway, Vercel, etc.

---

**Related Links**

- Online Path Builder:  
  [https://polypathsui.up.railway.app/](https://polypathsui.up.railway.app/) 