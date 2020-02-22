# satellite-orbit-prediction
Predicting the position of satellites is one of the big challenges in astronomy. More than 500,000 pieces of debris are tracked as they orbit the Earth. They all travel at speeds up to 28163.52 km/hour, fast enough for a relatively small piece of orbital debris to damage a satellite. If space debris hits the satellite it would result in the creation of more debris. According to NASA, there are more than 3,000 satellites currently revolving around the earth’s orbit. If most of these satellites are damaged as a result of space junk, it will result in the creation of more space debris that will lead to Kessler syndrome. The existing SGP4-simulator in the satellite predicts the position of the satellite before but it’s an approximation. The solution can be to create a machine learning model that learns from the historical publicly available data that contains simulated coordinate data and the true coordinate data and predicts the value which has less error as compared to SGP4-simulator. We will be using gradient boosting in this project. The machine learning model will lie somewhere in between the simulated value and the true value and thus will be suited well enough to improve the existing model. The accuracy of the existing model will be increased.
