# Predicting Speed

With today’s cycling computers and smart sensors, bicyclists are able to capture a rich collection of data from each ride. GPS units provide high-resolution positional data, which translates directly into speed, distance, and elevation profiles. Additional sensors capture the rider’s power output, cadence, heart rate, respiratory rate, and more. Together, these telemetry data enable precise monitoring, comparative analysis, and the optimization of training strategies.

This notebook is all about *speed*. In particular, I explore how well we can predict a rider's speed based on the available telemetry.   

Intuitively, we know the harder that a rider pedals, the faster they go. But there are multiple other factors that could affect their speed. If a rider is climbing a hill, for example, much of their power is needed to overcome gravity. A rider who is standing&mdash;not sitting&mdash;is able to generate greater torque on the pedals, but their overall pedal stroke may be less efficient. To determine the best predictors of speed, I build a linear model and use feature selection to explore many of the available data channels.
