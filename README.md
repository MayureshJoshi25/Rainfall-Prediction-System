# Rainfall-Prediction-System
Rainfall prediction system using Python.

Dataset – From Kaggle – Name = Rainfall in India , Info: Sub-division wise monthly data for 115 years from 1901-2015.

PROCESS
 

![image](https://github.com/MayureshJoshi25/Rainfall-Prediction-System/assets/60180388/a5ea0ab0-4ebd-44d1-9c78-36d8e3de8e12)










STEPS:
CONNECTION TO HTML:
1.	 A user issues a request for a domain's root URL / to go to its index page
2.	main.py maps the URL / to a Python function
3.	The Python function finds a web template living in the templates/ folder.
4.	A web template will look in the static/ folder for any images, CSSfiles it needs as it renders to HTML
5.	Rendered HTML is sent back to main.py
6.	main.py sends the HTML back to the browser
URL IN THE BROWSER AND BACKEND CONNECTION:
1.	First. we imported the Flask class and a function render template.
2.	Next, we created a new instance of the Flask class.
3.	We then mapped the URL / to the function index(). Now, when someone visits this URL, the function index() will execute.
4.	The function index() uses the Flask function render template() to render the index.html template we just created from the templates/ folder to the browser.
5.	Finally, we use run() to run our app on a local server.
6.	We'll set the debug flag to true, so we can view any applicable error messages if something goes wrong, and so that the local server automatically reloads after we've made changes to the code.
7.	 When we visited http://127.0.0.1:5000/, main.py had code in it, which mapped the URL / to the Python function index().
8.	index() found the web template index.html in the templates/ folder, rendered it to HTML, and sent it back to the browser.

Important Libraries Used(Terminologies):

•	Pickle : Pickle is a useful Python tool that allows you to save your ML models, to minimise lengthy re-training and allow you to share, commit, and re-load pre-trained machine learning models. Most data scientists working in ML will use Pickle or Joblib to save their ML model for future use.
•	Numpy: NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices
•	Pandas: pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. 
•	Sklearn: scikit-learn is a free software machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support-vector machines
•	Flask: Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions. 
Technologies used:
•	Flask
•	Jupyter Notebook
•	Visual Studio Code
•	HTML, CSS, Bootstrap
•	Python

Algorithms used:
•	Linear Regression
•	Lasso
•	Ridge
•	SVM
•	Random Forest

