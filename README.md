```bash
# EASY_OCR
#### Text Detection From Images Using EasyOCR
```

```bash
JAIDED- AI(OCR Owner) uses the OCR mainly to Extract key informations from
ID Card / Passport / Identification Document.
Suitable to incorporate into KYC processing.
```
```bash
#### If you need to check simple text in the images you can use the OCR library available on 
[easy_ocr](https://pypi.org/project/easyocr/).
```
```bash
## 1. REQUIRED LIBRARIES - 
- Run these commands to install [pytorch](https://pytorch.org/get-started/locally/).

!pip install torch torchvision torchaudio
!pip install easyocr
```
```bash
import easyocr
import cv2
import matplotlib.pyplot as plt
import numpy as np
```

```bash
## 2. Upload the Image from which you require text.

![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/surf.jpeg)
```
```bash
## 3. Run the Library.

Read the image using easyocr module and store the results into variable.
```

```bash
## 4. View the Text

Use the saved result to display on the image itself to rectify.

![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/surf_with_text.png)
```
```bash
## 5. Use it to check for multiple text Images.

![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/sign.png)
![Image](https://github.com/Mohshaikh23/EASY_OCR/blob/main/sign_with_text.png)
```