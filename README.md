# arabic-ocr
## parsing arabic key words using ocr

**parsing specific keywords from arabic administrative documents using ocr :**

1. step 1 : applying preprocessing  techniques to guarantee better results

2. step 2 : extract the txt using ocr tools:
   - **easy-ocr** vs **tesseract** vs **Trocr by hugging face** : better result are made by tesseract.

4. step 3 :  extracting the specific key words using nltk tools like :
   - stemming using nltk.stem.SnowballStemmer as it supports arabic

5. step 4 : wrap the previous parts in app using flask, the app take as input a jpg image and return the parsed words
