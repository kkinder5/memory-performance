# memory-performance

Predicting Human Memory Performance
Summary
This project uses data from my dissertation project (see https://trace.tennessee.edu/utk_graddiss/8126/, Experiment 1)

Data were collected by recruiting 36 participants, who performed a memory task with mouse-tracking in-person.

Participants performed a memory task where they were shown either 2, 3, 4, or 5 objects containing different colors. After a brief delay, participants responded with a mouse-cursor, clicking the upper-left or upper-right button to state whether one of the colors changed or if they all remained the same. The outcome variable is whether they Rememember or Forgot the objects in memory. See the link above for more details.

Goal: Predict human memory performance based on relevant features
Database Schema
Number of attributes: 9800 rows and 4 columns

Outcome Variable:

Memory Performance - Remembered or Forgotten
Feature Information:

Memory Storage - The number of objects held in memory, either 2,3,4 or 5
Speed - Amount of time to click a response (in milliseconds)
Initiate Move Time - Time taken to begin moving the mouse-cursor (in milliseconds)
These features were obtained using the MouseTracker software (http://www.mousetracker.org/)
