# pdf-ocr-racetrack

comparing all* the ocr methods for a pdf

## pdf to ocr processes included

(each as separate script)

1. pypdfocr
2. ocrmypdf
3. PyPDF2
4. QPDF
5. 
6. tika-python (dependancy is JAVA :sadface:)

### pypdfocr

<https://github.com/virantha/pypdfocr>

Broken for 3.8.x Python apparantly.

### ocrmypdf

<https://github.com/jbarlow83/OCRmyPDF>

`brew install ocrmypdf` worked fine on my macbook.

Example: `ocrmypdf ~/Downloads/scanned.pdf fixed.pdf`

### tika-python

<https://github.com/chrismattmann/tika-python>
