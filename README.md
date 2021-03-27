# Textract

* The main motive behind this project was that we often faced the problem of separately typing any content instead of copy-pasting from an already existing document or image which are not in typed format.

* Hence, a text extractor which would simply scanning and extracting the content of the file would save loads of time and also reduce the chances of typographical error to 0%.

## Flow of the Application

* Our system takes the scanned image/document from the user as an input.

* Then perform some image pre-processing techniques, like scaling, binarization and noise removal.

* Use Optical Character Recognition using [Tesseract Engine](https://github.com/tesseract-ocr/tesseract) and extract the text.

