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


**Related Links**

- Online Path Builder:  
  [https://polypathsui.up.railway.app/](https://polypathsui.up.railway.app/) 