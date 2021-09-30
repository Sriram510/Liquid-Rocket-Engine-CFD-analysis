# Liquid-Rocket-Engine-CFD-analysis
This repo contains the result of my experiments with liquid rocket engines by conducting computational fluid dynamics
## Steps include:-
###### 1. Choosing fuel and oxidiser for reliable and cost effective operation.
###### 2. Assumed requirements-thrust of 100kgs,no engine cooling, easily affordable propellants.
###### 2. Liquid oxygen(easily available and abundant), Butane(high vapour pressure and common used as stove gas) was opted to use.
###### 3. As the rocket engine is not being cooled, low O/F(oxidizer/fuel) ratio was chosen.
###### 4. After choosing the propellants and O/F ratio, CEA(Chemical Equilibrium with Application) results were obtained from RPA software by Alexander Ponomarenko.
###### 5. Engine temperature , pressure, mass flow rate, exit velocity etc. was obtained.
###### 6. After getting the contour from the RPA software, corresponding design mesh was made in Ansys 19.2 and results obtained are as follows:-
## Mach_Number along the nozzle axis:-![MachCont](https://user-images.githubusercontent.com/90887611/135408532-aa078598-1eaa-44cb-bd63-ced249eb6798.jpeg)
## Pressure-distrubution along the nozzle-![PressCont](https://user-images.githubusercontent.com/90887611/135408684-dc2c4e41-a301-49cf-93b1-6cd84b2a331f.jpeg)
## Gas-velocity along the nozzle:-![VelCont](https://user-images.githubusercontent.com/90887611/135408765-8146c105-892a-43c1-9471-6d415c7122b6.jpeg)
##Temperature-varations along the nozzle:-![TempCont](https://user-images.githubusercontent.com/90887611/135408891-67ab0cd9-cfcc-4f06-b08a-3b0abf6e7b5b.jpeg)
## Chamber Design that was chosen was given by-
![engine contour](https://user-images.githubusercontent.com/90887611/135410753-48fc51fe-528e-4ced-b446-525e3d0be59d.png)

**Hence a reliable engine without cooling complexity(though inefficient) simulation was successful, data of which can be used for further alterations in designs iteratively.**

**NOTE:-Highly beneficial for amateur rocketry
