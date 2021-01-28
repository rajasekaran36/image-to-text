# Image to Text using Tesseract
## Step 1:
### Prerequest 
#### Windows
On Windows
download binary from https://github.com/UB-Mannheim/tesseract/wiki. then add pytesseract.pytesseract.tesseract_cmd = 'C:\Program Files (x86)\Tesseract-OCR\tesseract.exe' to your script.

#### Linux (Ubuntu/Mint/Any Deb based)
#### Installing Tesseract Binaries
```bash
sudo apt-get update
sudo apt-get install libleptonica-dev 
sudo apt-get install tesseract-ocr libtesseract-dev
```
## Step 2:
#### Run this before running tesseract.py
```bash
pip install -r requierments.txt
```

## Step 3:
### To run program
Make sure your source images available in Images directory (in mycase pyinfo.png)

```bash
python  Tesseract.py --image Images/pyinfo.png
```
