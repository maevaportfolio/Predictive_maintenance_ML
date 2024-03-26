# Predictive_maintenance_ML

![image](https://github.com/maevaportfolio/Predictive_maintenance_ML/assets/108234726/976d27c7-c857-44ff-9730-b0cf2d910005)


This predictive maintenance project focuses on the analysis and interpretation of real industry data to identify potential equipment failures before they occur. By leveraging a machine learning model, this project aims to classify equipment based on their risk of failure, utilizing six key features and targeting two specific outcomes.

[➡️ dataset](https://www.kaggle.com/datasets/stephanmatzka/predictive-maintenance-dataset-ai4i-2020)

This dataset reflects real predictive maintenance encountered in the industry with measurements from real equipment. The features description is taken directly from the dataset source.

### **The six features are:**
* Type: the quality of the product, consisting of a letter L, M, or H. Meaning low, medium, and high, respectively.
* Air temperature [K]: generated using a random walk process later normalized to a standard deviation of 2 K around 300 K.
* Process temperature [K]: generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature
plus 10 K.
* Rotational speed [rpm]: calculated from power of 2860 W, overlaid with a normally distributed noise.
* Torque [Nm]: torque values are normally distributed around 40 Nm with an Ïƒ = 10 Nm and no negative values.
* Tool wear [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process.

### **The targets are:**
* Target: failure or no failure (to perform binary classification).
* Failure Type: type of failure (to perform multiclass classification).


### Objectives 

The project aims for two main objectives:

- **Target**: Identify whether equipment will experience a failure or not (binary classification). This allows for the prevention of unexpected shutdowns and proactive planning of maintenance interventions.  
- **Failure Type**: Determine the type of failure (multiclass classification). This helps diagnose specific problems and apply the correct corrective measures.  

### Project Stakes  

The main stake of this predictive maintenance project is to reduce costs and optimize operations by preventing failures before they occur. By identifying at-risk equipment in advance, businesses can better plan maintenance operations, reduce machine downtime, and extend their equipment's lifespan. This also ensures consistent quality production, avoiding unexpected interruptions that can affect the supply chain and customer satisfaction.

By integrating these data into a machine learning model, the project aims to provide an analytical and data-driven approach to maintenance decision-making, marking a significant evolution from traditional reactive methods.
