# Earth Orbit and Close Approach Objects Analysis

This project aims to perform initial analysis on two datasets related to near-earth and in-orbit objects. How does the dataset change over the years? How do the different distances from Earth compare? What are the most common objects? How does the object density change? Can we observe future trends and predict how object types and density can change?

## Dataset Information:

Two datasets are used in the project: the first contains near-Earth objects that are passing close to Earth's orbit. The second includes objects that are in Earth's orbit.

## Objectives

The project will involve multiple data analyses, data pre-processing, exploratory data analysis, model training, and evaluation.

### Key Features to Consider
- Close Approach Date: Analyzing the frequency and timing of NEO approaches can reveal temporal patterns or trends.
- Miss Distance: This indicates how close the object comes to Earth, measured in astronomical units (AU), lunar distances (LD), or kilometers.
- Estimated Diameter: Provides insight into the potential impact severity if the object were to collide with Earth.
- Relative Velocity: The speed at which the NEO approaches Earth, which can affect the kinetic energy upon impact.
- Absolute Magnitude (H): A measure of the object's brightness, which can be used to estimate its size.
- Orbit Uncertainty: Reflects the confidence in the predicted orbit, with lower values indicating higher certainty.

### Identifying Patterns and Trends
To uncover meaningful patterns:
- Time Series Analysis: Plotting the number of close approaches over time can help identify any increases or decreases in NEO activity.
- Scatter Plots: Visualizing relationships between variables, such as miss distance versus estimated diameter, can highlight potentially hazardous objects.
- Histograms: Analyzing the distribution of NEO sizes or velocities can provide insights into the typical characteristics of these objects.
- Clustering: Applying clustering algorithms can group NEOs with similar attributes, potentially identifying common origins or behaviors.