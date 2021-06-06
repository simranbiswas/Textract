# Textract

* The main motive behind this project was that we often faced the problem of separately typing any content instead of copy-pasting from an already existing document or image which are not in typed format.

* Hence, a text extractor which would simply scanning and extracting the content of the file would save loads of time and also reduce the chances of typographical error to 0%.

## Application Link:

* Desktop Version (For images & PDF's) : [http://18.222.220.89:5000/](http://18.222.220.89:5000/)
* Mobile Version (Downloadable APK package only for images) : [https://drive.google.com/file/d/1JLeMwO4LZjzQcbgoA5ARX-z3L8OsZ4-M/view?usp=sharing](https://drive.google.com/file/d/1JLeMwO4LZjzQcbgoA5ARX-z3L8OsZ4-M/view?usp=sharing)

## Flow of the Application

* Our system takes the scanned image/document from the user as an input.

* Then perform some image pre-processing techniques, like scaling, binarization and noise removal.

* Use Optical Character Recognition using [Tesseract Engine](https://github.com/tesseract-ocr/tesseract) and extract the text.


## Usage Guidelines:

### 1. Desktop Version

* The link [http://18.222.220.89:5000/](http://18.222.220.89:5000/) lands on this page, where you can submit the file from which you want to extract text.
  <p>
    <img src="https://github.com/simranbiswas/Textract/blob/main/images/intro.PNG" width="500" height="250" title="intro">
  </p>
  
* After uploading and submitting a file, the result appear as shown in the image and you click on **Copy To Clipboard** to copy and use the text as you want. 
  <p>
    <img src="https://github.com/simranbiswas/Textract/blob/main/images/Capture.PNG" width="500" height="300" title="capt">
  </p>
  
  
### 2. Mobile Version

* After downloading the APK package from this [link](https://drive.google.com/file/d/1JLeMwO4LZjzQcbgoA5ARX-z3L8OsZ4-M/view?usp=sharing), install it in your device and start the app.
  <p align="center">
    <img src="https://github.com/simranbiswas/Textract/blob/main/images/app.png" width="175" height="300" title="app">
  </p>
  
* Upload an image and the results come out as follows. Then simply copy-paste the text and use it as per you requirement.
  <p align="center">
    <img src="https://github.com/simranbiswas/Textract/blob/main/images/result.png" width="175" height="300" title="result">   
    <img src="http://www.pngall.com/wp-content/uploads/2016/07/Arrow-Free-Download-PNG.png" width="100" height="100" title="arrow">   
     <img src="https://github.com/simranbiswas/Textract/blob/main/images/cc.png" width="175" height="300" title="cc">
  </p>
  
  
## Technology Used:

* Flask
* Tesseract OCR Engine
* TensorFlow, OpenCV
* Flutter
* AWS (Deployment)



  
  
