# Truck-Backer-Upper
Directing and controlling the truck to a specific parking lot to unload is one of the non-linear control issues.
The purpose of this issue is to replace cars with humans to control vehicles. In this case, the truck starts from a desired point on the screen and moves in reverse gear to the parking lot until it is finally in the desired position and the work is completed.
The position of the truck in the environment is determined by three features:
1: 𝒙) The rear position of the truck on the plate
2: 𝜙) Truck angle with horizontal surface
3: 1) Steering angle
Relationship between variables through relationships:
1)x(𝑡 + 1) = 𝑥(𝑡) + cos[𝜙(𝑡) + 𝜃(𝑡)] + sin[𝜃(𝑡)] sin[𝜙(𝑡)]
2)𝜙(𝑡 + 1) = 𝜙(𝑡) − 𝑠𝑖𝑛−1[2sin[𝜃(𝑡)]/𝑏]

