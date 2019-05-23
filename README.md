# Character-Recognition (OCR)

#### Optical character recognition or optical character reader abbreviated as OCR, is the conversion of images of handwritten or printed text into machine-encoded text, whether from a scanned document, a photo of a document, a scene-photo (for example, a bill of products can be scanned and stored in the PC as a record).

*In this simple project, the text is scanned, boxed out and the message is detected.*

*It uses tesseract and East text detector deeplearning model.*

#### Tesseract

Tesseract is an optical character recognition engine for various operating systems. It is free software, released under the Apache License, Version 2.0, and development has been sponsored by Google since 2006.

#### East text detector model

East (abbreviation for Efficient and Accurate Scene Text Detector) is a deeplearning model. It basically detects the text in an image and 
gives the geometry (like top, bottom, right, left, offset pt.) and confidence scores. 

Links for better understanding:
* [Tom Hoag]<https://medium.com/@tomhoag/opencv-text-detection-548950e3494c>
* [Adrian from pyimagesearch]<https://www.pyimagesearch.com/2018/09/17/opencv-ocr-and-text-recognition-with-tesseract/>
* [Cornell University]<https://arxiv.org/abs/1704.03155>
