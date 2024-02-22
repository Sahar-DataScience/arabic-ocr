# arabic-ocr
parsing arabic key words using ocr

parsing specific keywords from arabic administrative documents using ocr :

step 1 : applying preprocessing  techniques to guarantee better results

step 2 : extract the txt using ocr tools:
  1 - easy ocr vs tesseract :
  better result are made by tesseract

step 3 :  extracting the specific key words using nltk tools like : 
  stemming using nltk.stem.SnowballStemmer as it supports arabic

step 4 : wrap the previous parts in app using flask, the app take as input a jpg image and return the parsed words
