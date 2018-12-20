# Path Planning

This projects implements a simple path planning logic unit to navigate the vehicle in a high-way driving scenario.

<img src = "Path_Planning.gif" align="center" width = "800" hight = "600">

# Behavioural Planning Model Explantion
The behavioural planning model gets the infromation about the other vehicles on the from the sensor fusion module. The decisoun making is mainly based on the following three flag:

1) Car_ahead: Evaluates if there is a car ahead of our self-driving car.
2) Car_left: Evaluates if there is a car left of our self-driving car.
3) Car_right: Evaluates if there is a car right of our self-driving car.
