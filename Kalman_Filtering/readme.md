# Kalman Filters Applied to Sensor Fusion in Self-Driving Cars
Have you ever wondered why self-driving cars have many sensors?
What goes behind the scene in combining this sensory information for the actual operation of the vehicle?

Here is my attempt to give you a short view of how we estimate:
    1. Position
    2. 3D Orientation
    3. Velocity

Using the information from:
    1. IMU - Inertial Measurement Unit.
    2. GNSS - Global Navigation Satellite System.
    3. LIDAR - Light Detection and Ranging.

Error-State Extended Kalman Filter (ES-EKF) for State Estimation using IMU, GNSS & LIDAR sensors

    · Accelerometer and gyroscope readings come from the IMU, integrating IMU readings leads to dead-reckoning positioning systems, which drift with time.

    · To avoid drift we fuse this information with absolute position readings such as GPS or vision/LIDAR.

    · In this project, IMU biases are not considered and quaternion is used to represent the orientation in space

ES-EKF is one of the tools we may use for this purpose within the KF paradigm. It allows overcoming possible parameter singularities and gimbal lock issues.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ii5cZERYFuw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
