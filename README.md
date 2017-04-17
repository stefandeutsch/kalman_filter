# We can use a time series of energy system data and produce an estimate of unknown system states using Kalman Filtering. The estimations converge over time despite measurement noise, and tend to be more accurate than estimates based on a single data point. Kalman filters augmented for parameter estimation can accurately learn and predict a building’s thermal response to changing weather and occupancy, saving significant energy. 

# This Kalman filter algorithim will use an ordinary differential equation solver, where the rate of change of the system states (dx/dt) depends on time, the value of the states, and a variety of input data.
