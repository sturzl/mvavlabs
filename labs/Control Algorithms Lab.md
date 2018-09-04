# Intro to control algorithms
## [See it in action!](https://www.youtube.com/watch?v=ZRSFsq6A5L4)
* **Intro material**
  * https://www.youtube.com/watch?v=4Y7zG48uHRo
  * Note: The same concepts apply to controlling anything, not just cars: Robots, airplanes, etc
  * PID was invented by a US Navy sailor tasked with autonomously steering boats. He derived the P, I and D terms by watching helmsman steer boats. His 1922 system was better than the sailors, but was not implemented due to resistance from sailors.
* Install the IDE and test the car
  * Install the OpenMV IDE https://openmv.io/pages/download 
  * Grab the code from github and put it in the ide: https://github.com/Sashulik/Detroit-Autonomous-Vehicle-Group/tree/master/02-OpenMV 
  * Run it on the car (Ask someone for a quick how to)
* Modify the PID (look for !!! in the code)
  * Run it and see how it goes
  * Modify the code by the !!! to make it fail
  * Modify the code so it succeeds but is different the the original values
* Get the car to follow a different color line
* Optimize for faster lap time (Until you’re bored)
  * Switch to inside color
  * Increase car speed
  * Tune the PID to handle the new speed. Read the below links if you’re REALLY interested in PID
    * https://en.wikipedia.org/wiki/PID_controller#Manual_tuning
    * https://robotics.stackexchange.com/questions/167/what-are-good-strategies-for-tuning-pid-loops
    * https://www.crossco.com/blog/basics-tuning-pid-loops
    * http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.623.275&rep=rep1&type=pdf
* Learn about a control algorithm for an autonomous car
  * Model Predictive Control (MPC)
    * https://www.youtube.com/watch?v=8U0xiOkDcmw
    * https://www.youtube.com/watch?v=cEWnixjNdzs
