# chrome-ext-vue-tooltip-translator

Mouse Tooltip Translator **Chrome Extension** using `Vue` + `Vuetify`

![Chrome Web Store](google.png)

**`ocr`, `tesseract`, `opencv`, `pdfjs`, `vuetify`**

## Features

- Hover or select (highlight) on text to translate
- Use left ctrl to Listen pronunciation with google TTS (text to speech)
- Use right alt to translate writing text in input box (or highlighted text)
- Google translator and bing translator are used for translation
- Support pdf to display translated tooltip using PDF.js
- Support dual subtitles for youtube video
- Process OCR when hold left shift and mouse over on image (ex manga)
- Translate with Speech recognition

## Build yourself to install

1. Install node js, <https://nodejs.org/en/> , node 18
2. open terminal and type below

```bash
$ git clone https://github.com/devmaster518/chrome-ext-vue-tooltip-translator.git
$ cd chrome-ext-vue-tooltip-translator

$ npm install
$ npm run build
# or 'npm run watch' for developing
```

3. You will see `./build` path
4. Open chrome browser and goto `chrome://extensions/`
5. Turn on top right corner developer mode
6. Open the folder (`./build`) as unpacked extension folder

---

&copy; 2024 @codeguru827

All Rights Reserved.
