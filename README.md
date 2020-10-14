# Handwritten-Digit-Recognition-using-python
A python program for handwritten digit recognition.

Programming language used:  
Python using scikit learn module. 

Problem type: 
Classification based problem. 

Classifier used: 
Decision Tree Classifier. 

Dataset: 
“Keggle” site used as a source for dataset.
Total: 42000 records of pixels of different images of handwritten digits(0-9). 
Training set consists of first 50% records. 

Got to learn converting an excel sheet's entry (pixel values) into an image, also converting an image into and excel sheet entry i.e storing the pixel values. 

Image of a single hand written digit is passed as input.

<img src='https://github.com/sonalisaraswat/Digit-Recognition-using-python/blob/master/aa.jpg' width="60%" height="200">


***Outputs:***
***The input image is coverted to a row of pixels, which is stored in the excel sheet "array.csv", this is now converted into a 28*28 pixel image.***

<img src = "https://github.com/sonalisaraswat/Digit-Recognition-using-python/blob/master/Figure_1.png" width="60%" height ="200">

The data from this excel sheet is used to predict the digit written in the input image, using the "decision tree classifier".

<img src="https://github.com/sonalisaraswat/Digit-Recognition-using-python/blob/master/Capture.PNG" width="300">

# Instruction For Running This in your PC:<br>

***Install The Required Modules by giving folllowing Command***<br>
```pip3 install -r requirements.txt```<br>

***Now Run This Final Command In YoUR pc***<br>
```python3 Minor.py```<br>