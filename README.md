# Grid Dynamics Code Challenges: Operation High Vantage

Welcome to the first challenge. You have **1.5 hours** to complete it. 

## The Scenario
You are building the data processing pipeline for a fleet of high-altitude survey drones. The drones return altitude data as arrays of integers, but the sensors occasionally glitch, recording negative numbers that must be ignored. 

## The Challenge (3 Levels)
This is a **progressive** coding challenge. You are expected to build upon and refactor your code as you advance through the levels. **Do not copy-paste monoliths; reuse your functions.**

* **Level 1 (Target: 15 mins):** Write two functions: `cleanData(arr)` to filter out any negative altitude readings, and `findPeak(arr)` to find the highest altitude in the cleaned array.
* **Level 2 (Target: 30 mins):** Build upon Level 1. Write `calculateElevationGain(arr)`. This function must take raw drone data, clean it, and calculate the total upward climb (sum of all positive altitude changes between consecutive points).
* **Level 3 (Target: 45 mins):** The system now receives an array of arrays (multiple drone flight paths). Write `findSteepestPath(matrix)`. Identify and return the specific flight path that has the highest continuous elevation gain. *Your solution must be highly optimized for Time and Space complexity.*

## Instructions
1.  Navigate into your preferred language folder (`/Python`, `/Java`, or `/JS_TS`).
2.  Write your code inside the respective `Level_1`, `Level_2`, and `Level_3` directories.
3.  Commit your code frequently. Our automated test suite will run on every commit.

## Submission
When you are finished (or when the 1.5-hour timer is up):
1. Create a new branch called `submission`.
2. Commit your final code to this branch.
3. Open a **Pull Request** from `submission` into `main`. **Do not merge it yourself.**
