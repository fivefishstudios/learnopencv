# Optical Character Recognition using PaddleOCR.
This repository contains code of our blog post Optical Character Recognition using PaddleOCR.

This code uses PaddleOCR to perform OCR on various scenarios like Receipts, ID-cards, Road signs and more. This repository also focuses on comparing various models provided by PaddleOCR that are PP-OCRv3, PP-OCRv2, SRN and NRTR.

## Requirements
- python-Levenshtein
- paddlepaddle-gpu
- paddleocr

## Notebooks
This repository contains two different notebooks for performing both the tasks as explained above.

- **[OCR_inference.ipynb](https://colab.research.google.com/github/sanyam83/learnopencv/blob/master/Optical%20Character%20Recognition%20using%20PaddleOCR/OCR_inference.ipynb)**: This notebook contains inference code of PaddleOCR. In this, PP-OCRv3 along with text detector, recognizer and angle classifier are tested on various real life scenarios.

- **[OCR_comparison.ipynb](https://colab.research.google.com/github/sanyam83/learnopencv/blob/master/Optical%20Character%20Recognition%20using%20PaddleOCR/OCR_comparison.ipynb)**: This notebook conatins the comparison code of the models provided by PaddleOCR toolkit. In this PP-OCRv3, PP-OCRv2, SRN and NRTR are tested on COCO text dataset. 

## Output examples
![receipt](https://github.com/sanyam83/learnopencv/blob/master/Optical%20Character%20Recognition%20using%20PaddleOCR/output_images/06-receipt1-output.jpg)
![id](https://github.com/sanyam83/learnopencv/blob/master/Optical%20Character%20Recognition%20using%20PaddleOCR/output_images/10-id-card-output.jpg)
# AI Courses by OpenCV

Want to become an expert in AI? [AI Courses by OpenCV](https://opencv.org/courses/) is a great place to start. 

<a href="https://opencv.org/courses/">
<p align="center"> 
<img src="https://www.learnopencv.com/wp-content/uploads/2020/04/AI-Courses-By-OpenCV-Github.png">
</p>
</a>
