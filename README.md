
# EASY_OCR
#### Text Detection From Images Using EasyOCR

---
```

JAIDED- AI(OCR Owner) uses the OCR mainly to Extract key informations from
ID Card / Passport / Identification Document.
Suitable to incorporate into KYC processing.
```
---

>If you need to check simple text in the images you can use the OCR library available on [easy_ocr](https://pypi.org/project/easyocr/).


## 1. Required Libraries - 
- Run these commands to install [pytorch](https://pytorch.org/get-started/locally/).

`!pip install torch torchvision torchaudio `

- Run these commands to install [easy_ocr](https://pypi.org/project/easyocr/).

`!pip install easyocr `

- Run these commands to import Libraries

```
import easyocr
import cv2
import matplotlib.pyplot as plt
import numpy as np
```



## 2. Upload the Image from which you require text.

>![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/surf.jpeg)

## 3. Run the Library.

Read the image using easyocr module and store the results into variable.

## 4. View the Text

Use the saved result to display on the image itself to rectify.

>![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/surf_with_text.png)

## 5. Use it to check for multiple text Images.

>![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/sign.png)
>![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/sign_with_text.png)

---