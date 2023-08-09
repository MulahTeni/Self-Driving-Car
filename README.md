# **Self-Driving Car Project**
In this repository, we are going to try to code a simple self-driving car project.

###**Collecting Data**
We will use Udacity Self-driving Car Simulator for collecting data and later simulating our self-driving car model.
<p align="center">
<img src="simulation.png" alt="Simulation" style="height: 300px; width:800px;"/>

**Steps:**
* Download Udacity Self-driving Car Simulator and run. You can use the following link: https://github.com/udacity/self-driving-car-sim
* Select preffered track and click on 'TRAINING MODE' as shown below.
<p align="center">
<img src="1.png" alt="Simulator" style="height: 600px; width:800px;"/>


* Click on record and start driving as shown below. Min 3 laps recommended.
<p align="center">
<img src="2.png" alt="Training" style="height: 600px; width:800px;"/>


* Save the path for recorded data.


or just use the pre prepared data from https://github.com/rslim087a/track

###**Training Model**
Our models architecture will be NVIDA's model and we will use Google Colab for proccess everthing faster. NVIDA's model is shown below.
<p align="center">
<img src="model.png" alt="Model" style="height: 700px; width:505px;"/>


**Steps:**
* Set up imports.
* Preproccess the data.
* Create the model architecture.
* Train the model with preproccessed data.
* Save the trained model for later use.

###**Testing Trained Model**
We will use conda to connect the trained model and Udacity simulator.

**Steps:**
* Create a file to use the model for driving.
* Create a conda environment and connect to the environment.
* Run python file
* Open simulator, select track and click on 'AUTONOMUS MODE'

###**Simulation Video**


###**References**
* Mariusz Bojarski, Ben Firner, Beat Flepp, Larry Jackel, Urs Muller, Karol Zieba and Davide Del Testa (2016). End-to-End Deep Learning for Self-Driving Cars. NVIDIA Developer. https://developer.nvidia.com/blog/deep-learning-self-driving-cars/
* Chris Gundling. (2017, January 21). Udacity self driving car P3 - NVIDIA vs. VGG style on track 1 [Video]. Youtube. https://www.youtube.com/watch?v=hUp1T83X8f4
