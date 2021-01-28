### Prerequest 

### Windows
On Windows
download binary from https://github.com/UB-Mannheim/tesseract/wiki. then add pytesseract.pytesseract.tesseract_cmd = 'C:\Program Files (x86)\Tesseract-OCR\tesseract.exe' to your script.

### Linux (Ubuntu/Mint/Any Deb based)
#### Installing Tesseract Binaries
```bash
sudo apt-get update
sudo apt-get install libleptonica-dev 
sudo apt-get install tesseract-ocr libtesseract-dev
```
#### Run this before running this program
```bash
pip install -r requierments.txt
```


### To run program
Make sure your source images available in Images directory (in mycase pyinfo.png)

```bash
python  tesseract.py --image Images/pyinfo.png
```