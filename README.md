# EASY_OCR
#### Text Detection From Images Using EasyOCR

<style>
div {
  background-color: #2ce904;
  padding: 10px;
}
</style>
<div>
JAIDED- AI(OCR Owner) uses the OCR mainly to Extract key informations from
ID Card / Passport / Identification Document.
Suitable to incorporate into KYC processing.
</div>

#### If you need to check simple text in the images you can use the OCR library available on 
[easy_ocr](https://pypi.org/project/easyocr/).

## 1. REQUIRED LIBRARIES - 
- Run these commands to install [pytorch](https://pytorch.org/get-started/locally/).

<style>
div {
  background-color: #FF7700;
  padding: 10px;
}
</style>
<div>
!pip install torch torchvision torchaudio<br>
!pip install easyocr<br>
</div>

<style>
div {
  background-color: #2596be;
  padding: 10px;
}
</style>
<div>
import easyocr<br>
import cv2<br>
import matplotlib.pyplot as plt<br>
import numpy as np<br>
</div>


## 2. Upload the Image from which you require text.

![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/surf.jpeg)

## 3. Run the Library.

Read the image using easyocr module and store the results into variable.

## 4. View the Text

Use the saved result to display on the image itself to rectify.

![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/surf_with_text.png)

## 5. Use it to check for multiple text Images.

![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/sign.png)
![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/sign_with_text.png)