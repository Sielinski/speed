# Predicting Speed

With today’s cycling computers and smart sensors, bicyclists are able to capture a rich collection of data from each ride. GPS units provide high-resolution positional data, which translates directly into speed, distance, and elevation profiles. Additional sensors capture the rider’s power output, cadence, heart rate, respiratory rate, and more. Together, these telemetry data enable precise monitoring, comparative analysis, and the optimization of training strategies.

This notebook is all about *speed*. 

Intuitively, we know the harder that a rider pedals, the faster they go. But there are multiple other factors that could affect speed. If a rider is climbing a hill, for example, much of their power is needed to overcome gravity. A rider who is standing&mdash;not sitting&mdash;is able to generate greater torque on the pedals, but their overall pedal stroke may be less efficient. 

To understand the relationship between speed and these&mdash;and other&mdash;factors, I built a linear model to predict a rider's speed based on the data recorded by a Garmin Edge.
