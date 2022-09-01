# Predictive_maintenance_ML

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
Target: failure or no failure (to perform binary classification).
Failure Type: type of failure (to perform multiclass classification).

It also includes the following information, which is not useful for building the models:
UID: unique identifier ranging from 1 to 10000.
ProductID: the id of the product.
