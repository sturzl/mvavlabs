 # Three Components  Part 3 - Sensors
So you've now made a robot. It thinks and does all on its own using a control algorithm and some motor control code. The final step is to make it autonomous by adding some sensor input for the control algorithm. This will comes from a sensor on the car instead of the Sensor person in your group.

1. Change the control code to take input from the camera function. It outputs the same information as the Sensor.
2. See if the car can move to the goal! This will definitely take trial and error. (Hint 1: The camera code will give you feedback once a second. Don't move the car more than once every 4-5 seconds) (Hint 2: try to use the stop function when the robot is in mid turn, or make the turns a much smaller) (Hint 3: Wait for the camera to give you the same feedback a few times in a row before you decide what action to take)
3. You've now implemented a sensor! Usually this is tough because sensors rarely just provide data like "warm" or "cold". Often they have errors and say "I don't know", "warm" when the robot isn't doing the right thing, or "warmcoldwarmwarmcoldwarm" all at once because of noise.

# Congratualtions you've just made an autonomous robot!
