# FrenchDrivingOCR-

A Draft code to extract Text from new french driving licence using 
 1. [EasyOCR](https://github.com/JaidedAI/EasyOCR)
 2. Opencv 
 3. uvicorn

 ## Result
 
 ![Image](https://github.com/geekette86/FrenchDrivingOCR-/blob/master/screenshot.png)
 
 # To do
  1. Convert it to api with flask 
  2. Better result 

 # FastAPI
 Start the application:
- uvicorn main:app --reload
To test using *curl*:
- curl -F "file=@test.png" localhost:8000/upload