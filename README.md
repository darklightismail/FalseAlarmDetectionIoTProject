# Real-time False Alarm Detection with AI


In order to determine whether a fire alarm should sound, this project introduces a
smoke detector based on AI sensor fusion. We first start by building a fire alarm detection
system in order to be used to collect the data. Then we train our data and build a machine
learning model to predict if there is a fire or not in order to set the alarm. And finally,
we implement our model in the Arduino.

The Arduino Uno board serves as the system’s foundation. In fact, most sensors are
redundant for safety reasons, ensuring operation even if one sensor malfunctions.
Three distinct requirements are the focus of this project : Cut down on false alarms
using AI sensor fusion. Detect sensor flaws and errors. The Arduino board calculates all
AI model and process tasks which ensure that will be no latency.
