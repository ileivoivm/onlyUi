# Postbotany UI

**Path Builder is Deployed**

The Path Builder tool for this project is deployed at:  
[https://polypathsui.up.railway.app/](https://polypathsui.up.railway.app/)

Feel free to visit and try it out.

---

**Test Page: ui.html**

`ui.html` is a local test page designed for embedding the Path Builder via iframe and enabling remote interaction.

### Main Features

- **Three Buttons:**
  - `generate-seed`: Sends a "generateURL" command to the Path Builder to generate a compressed URL.
  - `redraw`: Sends a "reset" command to the Path Builder to clear the canvas.
  - `view-seeds`: Reserved for future features.
- **iframe Embedding:** Loads the Path Builder using `<iframe src="index.html">` for direct interaction.
- **Interaction Details:**
  - The buttons use the postMessage API to send commands to the Path Builder inside the iframe.
  - The Path Builder (`index.html`) automatically sends a postMessage with type: `newPath` and a decoded compressed hash string (payload is `#data_xxx...`) to the parent window (`ui.html`) whenever the path or points change.
  - The parent window can listen for and receive the latest compressed data in real time, making it easy to sync, display, or store.


---

**Related Links**

- Online Path Builder:  
  [https://polypathsui.up.railway.app/](https://polypathsui.up.railway.app/) 