# Udacity Deep Learning Nanodegree Project 1 - Bike Sharing Patterns

i have completed this project as part of my Udacity Deep Learning Nanodegree program requirment in April 2020. 

## Getting Started

### About Dataset
This Bike-Sharing-Dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. You can see the first few rows of the data above.

Below is a plot showing the number of bike riders over the first 10 days or so in the data set. (Some days don't have exactly 24 entries in the data set, so it's not exactly 10 days.) You can see the hourly rentals here. This data is pretty complicated! The weekends have lower over all ridership and there are spikes when people are biking to and from work during the week. Looking at the data above, we also have information about temperature, humidity, and windspeed, all of these likely affecting the number of riders. You'll be trying to capture all this with your model.

### Requirements
Basic requirements to run the project are as follows,
 - Numpy
 - Jupyter Notebook
 - Matplotlib
 - Pandas

However if you wish you install every  package I have in my environment, use `pip install -r requirements.txt` in the root directory of cloned project. 
####  Environment
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

### How to run the project?
The  project is located in the jupyter notebook file  `Predicting_bike_sharing_data.ipynb`  and it's include the training an the prediction part. The neural network is implemented in the file  `my_answer.py`  and used from the jupyter notebook.

### Training Parameters
```
# Hyperparameters
iterations = 5000
learning_rate = 0.5
hidden_nodes = 20
output_nodes = 1
```
## Training Results

`Progress: 100.0% ... Training loss: 0.055 ... Validation loss: 0.139`

### Training and Validation loss
![Training and Validation Loss](https://github.com/ManzarIMalik/project-bikesharing/blob/master/assets/Training_Validation_loss.png)

### Prediction Graph
![Prediction graph](https://github.com/ManzarIMalik/project-bikesharing/blob/master/assets/Precdictions.png)

### Udacity Rubric Results
![Udacity Rubric Results]([https://github.com/ManzarIMalik/project-bikesharing/blob/master/assets/UdacityRubric.png])

### Author

 - [Manzar Iqbal Malik](https://www.linkedin.com/in/manzarimalik)