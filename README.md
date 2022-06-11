# tandur-ml
## Prerequisites
### Running Locally
### Installing Python
Make sure you have Python installed on your machine.<br> 
<br>When you want to run the code, you may want to use the standard Python library venv to create a virtual environment and have all dependent packages to install and serve from the local project directory to avoid messing with system wide packages and their versions.</br>
### Installing Dependencies
Install all the dependencies required for the project by running the following lines:
- pip install numpy
- pip install pandas
- pip install seaborn
- pip install matplotlib
- pip install tensorflow
- pip install keras
- pip install scikit-learn
- pip install pathlib
### Running Remotely
If you want to run the code directly in your browser without installing locally, you can use Jupyter Notebook or Google Colab. If you want to change code and experiment with notebooks, you will need to make a copy of the notebook on your machine.
### Set Dataset Path
Set the path of the Crop_recommendation.csv dataset by selecting the path to save the csv file on your machine.</br>
```python
pd.read_csv('[Your Path]/Crop_recommendation.csv')
```
### INTRODUCTION
Most of the time, a problem that is often faced by farmers is crop failure. As farmers cannot predict the future's environmental conditions, we can make an application that can automatically recommend farmers to farm the best crop by using machine learning. In this case, we consider more than 3 features, such as temperature, precipitation, and humidity. To make realistic predictions, we can train data with many features to recommend farmers more properly.<br>

<br>We will use Python as the programming language for making DNN models. In this case, we use geospatial data from Kaggle to predict crop recommendation based on three features, those are Temperature, Precipitation, Humidity. Then, we will classify all the predictions based on the land's evaluation table.</br>

### Dataset
Containing 22 labels to classify, where we got 100 data for each label, including:
- rice
- maize
- chickpea
- kidneybeans
- pigeonpeas
- mothbeans
- mungbean
- blackgram
- lentil
- pomegranate
- banana
- mango
- grapes
- watermelon
- muskmelon
- apple
- orange
- papaya
- coconut
- cotton
- jute
- coffee
### TECHNOLOGIES
This project is built using Deep Learning Technology with Convolutional Neural Network algorithm and Transfer Learning. Here are the library that used in this project.
•	Python 3.7.12
•	TensorFlow 2.6.3
•	NumPy 1.21.6
•	Matplotlib 3.5.1
### LAUNCH
We use fixed model: 
```python
crop-recommendation-prediction.ipynb
```



