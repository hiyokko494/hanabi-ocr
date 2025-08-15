# Tesseract Local Bundle (Option B)

Place these files to enable offline/robust OCR:

/tesseract/
  worker.min.js
  tesseract-core.wasm.js
  tesseract.min.js        (optional)
  lang-data/
    jpn.traineddata.gz
    eng.traineddata.gz

Open ../index.html in a browser. If the files exist, 「画像から解析」 will OCR.
Otherwise, use 「テキストから解析」 to proceed.
