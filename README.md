# Grid Dynamics Code Challenge: Operation High Vantage

Welcome to your technical assessment. You have **1.5 hours** to complete this challenge. 

## The Scenario
You are building the data processing pipeline for a fleet of high-altitude survey drones. The drones return altitude data as arrays of integers, but the sensors occasionally glitch, recording negative numbers that must be ignored. 

## The Challenge (3 Levels)
This is a **progressive** coding challenge. You are expected to build upon and refactor your code as you advance through the levels. **Do not copy-paste monoliths; reuse your functions.**

* **Level 1 (Target: 15 mins):** Write two functions: `cleanData(arr)` to filter out any negative altitude readings, and `findPeak(arr)` to find the highest altitude in the cleaned array.
* **Level 2 (Target: 30 mins):** Build upon Level 1. Write `calculateElevationGain(arr)`. This function must take raw drone data, clean it, and calculate the total upward climb (sum of all positive altitude changes between consecutive points).
* **Level 3 (Target: 45 mins):** The system now receives an array of arrays (multiple drone flight paths). Write `findSteepestPath(matrix)`. Identify and return the specific flight path that has the highest continuous elevation gain. *Your solution must be highly optimized for Time and Space complexity.*

---

## How to Write and Test Your Code
Because you are working in a secure, compute-less web editor (`github.dev`), **you do not have a local terminal.** Instead, you will use GitHub Actions as your automated testing pipeline.

### Step-by-Step Testing Workflow:
1. **Choose Your Language:** Navigate into your preferred folder (`/Python`, `/Java`, or `/JS_TS`) and write your logic for Level 1.
2. **Commit Your Code:** Click the "Source Control" icon on the left sidebar, type a commit message, and click **Commit & Push**.
3. **Open a New Window:** Right-click the hamburger menu (≡) in the top-left corner of the editor and select **"Open link in new window"**. This will open the standard GitHub interface.
4. **Check Your Tests:** In the new window, click the **Actions** tab. Click on your most recent commit to see the live test logs. The automated grader will show you exactly which unit tests passed or failed.
5. **Iterate:** Use the taskbar at the bottom of your screen to easily swap back and forth between your code editor window and your test results window. Commit frequently to check your progress!

---

## Final Submission
When you have completed all three levels (or when the 1.5-hour timer is up):
1. Ensure all your final code is committed and pushed.
2. Create a new branch called `submission`.
3. Open a **Pull Request** from your `submission` branch into `main`. 
4. **Do not merge the Pull Request yourself.** Leave it open. Our AI Review Agent will automatically grade your PR for modularity and complexity.
