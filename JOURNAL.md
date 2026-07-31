# Robotic arm project
## 14/07/26
### Planning
- I researched how robotic arms actually work and looked at some different examples.
- I was inspired by the Dobot magician's design and it's 3d printing function so established that my robotic arm will have a 3d printing nozzle as the head, rather than a grabber.

### Time: 1 hour

## 15/07/26
### Servo selection
- I decided on 5 axes, having the base and shoulder servos being the Feetech SCS215 due to its 19kg.cm torque, the elbow and wrist pitch servos being the Feetech SCS15 with 17kg.cm torque, and the wrist roll servo being the Feetech SCS0009.
- Since all these servos are smart serial servos they are able to have the wires connect into the servos, making a daisy-chain of wires, which will result in the arm having a cleaner look.

### Time: ~3 hours

## 18/07/26
### Rough design
- I created a rough sketch of the shape and wiring of the arm, as well as how the servos would be arranged inside of it.
- I also considered the idea of using 2 servos for the shoulder joint in case one would not be strong enough.
<img width="1080" height="395" alt="Screenshot_2026-07-28-18-23-27-891-edit_com android chrome" src="https://github.com/user-attachments/assets/54558ed3-1d97-45fe-8b7b-6aaa1817a46f" />

### Time: 1.5 hours

## 26/07/26
### CAD setup
- As this was my first time using CAD I took some time to learn how it worked and the basic controls.
- To begin modeling the robotic arm I imported the required servos into Onshape from Grabcad, however, some of the dimensions on the Feetech SCS215 were not accurate.
- I had to manually edit the CAD model to make it accurate but I was still unsure if the new model was correct because of the lack of information on the servo horn's dimensions.

### Time: ~2.5 hours

## 27/07/26
### Switching servos
- Because having a modified servo wasn't ideal and might ruin the project later on, I made a decision to replace the Feetech SCS215s and the Feetech SCS15s with the Feetech STS3215 because it had an accurate CAD model and included brackets which I would have had to make later on.
- The Feetech STS3215 is the same size and weight as the SCS215 but uses a magnetic encoder instead of a potentiometer which means that the servo will not degrade over time.
- I also replaced the Feetech SCS15 because the STS3215 was thinner and lighter with a greater torque.
<img width="756" height="533" alt="image" src="https://github.com/user-attachments/assets/064c78cb-8367-4ef4-95ad-d0c97623476c" />

### Time: ~1.5 hours

### Starting modeling
- I modeled the main base mount with a rectangular base and cone frustums layered above.
- The angled cutout on top of the frustrum ended up taking the longest time to make.
<img width="532" height="603" alt="image" src="https://github.com/user-attachments/assets/47badb9a-eb03-4bb2-a0bb-5dceaa01629e" />

### Time: 1 hour

## 28/07/26
### Parallel linkage
- Created a small linkage mechanism to learn how the revolute mate feature worked and to help me understand how parallel linkage would work in my arm.
<img width="1242" height="522" alt="image" src="https://github.com/user-attachments/assets/f7b8af0a-c3af-40c2-9cc3-f2aa60162f05" />

### Time: 1 hour

- Created a prototype to visualize how the robotic arm would have its joints controlled from the base.
- Having the servos in the base would mean a lighter arm which would reduce chance of servos not being strong enough and increase the weight it can lift, important for a heavy 3d printing nozzle.
<img width="512" height="314" alt="image" src="https://github.com/user-attachments/assets/054c53db-2c7b-4c45-b025-60349687bcfb" />

### Time: ~5 hours

## 29/07/26
### Refining prototype
- Since the system to keep the end effector always parallel to the ground was not working I had to modify some dimensions in the prototype.
- This led to all the revolute mates having an error, so I had to tediously reapply all joint mates.
- It still didn't work so I had to change even more and reapply all mates again.

### Time: 2 hours

## 30/07/26
### Experimental testing
- Created CAD models for different things where the lengths are actually reflective of what the real arm might have e.g. link connectors with correct sized screw holes.
- Created a prototype for remotely controlling the end effector (move it up and down) instead of just keeping it parallel to the ground.

### Time: 3 hours

## 30/07/26
### Designing the arm
- Started creating the CAD model for the final version of the arm.
- Needed to find different screws for different things like M3 screws to connect to the servo, and M4 shoulder screws as a pivot between 2 bars in the linkage mechanism.
- Had to factor in many different things when selecting screws like the type of steel, head length, diameter and cost.
<img width="933" height="602" alt="image" src="https://github.com/user-attachments/assets/1df54e81-2062-4e2f-98fa-8763c3088a8d" />

### Time: ~5 hours


