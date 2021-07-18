# Longitudinal (PID) & Latitudinal Control (Stanley) for Self-Driving Cars

GOAL: To track the desired trajectory & desired velocity set up on the racetrack in CARLA

1.	PID controller for longitudinal control.
2.	Stanley controller for latitudinal control 

Stanley Controller:
1. It is a Non-Linear control law for an automobile to autonomously track a trajectory for latitudinal control.
2. Existing methods can suffer from a lack of global stability and a lack of tracking accuracy.
3. It treats automobile trajectory tracking in a new manner, by considering the orientation of the front wheels not the vehicle’s body w.r.t desired trajectory, enabling collocated control of the system for which global asymptotic stability is proven.
4. It was implemented on a Volkswagen Touareg, “Stanley”, the Stanford Racing Team’s entry in the DARPA Grand Challenge 2005, a 132 mi autonomous off-road race

video: video: https://youtube.com/embed/J2OgfHaDjxc
